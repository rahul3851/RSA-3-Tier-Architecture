# RSA-3-Tier-Architecture

This repo contains terraform code for deploying a 3-tier architecture on AWS consists of a web tier with a load balancer, an app tier with EC2 instances, and a data tier with a MySQL database deployed on RDS in the us-east-1 region.
Web Tier: ELB - Acts as the entry point for end users.
Application Tier: EC2 Instances - Deployed across multiple azs in private subnets.
Data Tier: MySQL database deployed on RDS, utilizing a subnet group with 3 private subnets across multiple az's.

**For Access Keys & Secrets :**
export AWS_ACCESS_KEY_ID=
export AWS_SECRET_ACCESS_KEY=

