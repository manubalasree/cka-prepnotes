## Fixing Broken Nodes
1. From Master find port
```
kubectl cluster-info
```

2. Find Node kubelet definition file
```
cd /etc/systemd/system/kubelet.service.d/
vi 10-kubeadm.conf
```
3. kubelet conf
```
vi /etc/kubernetes/kubelet.conf
```

