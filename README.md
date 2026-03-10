# CloudAutoX-EKS-Automation
AWS EKS infrastructure automation using Ansible and Docker
# CloudAutoX – AWS EKS Infrastructure Automation

## Project Overview
CloudAutoX is a DevOps project that automates cloud infrastructure and Kubernetes deployments on AWS using Ansible.

## Tech Stack
- AWS
- EKS
- Ansible
- Docker
- Kubernetes
- Linux

## Architecture
EC2 Control Node → Ansible Automation → Docker Container → Kubernetes Pods → AWS EKS → Load Balancer → Internet Users

## Implementation Steps
1. Provision AWS EC2 instances
2. Configure Linux servers using Ansible
3. Automate Docker installation
4. Create AWS EKS cluster
5. Deploy containerized application
6. Expose service via LoadBalancer

## Commands Used
```bash
kubectl get nodes
kubectl apply -f nginx.yml
kubectl expose deployment nginx-app --type=LoadBalancer --port=80
