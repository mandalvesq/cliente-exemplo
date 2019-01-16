# cliente-exemplo
Repositório de exemplo de clientes

## Usage



### Simple example:

```hcl
module "instance" {
  
}
```

### Example with additional volumes and EIP

```hcl
module "kafka_instance" {
  
}
```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| additional_ips_count | Count of additional EIPs | string | `0` | no |
| allowed_ports | List of allowed ingress ports | list | `<list>` | no |


## Outputs

| Name | Description |
|------|-------------|
| alarm_ids | CloudWatch Alarm IDs |
| aws_key_pair_name | Name of AWS key pair |


## Related Projects

Check out these related projects.

- [terraform-aws-ec2-instance](https://github.com/XXXXXXXXXX/XXXXXXXXXXX) - Terraform Module for providing a general EC2 XXXXXXXXX


## References

For additional context, refer to some of these links. 

- [terraform-aws-XXXXXXXXXX](https://github.com/XXXXXXXXXXXXXx/XXXXXXXXX) - Terraform module to define a generic xxxxxxxxxxxxxxxxxxxxxx


## Help

**Got a question?**

File a GitHub [issue](https://github.com/XXXXXXXXXXXX/issues), send us an [email][email] or join our [Slack Community][slack].


## Copyright

Copyright © 2017-2018 [Claranet](https://br.claranet.com/)


### Contributors

|  [![Amanda Quinto]<br/>[Eduardo Namba]<br/>[Denis Apolinario] | |---|---|
