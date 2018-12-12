Pact Broker on Kubernetes
=========================

To get started with GKE:

```bash
gcloud container clusters create my-cluster
kubectl apply -f .
watch -n 1 kubectl get configmap,svc,pod
```

See the ConfigMap for configuration settings. Currently this is just set to a built in SQLite database, but obviously
this is not suitable for production usage.
