kubectl apply -f .\client-deployment.yml
kubectl apply -f .\mongo-deployment.yml
kubectl apply -f .

kubectl get pod
kubectl get all

kubectl logs

kubectl delete all --all