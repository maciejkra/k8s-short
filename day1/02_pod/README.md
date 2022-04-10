1. Create pod with python application from image `krajewskim/python-api:new`
2. Port forward and check `/healthz` & `/docs` endpoint (application works on port 5002)
3. Check logs

```sh
kubectl logs <pod-name>
```

4. Describe pod

```sh
kubectl describe pod <pod-name>
```