# Kubernetes CIS benchmarks analysis

## Story

![msedge_epkPG8IGZO](../images/2023-05/msedge_epkPG8IGZO.png)

## Solution

```
kubectl apply -f scenarios/kube-bench-security/node-job.yaml

kubectl apply -f scenarios/kube-bench-security/master-job.yaml
```

![vmware_JtReZZnCIw](../images/2023-05/vmware_JtReZZnCIw.png)

```
kubectl logs -f kube-bench-node-xn74h
```

![vmware_jeDkpFHWdU](../images/2023-05/vmware_jeDkpFHWdU.png)

```
kubectl logs -f kube-bench-master-bbvbm
```

![vmware_wFqoQRCecP](../images/2023-05/vmware_wFqoQRCecP.png)

关于其它CIS的更多信息，请查看同目录下的**Docker CIS benchmarks analysis**这篇文章。