Title: terraform
Date: 2018-5-15 11:25
Tags: Terraform
Category:
Slug: terraform
Summary:
Status: Published
#########

### Installing Terraform

* Go to https://www.terraform.io/downloads.html
* Copy link address for chosen platform
  * e.g. https://releases.hashicorp.com/terraform/0.11.7/terraform_0.11.7_linux_amd64.zip
* wget it
  ```
  cd /tmp
  wget https://releases.hashicorp.com/terraform/0.11.7/terraform_0.11.7_linux_amd64.zip
  ```
* unzip
  ```
  unzip terraform*
  ```
* copy binary to installation folder
  ```
  sudo cp terraform /usr/local/bin/
  ```
* check its installed
  ```
  terraform -v
  ```
