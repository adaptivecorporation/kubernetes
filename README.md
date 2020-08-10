# Multitenant NGINX Ingress Controller - Bare Metal Kubernetes

Installation on bare-metal systems

Step 1. Install the NGINX controller

```bash
kubectl apply -f nginx-controller.yml
```

Step 2. Apply the ingress rules

```bash
kubectl apply -f ingress.yml
```

Step 3. Configure firewall / routing rules and open port 80 (and 443) and point it to the speicified node port. You can find the node ports with this command:

```bash
kubectl get svc -n ingress-nginx
```

To find the node that the ingress service is running on, use this command:

```bash
kubectl get pods -n ingress-nginx -o wide 
```
