# Kubernetes-Handson
Hands-on Kubernetes practice repository including Pods, Deployments, Services, ConfigMaps, and real-world use cases with YAML manifests, Minikube setup, and troubleshooting examples.



# Kubernetes Basics - Day 01

## 📌 Overview
This document covers:
- Docker vs Kubernetes
- Kubernetes Architecture
- Minikube Setup
- Pod Creation (Imperative & Declarative)

---

## 🐳 Docker vs Kubernetes

| Feature        | Docker              | Kubernetes              |
|----------------|-------------------|------------------------|
| Purpose        | Containerization   | Orchestration          |
| Scaling        | Manual            | Auto Scaling           |
| Deployment     | Single host       | Cluster-based          |

---

## ☸ Kubernetes Architecture

### Control Plane Components:
- API Server
- etcd
- Scheduler
- Controller Manager

### Worker Node Components:
- kubelet
- kube-proxy

---

## ⚙️ Minikube Setup

### Prerequisites:
- 2 CPUs
- 2GB RAM
- 20GB Disk

### Installation:
```bash
yum install docker -y
systemctl start docker

curl -LO https://github.com/kubernetes/minikube/releases/latest/download/minikube-linux-amd64
install minikube-linux-amd64 /usr/local/bin/minikube

🚀 Start Cluster
minikube start --driver=docker --force

📦 Pod Creation (Imperative)
kubectl run mypod --image=nginx

📄 Pod Creation (Declarative)
apiVersion: v1
kind: Pod
metadata:
  name: nginx-pod
spec:
  containers:
    - name: nginx
      image: nginx



---

# ✅ Step 3: Add What Recruiters ACTUALLY Look For

Your notes are missing this 👇 (very important)

## Add these sections in every repo:

### 🔹 1. Real-Time Use Case
Example:
> “Used Kubernetes to deploy microservices with auto-scaling in AWS EKS”

---

### 🔹 2. Troubleshooting Section
Example:
Issue: minikube start failed with root user
Solution: Used --force flag


---

### 🔹 3. Architecture Diagram (Clean)
Use tools:
- draw.io
- lucidchart

(Not ASCII art like you wrote ❌)

---

### 🔹 4. Folder Structure

---

# ✅ Step 4: Build 1 STRONG PROJECT (Very Important)

Notes alone won’t get you job.

You need this 👇

## 🔥 Must-Have Project

### 👉 CI/CD Pipeline Project
GitHub → Jenkins → Docker → Kubernetes → AWS

Include:
- Jenkinsfile
- Dockerfile
- Kubernetes manifests
- Screenshots
- Architecture diagram

---

# ✅ Step 5: Make Your GitHub Look Professional

## Your Profile Should Have:

### 🔹 Profile README
Hi, I'm Pranay 👋

DevOps Engineer with 3.7 years experience in:

AWS
Kubernetes
Terraform
Jenkins

🔧 Projects:

CI/CD Pipeline on AWS
Kubernetes Deployment Automation

📫 Contact: LinkedIn | Email: gorantlapranay8@gmail.com


---

# ✅ Step 6: Push Code Properly

Bad:
file1.txt
notes.txt
newfile.txt

Good:

k8s-minikube-setup/
k8s-pod-deployment/
k8s-deployment-service/

---

# ✅ Step 7: Daily Contribution Strategy

Post:
- 1 small commit daily
- Improve README
- Add YAML files
- Add scripts

👉 Recruiters LOVE active profiles

---

# 🚀 Final Strategy (Very Important)

To reach **12–15 LPA**, your GitHub must show:

✔ Real projects  
✔ Clean documentation  
✔ Cloud usage (AWS EKS)  
✔ CI/CD pipelines  
✔ Troubleshooting skills  

---

# 🔥 Simple Action Plan (Follow This Exactly)

### Day 1:
- Create GitHub repos
- Clean your Kubernetes notes

### Day 2:
- Upload Minikube + Pod examples

### Day 3:
- Add Deployment + Service YAML

### Day 4:
- Start CI/CD project

### Day 5–7:
- Add Jenkins + Docker + K8s integration

---

# ⚠️ Final Honest Advice

Your notes show:
✔ You are learning well  
❌ But not presenting professionally  

👉 Difference between:
- 6 LPA → Notes  
- 15 LPA → Projects + clean GitHub  

---

