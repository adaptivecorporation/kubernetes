# Multitenant NGINX Ingress - Bare Metal Kubernetes
Manifests included

Installation on bare-metal systems

Step 1. Install the NGINX controller

```bash
kubectl apply -f nginx-controller.yml
```

Step 2. Apply the ingress rules

```bash
kubecl apply -f ingress.yml
```
