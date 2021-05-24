# Jitsi Helm Chart

> This is WIP. Only tested docker-desktop.

TODO:

- [ ] Add Jigasi to the deployment
- [ ] Manually create HA deployment
- [ ] Configure healthchecks
- [ ] Configure to use templates
- [ ] Update images to a more recent version

To install run the following command:

```bash
kubectl apply -n jitsi -f prosody-deployment.yaml
kubectl apply -n jitsi -f prosody-service.yaml
kubectl apply -n jitsi -f jvb-deployment.yaml
kubectl apply -n jitsi -f jvb-service.yaml
kubectl apply -n jitsi -f jicofo-deployment.yaml
kubectl apply -n jitsi -f web-deployment.yaml
kubectl apply -n jitsi -f web-service.yaml
```
