# Selectors

Taint the node

```
kubectl taint nodes node1 key1=value1:NoSchedule
```

untaint the node
```
kubectl taint nodes node1 key1=value1:NoSchedule- (give -)
example: kubectl taint nodes ip-192-168-44-96.ec2.internal hardware=gpu:NoSchedule-
```

label the node

```
kubectl label nodes <your-node-name> disktype=ssd
```
Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes/