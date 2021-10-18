# NginxWebServer deployment

Nginx Web server is deployed using Kubernetes deployment and it is exposed on port 30176 ad it is accebile at http://147.182.131.42:30176/

Have used Docker image https://hub.docker.com/_/nginx

Have used HPA (Horizontal pod Autoscaler ) with command :  kubectl autoscale deployment php-apache --cpu-percent=50 --min=1 --max=10 (also yaml file is uploaded hpa.yaml)

adminuser.yaml and clusterbind.yaml files was used for kubernerets dashboard.
