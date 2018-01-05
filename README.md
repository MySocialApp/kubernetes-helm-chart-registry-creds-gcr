# kubernetes-helm-chart-registry-creds-gcr
Kubernetes Helm Chart for registry-creds GCR

# Usage
Following [registry-creds](https://github.com/upmc-enterprises/registry-creds) instructions, use ***application_default_credentials.json*** and copy its content in the values file (registryCredsAppDefaultCredsJson):

```bash
base64 -w 0 ~/.config/gcloud/application_default_credentials.json
```