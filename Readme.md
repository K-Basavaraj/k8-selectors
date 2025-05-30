# Selectors

Taint the node

```
kubectl taint nodes node1 key1=value1:NoSchedule
```

label the node

```
kubectl label nodes <your-node-name> disktype=ssd
```
Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes/