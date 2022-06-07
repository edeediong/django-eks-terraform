# django-eks-terraform

This repository contains files for provisioning a Kubernetes cluster and deploying an application to said cluster all using Terraform.

## Configure AWS CLI access credentials

you step up your Configure AWS CLI Access Credentials

```text
aws_access_key_id = xxx
aws_secret_access_key = xxx
default_region_name = xxx
defualt_output_formet = xxx
```

## Select Terraform Workspace

```text
terraform workspace list
terraform workspace select "workspace name"
```

## Deploying Your Code

```text
terraform init
terraform plan
terraform apply
```
