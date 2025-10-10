# Kubernetes Guestbook Project

A simple multi-tier web application using Kubernetes.

## Deploy
1. Start your cluster (e.g., minikube start).
2. Apply all YAMLs: kubectl apply -f .
3. Access the app: minikube service frontend-service (or use port-forward: kubectl port-forward svc/frontend-service 8080:80).

## View
- Pods: kubectl get pods
- Logs: kubectl logs <pod-name>
- Dashboard: minikube dashboard

## Cleanup
kubectl delete -f .
