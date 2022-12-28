minikube start --nodes 3 -p multinode-demo
kubectl get node --show-labels
kubectl label nodes multinode-demo-m03 disktype=ssd
kubectl label nodes multinode-demo-m03 disktype-
#pod will be schulde on node 3 