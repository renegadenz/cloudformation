# AWS CloudFormation Templates
This repository, created by James Mead, a DevOps Engineer, contains a collection of AWS CloudFormation templates that can be used to provision and manage various AWS resources. The templates are written in YAML format and can be easily deployed using the AWS CloudFormation service. James's GitHub username is renegadenz.

## Overview
The following AWS resources are provisioned using the templates in this repository:

Application Load Balancer: A highly available and scalable load balancer for routing traffic to your applications running on Amazon EC2 instances or containers.
Amazon Elastic Kubernetes Service (EKS): A managed Kubernetes service that makes it easy to deploy, manage, and scale containerized applications using Kubernetes on AWS.
Amazon Elastic Container Service (ECS): A fully managed container orchestration service that makes it easy to run, stop, and manage Docker containers on a cluster of Amazon EC2 instances.
Amazon Managed Streaming for Apache Kafka (MSK): A fully managed service that makes it easy to build and run applications that use Apache Kafka to process streaming data.
Amazon Kinesis: A fully managed service for real-time data processing and analytics.
Amazon CloudFront and Amazon S3: A content delivery network (CDN) that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all backed by AWS Shield for DDoS protection.

## How to use
To deploy any of the templates in this repository, you will need to have an AWS account and access to the AWS CloudFormation service. You can use the AWS Management Console or the AWS CLI to deploy the templates.

1. Clone the repository to your local machine:

```
git clone https://github.com/renegadenz/cloudformation.git
```
2. Choose the template you want to deploy and navigate to the corresponding folder.

3. Open the template in a text editor and modify any parameters or configurations as needed.

4. Deploy the template using one of the following methods:

AWS Management Console: Upload the template to the AWS CloudFormation service and follow the prompts to launch the stack.
AWS CLI: Use the aws cloudformation create-stack command to deploy the template from the command line.

## Contributions
Contributions to this repository are welcome and encouraged! If you find a bug or have an idea for a new template, please open an issue or submit a pull request.

## License
This repository is licensed under the MIT License.