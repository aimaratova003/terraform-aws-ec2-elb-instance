# terraform-aws-ec2-elb-instance

```

module "terraform_elb" {
  source ="aimaratova003/ec2-elb-instance/aws"
  instance_type = var.instance_type
  ami = var.ami
  key_name = "tuncay"
}
