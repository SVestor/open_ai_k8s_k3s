## k8s-k3s ai generated manifests portfolio

---

| NAME                    | PROMPT                                                                                    | DESCRIPTION                              | EXAMPLE                                                 |
|-------------------------|-------------------------------------------------------------------------------------------|------------------------------------------|---------------------------------------------------------|
| app-configmap.yaml      | "configure configmap for a pod"                                                           | a basic ConfigMap resource example       | [app-configmap.yaml](yaml/app-configmap.yaml)           |
| app-cronjob.yaml        | "config a CronJob running at 4AM every 2 days rebooting nginx"                            | a basic CronJob resource example         | [app-cronjob.yaml](yaml/app-cronjob.yaml)               |
| app-livenessProbe.yaml  | "configure a liveness probe for the pod"                                                  | a basic liveness probe example           | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)   |
| app-deploy.yaml         | "make deployment of basic-app based on docker image"                                      | a basic deploy example                   | [app-deploy.yaml](yaml/app-deploy.yaml)                 |
| app-multicontainer.yaml | "configure pod with multiple containers"                                                  | a basic multicontainer pod example       | [app-multicontainer.yaml](yaml/app-multicontainer.yaml) |
| app-readinessProbe.yaml | "configure a readineness probe for the  pod"                                              | a basic readiness probe example          | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |
| app-job.yaml            | "config a job running every 15 minutes doing backaup of folder data to backups directory" | a basic job resource example             | [app-job.yaml](yaml/app-job.yaml)                       |
| app-resources.yaml      | "configure resource limits and requests for the pod"                                      | a basic resource limits requests example | [app-resources.yaml](yaml/app-resources.yaml)           |
| app-secret-env.yaml     | "use a Secret to set environment variables"                                               | a basic secret example                   | [app-secret-env.yaml](yaml/app-secret-env.yaml)         |
| app-volumeMounts.yaml   | "configure volume mounts for the pod"                                                     | a basic volume example                   | [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml)     |
| app.yaml                | "define a basic pod resource, container name is my-container"                             | a basic pod exapmple                     | [app.yaml](yaml/app.yaml)                               |

---