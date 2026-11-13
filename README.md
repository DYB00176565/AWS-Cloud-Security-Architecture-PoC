# AWS Cloud Proof of Concept – Security Architecture

## Project Overview

This project involved designing and implementing an AWS cloud proof of concept based on client requirements.

The solution focused on secure network architecture, infrastructure configuration and controlled access between cloud services.

## Objectives

- Design a secure AWS network environment.
- Configure public and private subnets.
- Control access between cloud resources.
- Implement and test cloud infrastructure components.

## Tools and Technologies

- Amazon Web Services (AWS)
- Amazon VPC
- EC2
- Bastion Host
- Security Groups
- Application Load Balancer
- Amazon RDS (MySQL)
- Amazon S3
- Auto Scaling

## My Contribution

My main contribution focused on AWS networking and infrastructure configuration.

I worked on:

- Configuring VPC and subnets across two Availability Zones.
- Setting up EC2 instances and a Bastion Host.
- Configuring Security Groups and access restrictions.
- Setting up an Application Load Balancer.
- Configuring database connectivity with Amazon RDS.
- Testing network access and communication between resources.

## Testing and Results

The implemented environment was tested to verify:

- SSH access through the Bastion Host.
- Restricted access to private EC2 instances.
- Security Group access rules.
- Database connectivity from the application server.
- Application Load Balancer target health.

## Limitations

Some components were not fully implemented due to AWS Academy lab limitations and cost restrictions.

These included NAT Gateway and some additional production security improvements. The RDS configuration also used Single-AZ deployment.

## Report

The full technical report, including architecture diagrams, configuration screenshots, testing and results, is available here:

[View AWS Cloud PoC Report](https://github.com/DYB00176565/AWS-Cloud-Security-Architecture-PoC/blob/main/AWS_Cloud_PoC_Report.pdf)

## Disclaimer

This project was developed as part of a university assignment for educational purposes.
