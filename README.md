# helm-deploy-Here-map

Deploy Here Maps with Kubernetes Helm chart



# run command 
```
helm template here-map . | kubectl create -f - -n dev
kubectl port-forward pod/<here-maps-xxxxx-xxx> 8081:8081 -n dev
```