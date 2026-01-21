kubectl apply -f namespace.yml
kubectl config set-context --current --namespace=mateapp
kubectl apply -f clusterIp.yml
kubectl apply -f nodeport.yml
kubectl apply -f deployment.yml
kubectl apply -f hpa.yml

Go to browser: localhost:30007



