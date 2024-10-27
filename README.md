minikube start 
kind create cluster
kubectl apply -f leader-election-crd.yaml
kubectl apply -f leader-election-instance.yaml
kubectl get pods
 kubectl delete pod <pod name>
 kubectl get pods
 check for leader reelection
 kubectl apply -f redis-deployment.yaml     \
 kubectl exec -it <redis pod> -- redis-cli
 
