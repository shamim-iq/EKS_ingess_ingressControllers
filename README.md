# Motive

This project will guide you through setting up an AWS EKS cluster powered by Fargate and the AWS Load Balancer Controller, perfect for your applications. You'll also discover the vital roles of ingress resources and ingress controllers, unlocking new levels of scalability and flexibility for your cloud-native deployments!

## Table of Contents
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Commands](#commands)
- [Accessing Your Application](#accessing-your-application)
- [License](#license)

## Requirements

Before you begin, ensure you have the following tools installed:

- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [eksctl](https://eksctl.io/introduction/#installation)
- [AWS CLI](https://aws.amazon.com/cli/)
- [Helm](https://helm.sh/docs/intro/install/)

## Getting Started

### Configuration

Configure your AWS CLI with your credentials:

```bash
aws configure
```

Create an EKS Cluster
- Create your EKS cluster using the following command:
  ```bash
  eksctl create cluster --name my-demo-cluster --region us-east-1 --fargate
  ```
- Update your kubeconfig to use the newly created cluster:
  ```bash
  eksctl create cluster --name my-demo-cluster --region us-east-1 --fargate
  ```


