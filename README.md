# Terraform AWS VPC Module

## Example


```sh
module "vpc-aws" {
  source  = "mamyro/vpc-aws/module"
  version = "0.0.2"

  vpc_cidr = "10.0.0.0/16"
  subnet_cidr = ["10.0.1.0/16" , "10.0.2.0/16" ]
}

```



