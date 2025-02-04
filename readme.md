## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | ~> 2.0 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | ~> 2.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | ~> 2.0 ~> 2.0 |
| <a name="provider_aws.us-east-2"></a> [aws.us-east-2](#provider\_aws.us-east-2) | ~> 2.0 ~> 2.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_dynamodb_table.dynamodb-homologacao](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/dynamodb_table) | resource |
| [aws_instance.dev](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_instance.dev4](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_instance.dev5](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_instance.dev6](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_instance.dev7](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_s3_bucket.dev4](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket) | resource |
| [aws_security_group.acesso-ssh](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group) | resource |
| [aws_security_group.acesso-ssh-us-east-2](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_amis"></a> [amis](#input\_amis) | n/a | `map` | <pre>{<br>  "us-east-1": "ami-026c8acd92718196b",<br>  "us-east-2": "ami-0d8f6eb4f641ef691"<br>}</pre> | no |
| <a name="input_cdirs_acesso_remoto"></a> [cdirs\_acesso\_remoto](#input\_cdirs\_acesso\_remoto) | n/a | `list` | <pre>[<br>  "191.32.154.79/32",<br>  "192.32.154.79/32"<br>]</pre> | no |
| <a name="input_key_name"></a> [key\_name](#input\_key\_name) | n/a | `string` | `"terraform-aws"` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_dev5"></a> [dev5](#output\_dev5) | n/a |
| <a name="output_dev6"></a> [dev6](#output\_dev6) | n/a |
| <a name="output_dev7"></a> [dev7](#output\_dev7) | n/a |
