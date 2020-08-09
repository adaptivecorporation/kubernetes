# Multitenant NGINX Ingress - Bare Metal Kubernetes
K8s Manifests

Installation on bare-metal

Step 1. Install the NGINX controller

```kubectl apply -f nginx-controller.yml
```

Step 2. Apply the ingress rules

```kubecl apply -f ingress.yml
```
