# Django AWS Infrastructure Assignment

## Overview
This project deploys a default Django application on AWS EC2 using Docker for containerization.

## Architecture
- AWS EC2 (t3.micro - Free Tier)
- Dockerized Django application
- Security Group with restricted SSH access
- Public access via HTTP
- ALLOWED_HOSTS configured

## Deployment Steps
1. Clone repository
2. Build Docker image
3. Run container
4. Access via EC2 public IP

## Security Considerations
- SSH restricted to single IP
- Minimal inbound ports
- Docker-based isolation
- Budget alert configured

## Pending Step
- Enable HTTPS (port 443) using self-signed certificate
