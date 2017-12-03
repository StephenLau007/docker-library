# docker
It have my test Dockerfile
## docker-library
搭建k8s集群for docker hub
### step
1.
2.docker hub build k8s base images
gcr.io/google_containers/kube-discovery-amd64:1.0
gcr.io/google_containers/kubedns-amd64:1.7
gcr.io/google_containers/kube-proxy-amd64:v1.4.1
gcr.io/google_containers/kube-scheduler-amd64:v1.4.1
gcr.io/google_containers/kube-controller-manager-amd64:v1.4.1
gcr.io/google_containers/kube-apiserver-amd64:v1.4.1
gcr.io/google_containers/etcd-amd64:2.2.5
gcr.io/google_containers/kube-dnsmasq-amd64:1.3
gcr.io/google_containers/exechealthz-amd64:1.1
gcr.io/google_containers/pause-amd64:3.0
## reference
> [kubeadm搭建kubernetes集群](https://mritd.me/2016/10/29/set-up-kubernetes-cluster-by-kubeadm/)
