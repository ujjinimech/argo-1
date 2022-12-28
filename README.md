# install argo cd
```
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

## install argocd cli
```
wget https://github.com/argoproj/argo-cd/releases/latest/download/argocd-linux-amd64
 sudo mv argocd-linux-amd64 /usr/local/bin/argocd
 chmod +x /usr/local/bin/argocd
 argocd --help 
```
