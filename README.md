
# 
echo "# tf_vpc" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/sidk2018/tf_vpc.git
git push -u origin master

git remote add origin https://github.com/sidk2018/tf_vpc.git
git push -u origin master

# AWS VPC module for Terraform
A lightweight VPC module for Terraform.
## Usage
module "vpc" {
source = "github.com/turnbullpress/tf_vpc"
name = "vpc_name"
cidr = "10.0.0.0/16"
public_subnet = "10.0.1.0/24"
}
See `interface.tf` for additional configurable variables.
## License
MIT
Let’s create a .giti
