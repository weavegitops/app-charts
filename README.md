# app-charts
A Git repostiory for demo apps

Add your helm chart sources to the charts directory.

You can use this HelmRepository to define the associate Helm Repository in your Weave Gitops environment. 

```
apiVersion: source.toolkit.fluxcd.io/v1beta1
kind: HelmRepository
metadata:
  name: weaveworks-charts
  namespace: flux-system
spec:
  interval: 1m
  url: https://weavegitops.github.io/app-charts/
```
