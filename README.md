# eks
Test Configuration eks cluster on aws


-  QSS3BucketName =  "aws-quickstart"
-  QSS3KeyPrefix  =  "quickstart-amazon-eks/" 

## Aws vpc template

https://aws-quickstart.s3.amazonaws.com/quickstart-amazon-eks/submodules/quickstart-aws-vpc/templates/aws-vpc.template'

## Aws eks template

https://aws-quickstart.s3.amazonaws.com/quickstart-amazon-eks/templates/amazon-eks.template.yaml


## Details

This tutorial creates 8 stack of cloudformation 

1. LinuxBastion+VPC July,18,2019 QS(0037)  [Nested]
2. Deploys EKS nodes into an existing VPC (qs-1p7nknoid) [Nested]
3. Deploys the EKS control plane (qs-1p7nknofn)
4. Deploys Lambda functions required for the AWS EKS Quick Start (qs-1p7nknoh4)
5. Deploys IAM roles and policies required for the AWS EKS Quick Start (qs-1p7nknohl)
6. Deploys an EKS cluster into an existing VPC (qs-1p7nknoi6)
7. This template creates a Multi-AZ, multi-subnet VPC infrastructure with managed NAT gateways in the public subnet for each Availability Zone. You can also create additional private subnets with dedicated custom network access control lists (ACLs). If you deploy the Quick Start in a region that doesn't support NAT gateways, NAT instances are deployed instead. **WARNING** This template creates AWS resources. You will be billed for the AWS resources used if you create a stack from this template. QS(0027)
This template creates a Multi-AZ, multi-subnet VPC infrastructure with managed NAT gateways in the public subnet for each Availability Zone. You can also create additional private subnets with dedicated custom network access control lists (ACLs). If you deploy the Quick Start in a region that doesn't support NAT gateways, NAT instances are deployed instead. **WARNING** This template creates AWS resources. You will be billed for the AWS resources used if you create a stack from this template. QS(0027)
8. Deploys an EKS cluster in a new VPC (qs-1p7nknoht)
    * EKSStack  
    * VPCStack


