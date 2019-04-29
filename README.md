# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/kube-proxy-amd64:${VERSION}
docker tag hawsers/kube-proxy-amd64:${VERSION} k8s.gcr.io/kube-proxy-amd64:${VERSION}
docker rmi hawsers/kube-proxy-amd64:${VERSION}
```
