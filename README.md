## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| environment | Environment name. | string | n/a | yes |
| erp\_firewall\_source\_ranges | List of source ranges applied to ERP \(app+db\) firewall rules, | list | `<list>` | no |
| gce\_project | GCP project ID. | string | n/a | yes |
| gce\_region | GCE region where resources are allocated. | string | n/a | yes |
| members\_project\_iam\_serviceaccountuser | list of project iam service account user members | list | `<list>` | no |
| members\_project\_logging\_configwriter | list of project logging config writer members | list | `<list>` | no |
| members\_project\_logging\_privatelogviewer | list of project logging privatelogviewer members | list | `<list>` | no |
| members\_project\_logging\_viewer | list of project logging viewer members | list | `<list>` | no |
| members\_project\_monitoring\_editor | list of project monitoring editor members | list | `<list>` | no |
| members\_project\_monitoring\_viewer | list of project monitoring viewer members | list | `<list>` | no |
| members\_project\_owner | List of project owners members | list | `<list>` | no |
| monitoring\_network\_address | Monitoring ipv4 network address. | string | `"192.168.2.0"` | no |
| monitoring\_network\_mask | Monitoring CIDR network mask. | string | `"24"` | no |
| project\_metadata\_user\_key | map of ssh public key by user | list | `<list>` | no |
| services\_network\_address | Services ipv4 network address. | string | `"192.168.1.0"` | no |
| services\_network\_mask | Services CIDR network mask. | string | `"24"` | no |

