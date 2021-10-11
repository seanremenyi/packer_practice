# packer_practice

## installing packer on amazon linux
Install yum-config-manager to manage your repositories.
`$ sudo yum install -y yum-utils`
Use yum-config-manager to add the official HashiCorp Linux repository.
`$ sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo`
Install.
`$ sudo yum -y install packer`

source: https://learn.hashicorp.com/tutorials/packer/get-started-install-cli?in=packer/aws-get-started