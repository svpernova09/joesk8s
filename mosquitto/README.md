# HAproxy Ingress for Mosquitto

The goal of these files are to spin up HAproxy ingress controll to route traffic to a Mosquitto service.

## kubectl

kubectl apply -f https://raw.githubusercontent.com/haproxytech/kubernetes-ingress/v1.6/deploy/haproxy-ingress.yaml

## Helm (use this  or kubectl apply -f)

helm repo add haproxytech https://haproxytech.github.io/helm-charts
