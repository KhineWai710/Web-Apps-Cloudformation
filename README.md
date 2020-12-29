# cloudformation-deploy-web-servers
Deploy a High-Availability Web App using CloudFormation

Application can be check here.
http://serve-webap-1akckqfmanmfc-1654206399.ap-northeast-1.elb.amazonaws.com/

![alt text](https://github.com/KhineWai710/cloudformation-deploy-web-servers/blob/main/High_Availability_Web_App.png)

## How to run
1. Create the stack
$ create.sh <stack_name> <deploy_yaml_file_name> <param_name>

2. Update the stack
$ create.sh <stack_name> <deploy_yaml_file_name> <param_name>

## File Structures
```
.
├── High_Availability_Web_App.png
|
├── create.sh
|
├── network-param.json           (Parameters for networks such as VPC, Subnets,)
|
├── network.yml                  (Deploy file for VPC, Subnets, Routing, etc..)
|
├── server-param.json            (Parameters for application deply such as EC2, ALB, ASG,etc..)
|
├── server.yml                   (Deply file for application deply such as EC2, ALB, ASG,etc..)
|
└── update.sh
```
