# result
Result app 

kubectl config set-context --current --namespace=vote

helm install -f helm/result.yaml result helm/result

helm uninstall result

kubectl get pods -n vote
