# azcontainer-eval-rvtools-reports
Azure container to evaluate rvtools reports

c.f. Based on the MS Learn page for creating containers in Azure with Terraform - https://learn.microsoft.com/en-us/azure/container-instances/container-instances-quickstart-terraform

Terraform AzureRM provider docs:
https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs

Docker image config:
https://developers.redhat.com/articles/2023/08/17/how-deploy-flask-application-python-gunicorn#the_application

Build docker image:
    docker build -t azc-eval-rvtools-reports:0.0.1 .

    docker login

    docker tag jwhoakley/azc-eval-rvtools-reports:latest jwhoakley/azc-eval-rvtools-reports:0.0.1

    docker push jwhoakley/azc-eval-rvtools-reports:0.0.1 

Nginx 
https://docs.gunicorn.org/en/22.0.0/deploy.html
https://phoenixnap.com/kb/docker-nginx-reverse-proxy
