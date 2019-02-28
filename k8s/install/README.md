1. 安裝版本 k8s 1.12.5

   ```bash
   yum makecache fast
   yum install -y kubeadm-1.12.5 kubelet-1.12.5 kubectl-1.12.5
   ```


1. 安裝 flannl 網路
kubectl apply -f  https://raw.githubusercontent.com/coreos/flannel/master/Documentation/kube-flannel.yml

kubectl delete -f  https://raw.githubusercontent.com/coreos/flannel/master/Documentation/kube-flannel.yml