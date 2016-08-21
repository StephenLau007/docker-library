FROM stephenlu/centos-ssh-root
ADD jdk-7u75-linux-x64.tar.gz /usr/local/
RUN mv /usr/local/jdk1.7.0_75 /usr/local/jdk1.7
ENV JAVA_HOME /usr/local/jdk1.7
ENV PATH $JAVA_HOME/bin:$PATH
