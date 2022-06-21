# petrichor

Example kubernetes deployment template repo.

## Folders

### `infra`

All k8s manifest files are stored in the `infra` folder to mimic a production respoitory.

### `infra/deployment.yaml`

Creates Deployment object. Uses values file for name, replicas, image, and secrets.

### `infra/service.yaml`

Creates Service object. Uses values file for name, serviceType, servicePort, serviceTargetPort

### `infra/values.yaml`

Manifest values file. Examples of Harness input variables in deployment.
