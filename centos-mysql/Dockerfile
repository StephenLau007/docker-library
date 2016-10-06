FROM centos:centos7 
MAINTAINER hashaki  
   
RUN yum install -y mysql-server mysql  
   
RUN /etc/init.d/mysqld restart &&\  
    mysql -e "grant all privileges on *.* to 'root'@'%' identified by 'root';"&&\  
    mysql -e "grant all privileges on *.* to 'root'@'localhost' identified by 'root';"&&\  
    mysql -u root -proot -e "show databases;"  
   
EXPOSE 3306  
   
CMD ["/usr/bin/mysqld_safe"] 