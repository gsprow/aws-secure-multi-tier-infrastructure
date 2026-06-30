# Secure Multi-Tier AWS Infrastructure

## Project Overview

This project demonstrates the design and deployment of a secure multi-tier AWS infrastructure using Amazon VPC, EC2, public and private subnets, route tables, an Internet Gateway, and Security Groups.

The objective was to build a cloud environment that follows AWS networking best practices by separating internet-facing resources from private infrastructure while maintaining secure connectivity.

---

## Business Scenario

A growing organization needs to host a public-facing web application while ensuring internal resources remain isolated from direct internet access.

This project demonstrates how AWS networking components can be combined to provide secure, scalable infrastructure suitable for future application growth.

---

## AWS Services Used

- Amazon VPC
- Amazon EC2
- Internet Gateway
- Route Tables
- Public Subnet
- Private Subnet
- Security Groups
- Amazon Linux 2023

---

## Architecture

*Architecture diagram coming soon.*

---

## Implementation Steps

- Created a custom Amazon VPC.
- Built separate public and private subnets.
- Attached an Internet Gateway.
- Configured public and private route tables.
- Associated the public subnet with internet access.
- Associated the private subnet with a private route table.
- Created a Security Group allowing HTTP traffic and restricted SSH access.
- Launched an EC2 instance within the public subnet.
- Automated Apache installation using EC2 User Data.
- Deployed a custom web page.

---

## Business Value

This architecture demonstrates secure network segmentation by exposing only internet-facing resources while keeping private infrastructure isolated.

The design provides a scalable foundation that can later support load balancers, databases, Auto Scaling Groups, and additional application tiers.

---

## Screenshots

Screenshots are located in the **screenshots** folder.

---

## Lessons Learned

Through this project I gained hands-on experience with:

- Amazon VPC networking
- Route Tables
- Internet Gateways
- Public vs Private Subnets
- EC2 deployment
- Security Groups
- EC2 User Data automation
- Linux web server deployment

---

## Future Improvements

- Add an Application Load Balancer
- Add Auto Scaling
- Deploy a private RDS database
- Configure CloudWatch monitoring
- Implement IAM Roles
