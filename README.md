

### Pre-reqs

1. Install Docker for the desktop and enable kubernetes.
2. Install nginx-ingress controller: https://kubernetes.github.io/ingress-nginx/deploy/#docker-desktop
2. Install kube cli tools.


### install
- From the repo directory, run `kubectl apply -f ./` to deploy these manifests to the cluster currently configured in your kube context.