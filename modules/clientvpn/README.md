## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_ec2_client_vpn_authorization_rule.client_vpn_authorization_rule](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ec2_client_vpn_authorization_rule) | resource |
| [aws_ec2_client_vpn_endpoint.client_vpn_endpoint](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ec2_client_vpn_endpoint) | resource |
| [aws_ec2_client_vpn_network_association.vpn_network_association](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ec2_client_vpn_network_association) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_create_client_vpn_endpoint"></a> [create\_client\_vpn\_endpoint](#input\_create\_client\_vpn\_endpoint) | n/a | `bool` | `true` | no |
| <a name="input_security_groups_vpn"></a> [security\_groups\_vpn](#input\_security\_groups\_vpn) | n/a | `any` | n/a | yes |
| <a name="input_subnet_ids"></a> [subnet\_ids](#input\_subnet\_ids) | n/a | `any` | n/a | yes |
| <a name="input_vpc_user_certificate_arn"></a> [vpc\_user\_certificate\_arn](#input\_vpc\_user\_certificate\_arn) | n/a | `string` | n/a | yes |
| <a name="input_vpnClientName"></a> [vpnClientName](#input\_vpnClientName) | n/a | `string` | `"VPNConnection"` | no |
| <a name="input_vpn_client_cidr_block"></a> [vpn\_client\_cidr\_block](#input\_vpn\_client\_cidr\_block) | CIDR for client to assign | `string` | `"20.0.0.0/16"` | no |
| <a name="input_vpn_server_certificate_arn"></a> [vpn\_server\_certificate\_arn](#input\_vpn\_server\_certificate\_arn) | n/a | `string` | n/a | yes |

## Outputs

No outputs.
