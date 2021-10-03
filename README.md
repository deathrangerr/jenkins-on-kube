# Kubernetes Manifests for Jenkins Deployment

# -> Clone this repo

# -> In volume.yaml change worke node01 to the hostname of your worker node where you want to deploy

# kubectl apply -f namespace.yaml
# kubectl apply -f volume.yaml
# kubectl apply -f serviceAccount.yaml
# kubectl apply -f deployment.yaml
# kubectl apply -f service.yaml



# -> Clean the cluster
# kubectl delete -f service.yaml
# kubectl delete -f deployment.yaml
# kubectl delete -f serviceAccount.yaml
# kubectl delete -f volume.yaml
# kubectl delete -f namespace.yaml
