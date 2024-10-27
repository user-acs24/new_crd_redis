kind create cluster 
minikube start 
ubectl apply -f leader-election-crd.yaml
ubectl apply -f leader-election-instance.yaml
kubectl delete pod
kubectl delete pod <pod name>
kubectl delete pod
check for reelection
