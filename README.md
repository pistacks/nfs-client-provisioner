# nfs-client-provisioner
Kubernetes NFS Client Provisioner on ARM

## Usage

```
$ kubectl apply -f manifests/rbac.yml
$ kubectl apply -f manifests/deployment-arm.yml
$ kubectl apply -f manifests/class.yml
$ kubectl apply -f manifests/pvc.yml
$ kubectl apply -f manifests/pod.yml
```

## Instructions

The [original source](https://github.com/kubernetes-retired/external-storage) can be found [here](https://github.com/kubernetes-retired/external-storage) and more detailed instructions can be found on [this blogpost](https://blog.pistack.co.za/kubernetes-nfs-client-provisioner-on-arm/)
