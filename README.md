app.yaml

Prompt: "Create an nginx deployment with 3 replicas"
Description: "YAML to define the basic schema of a Kubernetes application"
Example: app.yaml
app-livenessProbe.yaml

Prompt: "Add a liveness probe to the nginx deployment using http-get on port 80"
Description: "YAML to define a liveness probe for your application"
Example: app-livenessProbe.yaml
app-readinessProbe.yaml

Prompt: "Add a readiness probe to the nginx deployment using http-get on port 80"
Description: "YAML to define a readiness probe for your application"
Example: app-readinessProbe.yaml
app-volumeMounts.yaml

Prompt: "Create a volume mount for nginx deployment with a config map"
Description: "YAML to define and configure storage volumes for your application"
Example: app-volumeMounts.yaml
app-cronjob.yaml

Prompt: "Create a cron job in Kubernetes to run 'echo hello' every minute"
Description: "YAML to define a cron job within your application"
Example: app-cronjob.yaml
app-job.yaml

Prompt: "Create a Kubernetes job to run 'echo hello' once"
Description: "YAML to define a job within your application"
Example: app-job.yaml
app-multicontainer.yaml

Prompt: "Set up a multi-container pod with nginx and redis containers"
Description: "YAML to define a pod that runs more than one container"
Example: app-multicontainer.yaml
app-resources.yaml

Prompt: "Configure resource requests and limits for nginx container"
Description: "YAML to configure resource requests and limits for your application"
Example: app-resources.yaml
app-secret-env.yaml

Prompt: "Set up a secret environment variable for nginx deployment"
Description: "YAML to define environment variables using secrets"
Example: app-secret-env.yaml
