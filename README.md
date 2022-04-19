# Flux GitOps example with Google Kubernetes Engine

This is the source code for [GitOps setup in Google Kubernetes Engine using Flux CD
](https://felipelujan.medium.com/gitops-setup-in-google-kubernetes-engine-using-flux-cd-1e26b0ef1fc7)

Useful commands

```
flux bootstrap git \
 --url=ssh:... \
 --private-key-file=/Users/USERNAME/.ssh/id_rsa \
 --silent \
 --path=./clusters/wordpress_cluster \
 --branch="master"
```

```
flux get kustomization -A
```

```
flux get source git -A
```

```
flux get hr -A
```
