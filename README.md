# Kubernetes Manifests Portfolio

|  NAME                   |  PROMPT                                       |  DESCRIPTION                              |  EXAMPLE                                                               |
|------------------------|----------------------------------------------|------------------------------------------|-----------------------------------------------------------------------|
|  app.yaml               |  Kubernetes Pod Manifest                      |  Define a Pod named "app" running a container with the image "nginx:latest" on port 80 |  [app.yaml](./yaml/app.yaml)                             |
|  app-livenessProbe.yaml  |  Kubernetes Pod with Liveness Probe            |  Define a Pod named "app-livenessProbe" running a container with the image "gcr.io/k8s-k3s/demo:v1.0.0" running on port 8080. The container has a liveness probe configured, exposing port 8000, and checks the liveness using an HTTP probe on path "/". |  [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml)  |
