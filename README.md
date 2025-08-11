# Kubernetes Minikube Task 5

## What I did:
- Installed Minikube and started cluster
- Created Deployment and Service YAML files
- Deployed nginx app with 2 pods
- Exposed app using NodePort service
- Accessed app via browser
- Scaled pods to 4
- Used kubectl describe and logs commands
- Performed rollback (if needed)
- Cleaned up resources

## Commands used:
- minikube start
- kubectl apply -f deployment.yaml
- kubectl apply -f service.yaml
- kubectl get pods
- kubectl get svc
- minikube ip
- kubectl scale deployment nginx-deployment --replicas=4
- kubectl describe pods
- kubectl logs <pod-name>
- kubectl rollout undo deployment/nginx-deployment
- kubectl delete -f deployment.yaml -f service.yaml
- minikube stop

# The documentation describes the steps I followed and includes screenshots.