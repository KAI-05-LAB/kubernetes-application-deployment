# Kubernetes Application Deployment

## Objective

This project demonstrates deploying an application on Kubernetes using Deployments and Services.

## Components

### Deployment

The deployment manages Nginx pods and ensures high availability through multiple replicas.

### Service

The service exposes the deployed application and provides access to the pods.

## Kubernetes Commands

### Deploy Application

```bash
kubectl apply -f deployment.yaml
```

### Create Service

```bash
kubectl apply -f service.yaml
```

### Check Deployments

```bash
kubectl get deployments
```

### Check Pods

```bash
kubectl get pods
```

### Check Services

```bash
kubectl get services
```

### Rolling Update

```bash
kubectl set image deployment/nginx-deployment nginx=nginx:1.25
```

## Expected Outcome

* Nginx application deployed successfully
* Service exposes application
* Rolling updates supported

## What I Learned

* Kubernetes Deployments
* Kubernetes Services
* Pod management
* Rolling updates
* Application deployment workflow

## Challenges Faced

Understanding Deployments, Services, and rolling updates was initially challenging. Through studying Kubernetes YAML files and deployment workflows, I gained a better understanding of container orchestration.
