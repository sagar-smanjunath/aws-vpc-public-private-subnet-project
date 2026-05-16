# aws-vpc-public-private-subnet-project
# AWS VPC Infrastructure Setup with Public and Private Subnets

## Project Overview

This project demonstrates the implementation of a secure and scalable AWS VPC architecture using public and private subnets.

The infrastructure includes:

* Custom VPC
* Public and Private Subnets
* Internet Gateway
* NAT Gateway
* Route Tables
* EC2 Instances
* Security Groups

The project focuses on secure network communication, internet accessibility control, and subnet-level isolation in AWS.

---

# Architecture

The architecture consists of:

* One custom VPC
* Public subnet for internet-facing resources
* Private subnet for internal resources
* Internet Gateway attached to the VPC
* NAT Gateway for outbound internet access from private subnet
* Route tables configured for traffic management
* Linux EC2 instances deployed in both subnets

---

# AWS Services Used

* Amazon VPC
* Amazon EC2
* Internet Gateway
* NAT Gateway
* Route Tables
* Security Groups
* Elastic IP

---

# Steps Performed

## 1. Created Custom VPC

* Configured a custom VPC with CIDR block
* Enabled DNS hostnames and DNS resolution

## 2. Created Public and Private Subnets

* Configured separate subnets across availability zones
* Public subnet configured for internet access
* Private subnet isolated from direct internet exposure

## 3. Configured Internet Gateway

* Created and attached Internet Gateway to the VPC
* Allowed public subnet resources to access the internet

## 4. Configured NAT Gateway

* Created NAT Gateway inside the public subnet
* Associated Elastic IP for outbound internet communication
* Enabled private subnet instances to access external resources securely

## 5. Configured Route Tables

### Public Route Table

* Added route to Internet Gateway

### Private Route Table

* Added route to NAT Gateway

## 6. Launched EC2 Instances

* Deployed Linux EC2 instances in public and private subnets
* Verified connectivity and routing behavior

## 7. Configured Security Groups

* Allowed SSH access
* Controlled inbound and outbound traffic securely

---

# Key Concepts Demonstrated

* VPC Architecture Design
* Public vs Private Subnets
* Secure Network Isolation
* Internet and NAT Gateway Configuration
* Routing and Traffic Management
* Linux Server Deployment in AWS
* Cloud Networking Fundamentals

---

# Project Outcome

Successfully built a secure AWS cloud network architecture with controlled internet access and subnet isolation using AWS VPC services.

---

# Screenshots

Add all project screenshots inside the `screenshots` folder.

Example screenshots:

* VPC Creation
* Public and Private Subnets
* Route Tables
* NAT Gateway
* Internet Gateway
* EC2 Instances
* Security Groups
* Connectivity Verification

---

# Author

Sagar S M

LinkedIn:
https://linkedin.com/in/sagar-sm

GitHub:
https://github.com/sagar-smanjunath
