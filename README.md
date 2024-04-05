# k8sサンプル

## Commands

```
k get pods
k logs POD名
k get svc
k config view
k apply -f foo.yaml
k scale --replicas=3 -f foo.yaml
k delete -f foo.yaml
```

### コンテナ起動

```
kubectl run test -it --restart=Never --image=busybox /bin/sh
```
