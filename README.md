# argo-apps-ci

Here we store the Argo application manifests for the CI EKS cluster, managed by the SRE team.

The Argo CD installation is bootstrapped in the EKS cluster Terraform in the [terraform-eks-ci repository](https://github.com/uktrade/terraform-eks-ci)

## Argo

Argo CD is a Kubernetes-native continuous deployment (CD) tool. Unlike external CD tools that only enable push-based deployments, Argo CD can pull updated code from Git repositories and deploy it directly to Kubernetes resources. It enables developers to manage both infrastructure configuration and application updates in one system.

