R1soft Module
This module is used for creating R1soft 
 Prerequisites

1. Terraform 0.11.14

         ### Steps
         ## Edit the file below

```
git clone https://github.com/OtabekSamatov/r1soft-server
cd infrastructure/r1soft/
vi configurations/r1soft.tfvars
```

```
# Below code is used to set backend only	
```	

```
source setenv.sh configurations/ENVR/r1soft.rfvars 
terraform apply -var-file configurations/ENVR/r1soft.rfvars 
