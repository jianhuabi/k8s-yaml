
```bash
kubectl run curl --image=tutum/curl --generator=run-pod/v1 --command -- sleep 9999
```

```bash
kubectl run dnsutils --image=tutum/dnsutils --generator=run-pod/v1 --command -- sleep infinity
```