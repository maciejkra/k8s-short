https://kubernetes.io/docs/concepts/configuration/secret/

https://kubernetes.io/docs/tasks/configure-pod-container/pull-image-private-registry/


```sh
kubectl create secret generic my-secret --from-file=./my-secrets --from-literal=user=marcin
kubectl get secret my-secret -o yaml
kubectl create -f pod-secret.yaml
kubectl logs secret-pod | grep USER
kubectl logs secret-pod | grep PASSWORD
```