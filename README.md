# Kubernetes Version Switcher


### To run

###### todo: add makefile to build, the use github actions for build + release

```
go build main.go

mv main /usr/local/bin/kubeswitch

kubeswitch v1.x.x
```

### Enhancements:

1. Get OS version and decide on which URL to download from
2. Install Helm version 
3. For helm install, add logic to check server version to match
4. Implement flags for "yes" and "no" input
