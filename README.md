# k8s

FROM k8s.gcr.io/kube-apiserver:latest

FROM k8s.gcr.io/kube-controller-manager:latest

FROM k8s.gcr.io/kube-scheduler:latest

FROM k8s.gcr.io/kube-proxy:latest

FROM k8s.gcr.io/pause:latest

FROM k8s.gcr.io/etcd:latest

FROM k8s.gcr.io/coredns/coredns:latest
