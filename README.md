# ondrejsika-k8s-ingress (Kubernetes Ingress using Traefik)

    2019 Ondrej Sika <ondrej@ondrejsika.com>
    https://github.com/ondrejsika/ondrejsika-k8s-ingress

Simple way, how to setup Ingress with Let's Encrypt certificates & Prometheus Metrics.

## Install Traefik Ingress to Kubernetes

Apply locally

```
kubectl apply -f ingress-traefik.yml
```

or from Github's master

```
kubectl apply -f https://raw.githubusercontent.com/ondrejsika/kubernetes-ingress-traefik/master/ingress-traefik.yml
```
