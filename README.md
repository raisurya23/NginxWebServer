# NginxWebServer deployment

Nginx Web server is deployed using Kubernetes deployment and it is exposed on port 30176 ad it is accebile at http://147.182.131.42:30176/

Have used HPA (Horizontal pod Autoscaler ) with command :  kubectl autoscale deployment php-apache --cpu-percent=50 --min=1 --max=10 (also yaml file is uploaded hpa.yaml)
