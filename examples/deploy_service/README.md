# Deploy Service Cluster

This example illustrates how to deploy a service to the created cluster using the kubernetes provider.

It will:
- Create a cluster
- Configure authentication for the Kubernetes provider
- Create an Nginx Pod
- Create an Nginx Service

Expected variables:
- `project_id`
- `region`
- `network`
- `subnetwork`
- `ip_range_pods`
- `ip_range_services`

To provision this example, run the following from within this directory:
- `terraform init` to get the plugins
- `terraform plan` to see the infrastructure plan
- `terraform apply` to apply the infrastructure build
- `terraform destroy` to destroy the built infrastructure
