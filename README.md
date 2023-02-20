# argocd-test

## minikube start 5 nodes

```bash

minikube start --dry-run=true --driver=hyperv --nodes 5 --memory=4096 --cpus 4 --disk-size=40G --cni=calico --container-runtime=containerd --image-mirror-country="cn" --registry-mirror=https://hub-mirror.c.163.com --registry-mirror=https://docker.mirrors.ustc.edu.cn --image-repository=registry.cn-hangzhou.aliyuncs.com/google_containers --insecure-registry=registry.cn-hangzhou.aliyuncs.com --insecure-registry=registry.k8s.io
```
