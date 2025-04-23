![minikube-banner](https://github.com/user-attachments/assets/9ce20aaf-0c56-41a4-9074-affcee457d72)


<h1 align="center">Install Minikube on Google Compute Engine</h1>
<br>

## :dart: About

Install Minikube on Google Compute Engine

## :rocket: Technologies

The following tools were used in this project:

- [Terrafom](https://www.terraform.io/)
- [Google Cloud SDK](https://cloud.google.com/sdk/docs/quickstarts)
- [Google Cloud Platform](https://cloud.google.com/)
- [Minikube](https://minikube.sigs.k8s.io/docs/)
- [Kubernetes](https://kubernetes.io/)
- [Docker](https://www.docker.com/)

## :white_check_mark: Requirements

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com), [Google Cloud SDK](https://cloud.google.com/sdk/docs/quickstarts) and [Terraform](https://www.terraform.io/) installed.

## :checkered_flag: Starting

```bash
# Clone this project
git clone https://github.com/devenes/minikube-compute-engine

# Access
cd minikube-compute-engine

# Inıtialize terraform
terraform init

# Create a plan
terraform plan

# Apply the plan
terraform apply
```
