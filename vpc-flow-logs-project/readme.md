# Project #1: VPC Flow Logs

This project involves using VPC flow logs to resolve a connectivity issue between 2 EC2 instances.

This project was completed in the us-east-1 region, however it can be completed in any other AWS region.

For the original project and instructions created by Adrian Cantrill, please visit: https://github.com/acantril/learn-cantrill-io-labs/tree/master/00-aws-simple-demos/aws-vpc-flow-logs

# Project Steps

## Step 1: IAM roles

First, we must configure the EC2 SSM Session Manager role.

Navigate to Identity and Access Management (IAM) in the AWS Management Console.

![iam role](images/iamrole.png)

![create role](images/createrole.png)