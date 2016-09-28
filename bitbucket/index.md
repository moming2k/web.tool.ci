---
layout: default
---

# BitBucket

Run BitBucket in Docker
```
$ kubectl apply -f http://www.tool.ci/bitbucket/run-my-bitbucket.yaml

$ watch kubectl get pods

$ watch kubectl get svc

# if use minikube, use below command to open browser

$ minikube service my-bitbucket
```