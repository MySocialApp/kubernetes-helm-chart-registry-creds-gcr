# kubernetes-helm-chart-registry-creds-gcr

You can find here a helm chart we're using at [MySocialApp](https://mysocialapp.io) (iOS and Android social app builder - SaaS)

Kubernetes Helm Chart for registry-creds GCR

# Usage
Following [registry-creds](https://github.com/upmc-enterprises/registry-creds) instructions, use ***application_default_credentials.json*** and copy its content in the values file (registryCredsAppDefaultCredsJson):

```bash
base64 -w 0 ~/.config/gcloud/application_default_credentials.json
```
