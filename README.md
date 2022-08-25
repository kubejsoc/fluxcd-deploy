# fluxcd-deploy

```
flux bootstrap github --components-extra=image-reflector-controller,image-automation-controller --owner=kubejsoc --repository=fluxcd-deploy --branch=main --path=clusters/home --personal --token-auth
```