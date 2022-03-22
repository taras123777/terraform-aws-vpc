# Terraform AWS VPC Module

### Usage:
```
module "vpc" {
    source = "taras123777/vpc/aws"
    cidr_block = "10.0.0.0/16"
    tags = {
        Name = "Dev"
    }
}
```