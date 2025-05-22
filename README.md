# terraform-aws
This is infracture as code provisioning for terraform aws using terraform (iac)


# terraform {
  backend "s3" {
    bucket = "awstimothy12"
    region = "eu-north-1"
    key    = "terraform-backend/terraform.tfstate"
  }
# }