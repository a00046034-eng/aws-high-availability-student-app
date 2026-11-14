
# AWS High-Availability Student Application

## Project Overview
This project involved deploying a student management web application on Amazon Web Services (AWS).

The objective was to develop a secure, scalable and highly available cloud infrastructure capable of supporting a web application across multiple Availability Zones.

## Technologies Used
- Amazon EC2
- Amazon RDS (MySQL)
- AWS Secrets Manager
- Application Load Balancer (ALB)
- Auto Scaling Groups (ASG)
- Amazon VPC
- AWS Security Groups
- Node.js and Express

## Project Implementation

### Phase 1: Initial Deployment
- Deployed a Node.js web application on an EC2 instance.
- Configured a MySQL database.
- Set up networking and security groups.
- Tested application connectivity.

### Phase 2: Database and Security
- Migrated the database to Amazon RDS MySQL.
- Placed the database in private subnets.
- Configured AWS Secrets Manager for database credentials.
- Restricted database access using security groups.

### Phase 3: High Availability
- Configured an Application Load Balancer.
- Deployed application instances across two Availability Zones.
- Implemented an Auto Scaling Group.
- Configured health checks and tested application availability.
- Verified application functionality through the load balancer.

## Architecture
Internet → Application Load Balancer → EC2 Instances → Amazon RDS MySQL

AWS Secrets Manager provides secure access to database credentials.

## Testing and Results
- Successfully accessed the application through the ALB.
- Verified two healthy application instances.
- Tested the student management functionality.
- Configured automatic scaling to support changes in demand.

## Skills Demonstrated
- AWS cloud architecture
- Cloud networking and security
- Database management
- High availability
- Load balancing
- Auto Scaling
- Cloud troubleshooting

## Project Status
The infrastructure was deployed and tested in an AWS Academy lab environment.

This repository documents the architecture and implementation. Application source code and deployment evidence will be added where available.

