## AWS CLI Installation Instruction & Configuration(Requirements)

> Its recommended to create new `IAM` user with `Role` of `ADMIN` \
> Generate account credentials  

First you need to install `AWS-CLI-V2` by using :
> `Chocolatey` Must be installed on system to run option 1, and then run this command on PowerShell `(administrator)`

Option 1. `Chocolatey(for windows users)` -> https://community.chocolatey.org/packages/awscli \
Option 2. `Home Brew(for mac users)` -> https://formulae.brew.sh/formula/awscli \
Option 3. `By using installation file(All Platforms)` -> https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html


Run this command and set/add  `Access Key ID` , `Secrect Key ID` and `Region`
```bash
aws configure
```

 ------
 
# Terraform 

To initilize an Infrastructure
``` bash
terraform init
```
To Format code Variables/templates
``` bash
terraform fmt
```
For validations
``` bash
terraform validate
```
:seedling: To Build an infrastructure
``` bash
terraform apply
```
To show current state 
``` bash
terraform show
```
To refresh state 
``` bash
terraform refresh
```
To check providers
``` bash
terraform providers
```
:warning: To destroy infrastructue

``` bash
terraform destroy
```
