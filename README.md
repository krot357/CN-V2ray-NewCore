## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_chart_version"></a> [chart\_version](#input\_chart\_version) | Helm chart version. | `string` | `"0.1.1"` | no |
| <a name="input_create_namespace"></a> [create\_namespace](#input\_create\_namespace) | Create the namespace if it does not yet exists. | `bool` | `false` | no |
| <a name="input_jira_token"></a> [jira\_token](#input\_jira\_token) | Jira API token of the user. | `string` | n/a | yes |
| <a name="input_jira_user"></a> [jira\_user](#input\_jira\_user) | Email address of Jira user. | `string` | n/a | yes |
| <a name="input_name"></a> [name](#input\_name) | The name of the jiralert | `string` | `"jiralert"` | no |
| <a name="input_namespace"></a> [namespace](#input\_namespace) | The namespace in which the jiralert chart will be deployed. | `string` | `"infra-monitoring"` | no |
| Need only for previosly versions 
| <a name="input_registry_id"></a> [registry\_id](#input\_registry\_id) | Yandex container registry id. | `string` | n/a | yes |
| <a name="input_registry_pass"></a> [registry\_pass](#input\_registry\_pass) | Password for login to Yandex container registry. | `string` | n/a | yes |
| <a name="input_registry_user"></a> [registry\_user](#input\_registry\_user) | Username for login to Yandex container registry. | `string` | `"json_key"` | no |
|
| <a name="input_set"></a> [set](#input\_set) | Additional values to set. | `map(any)` | `{}` | no |
| <a name="input_set_sensitive"></a> [set\_sensitive](#input\_set\_sensitive) | Additional sensitive values to set. | `map(any)` | `{}` | no |
| <a name="input_value"></a> [value](#input\_value) | Values for the jiralert chart. | `string` | `""` | no |
