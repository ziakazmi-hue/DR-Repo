# Temenos DR Project

## Overview
This repository is used for learning and managing
the Temenos/Kony Fabric Disaster Recovery environment.

## Infrastructure
- AWS EKS
- Amazon ECR
- Amazon EC2 MySQL
- AWS Route 53
- Kubernetes
- Helm

## DevOps Tools
- Git
- GitHub
- Terraform
- GitHub Actions
- Argo CD

## Purpose
Version control for infrastructure configurations,
Kubernetes manifests, Helm charts and CI/CD automation.

## DR Testing Workflow

1. Verify the primary on-premises Kubernetes environment.
2. Validate AWS EKS cluster health.
3. Verify container images are available in Amazon ECR.
4. Validate DR database availability, data freshness, and standby read-only status.
5. Perform application recovery using Kubernetes and Helm.
6. Validate application connectivity after recovery.
