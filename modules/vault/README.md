# vault - AWS EC2-VPC Security Group Terraform module

## Usage

```hcl
module "vault_security_group" {
  source  = "terraform-aws-modules/security-group/aws//modules/vault"
  version = "~> 4.0"

  # omitted...
}
```

All automatic values **vault module** is using are available [here](https://github.com/terraform-aws-modules/terraform-aws-security-group/blob/master/modules/vault/auto_values.tf).

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
