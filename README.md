# ensf400-lab8-kubernetes-2

## Objective
This lab is for scheduling, configmaps, canary and blue-green deployment strategies of Kubernetes. Through Minikube, a simplified Kubernetes engine running on a single computer.

## Environment


```bash
$ minikube start --nodes 3 -p ensf400
```

This step will start the Minikube service with 3 virtual nodes, stored in a profile called `ensf400`. If for some reason your Codespaces instance was stopped (e.g., not using it for a while). You can restart the minikube service using this profile by running:

```bash
$ minikube start -p ensf400
```
