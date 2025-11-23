
# AWS EKS Deployment with Terraform, Docker & GitLab CI/CD

Automated the deployment of a Dockerized application on AWS EKS using Terraform and GitLab CI/CD. The infrastructure includes a custom VPC, public/private subnets, NAT gateways, and secure worker nodes. Kubernetes manifests (Deployment, LoadBalancer Service, ConfigMaps, Secrets) manage application deployment and expose it via an AWS NLB. GitLab pipelines build & push Docker images to Docker Hub and continuously deploy updates to the EKS cluster on every commit.

## Tech Stack

AWS, EKS, Kuberenetes, Terraform, Docker, CI/CD 



## Screenshots

![App Screenshot](https://github.com/SMThapa/eks/blob/master/web.png)

