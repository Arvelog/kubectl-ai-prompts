| Prompt | Description | Example |
|---|---|---|
| Create an nginx deployment with 3 replicas | YAML to define the basic schema of a Kubernetes application | app.yaml |
| Add a liveness probe to the nginx deployment using http-get on port 80 | YAML to define a liveness probe for your application | app-livenessProbe.yaml |
| Add a readiness probe to the nginx deployment using http-get on port 80 | YAML to define a readiness probe for your application | app-readinessProbe.yaml |
| Create a volume mount for nginx deployment with a config map | YAML to define and configure storage volumes for your application | app-volumeMounts.yaml |
| Create a cron job in Kubernetes to run 'echo hello' every minute | YAML to define a cron job within your application | app-cronjob.yaml |
| Create a Kubernetes job to run 'echo hello' once | YAML to define a job within your application | app-job.yaml |
| Set up a multi-container pod with nginx and redis containers | YAML to define a pod that runs more than one container | app-multicontainer.yaml |
| Configure resource requests and limits for nginx container | YAML to configure resource requests and limits for your application | app-resources.yaml |
| Set up a secret environment variable for nginx deployment | YAML to define environment variables using secrets | app-secret-env.yaml |
