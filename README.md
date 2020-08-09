# Multitenant NGINX Ingress - Bare Metal Kubernetes

Installation on bare-metal systems

Step 1. Install the NGINX controller

```bash
kubectl apply -f nginx-controller.yml
```

Step 2. Apply the ingress rules

```bash
kubectl apply -f ingress.yml
```
