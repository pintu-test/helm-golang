## Helm Golang

Setup service be-golang-service manifest and deploy to Kubernetes Cluster, with:
  - Autoscalling
  - Export service with Load Balancer
  - Limit resource cpu: 100m and memory: 128Mi

You can access this services from public with load balancer, and this IP http://34.101.210.225:8080

## Running Command

Install or Upgrade
```bash
helm upgrade  --install be-golang-service ./helm-golang --values ./helm-golang/values.yaml -n pintu
```


## References
  - https://helm.sh/docs/helm/helm_create/
  - https://keel.sh/docs/#policies
