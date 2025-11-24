# argocd-cilium-demo

```bash
until kustomize build --enable-helm https://github.com/christianh814/argocd-cilium-demo/bootstrap/overlays/default | kubectl apply -f - ; do sleep 1; done
```
