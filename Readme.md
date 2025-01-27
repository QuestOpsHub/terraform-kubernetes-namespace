# Azure Kubernetes Namespace Terraform Module

Terraform module to create Kubernetes Namespace.

## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_kubernetes"></a> [kubernetes](#provider\_kubernetes) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [kubernetes_namespace.namespace](https://registry.terraform.io/providers/hashicorp/kubernetes/latest/docs/resources/namespace) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_annotations"></a> [annotations](#input\_annotations) | ---------------------- Kubernetes Namespace ---------------------- | `any` | `null` | no |
| <a name="input_labels"></a> [labels](#input\_labels) | n/a | `any` | `null` | no |
| <a name="input_name"></a> [name](#input\_name) | n/a | `any` | `null` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_name"></a> [name](#output\_name) | ---------------------- Kubernetes Namespace ---------------------- |
