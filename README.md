# Kubernetes DevSecOps Pipeline

This project demonstrates an end-to-end DevSecOps workflow for containerized applications deployed to Kubernetes.

## Overview

The objective of this project is to automate application delivery while incorporating security checks throughout the software delivery lifecycle.

## Technology Stack

* GitHub Actions
* Docker
* SonarQube
* Trivy
* Kubernetes
* ArgoCD
* AWS

## Pipeline Flow

Developer Commit

↓

GitHub Actions

↓

Build Docker Image

↓

SonarQube Analysis

↓

Trivy Security Scan

↓

Push Image

↓

ArgoCD Deployment

↓

Kubernetes Cluster

## Security Controls

* Static Code Analysis
* Container Vulnerability Scanning
* Automated Deployment Validation

## Future Improvements

* OPA Policy Enforcement
* Runtime Security Monitoring
* Multi-Environment Deployments
