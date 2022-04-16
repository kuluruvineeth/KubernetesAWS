# KubernetesAWS

## AWS Services Covered

| S.No | AWS Service Name |
| ---- | ---------------- |
| 1.   | AWS EKS - Elastic Kubernetes Service  |
| 2.   | AWS EBS - Elastic Block Store  |
| 3.   | AWS RDS - Relational Database Service MySQL  |
| 4.   | AWS CLB - Classic Load Balancer  |
| 5.   | AWS NLB - Network Load Balancer  |
| 6.   | AWS ALB - Application Load Balancer  |
| 7.   | AWS Fargate - Serverless  |
| 8.   | AWS ECR - Elastic Container Registry  |
| 9.   | AWS Developer Tool - CodeCommit  |
| 10.  | AWS Developer Tool - CodeBuild  |
| 11.  | AWS Developer Tool - CodePipeline  |
| 12.  | AWS X-Ray  |
| 13.  | AWS CloudWatch - Container Insights  |
| 14.  | AWS CloudWatch - Log Groups & Log Insights  |
| 15.  | AWS CloudWatch - Alarms  |
| 16.  | AWS Route53  |
| 17.  | AWS Certificate Manager  |
| 18.  | EKS CLI - eksctl  |


## Kubernetes Concepts Covered

| S.No | Kubernetes Concept Name |
| ---- | ------------------- |
| 1.   | Kubernetes Architecture  |
| 2.   | Pods  |
| 3.   | ReplicaSets  |
| 4.   | Deployments  |
| 5.   | Services - Node Port Service  |
| 6.   | Services - Cluster IP Service  |
| 7.   | Services - External Name Service  |
| 8.   | Services - Ingress Service  |
| 9.   | Services - Ingress SSL & SSL Redirect  |
| 10.  | Services - Ingress & External DNS  |
| 11.  | Imperative - with kubectl  |
| 12.  | Declarative - Declarative with YAML  |
| 13.  | Secrets |
| 14.  | Init Containers |
| 15.  | Liveness & Readiness Probes |
| 16.  | Requests & Limits |
| 17.  | Namespaces - Imperative |
| 18.  | Namespaces - Limit Range |
| 19.  | Namespaces - Resource Quota |
| 20.  | Storage Classes |
| 21.  | Persistent Volumes |
| 22.  | Persistent Volume Claims |
| 23.  | Services - Load Balancers |
| 24.  | Annotations |
| 25.  | Canary Deployments |
| 26.  | HPA - Horizontal Pod Autoscaler |
| 27.  | VPA - Vertical Pod Autoscaler |
| 28.  | CA - Cluster Autoscaler |
| 29.  | DaemonSets |
| 30.  | DaemonSets - Fluentd for logs |
| 31.  | Config Maps |

## List of Docker Images  on Docker Hub

| Application Name  | Docker Image Name |
| ----------------- | ----------------- |
| Simple Nginx V1  | stacksimplify/kubenginx:1.0.0  |
| Spring Boot Hello World API  | stacksimplify/kube-helloworld:1.0.0  |
| Simple Nginx V2  | stacksimplify/kubenginx:2.0.0  |
| Simple Nginx V3  | stacksimplify/kubenginx:3.0.0  |
| Simple Nginx V4  | stacksimplify/kubenginx:4.0.0  |
| Backend Application  | stacksimplify/kube-helloworld:1.0.0  |
| Frontend Application  | stacksimplify/kube-frontend-nginx:1.0.0  |
| Kube Nginx App1  | stacksimplify/kube-nginxapp1:1.0.0  |
| Kube Nginx App2  | stacksimplify/kube-nginxapp2:1.0.0  |
| Kube Nginx App2  | stacksimplify/kube-nginxapp2:1.0.0  |
| User Management Microservice with MySQLDB  | stacksimplify/kube-usermanagement-microservice:1.0.0  |
| User Management Microservice with H2 DB  | stacksimplify/kube-usermanagement-microservice:2.0.0-H2DB  |
| User Management Microservice with MySQL DB and AWS X-Ray  | stacksimplify/kube-usermanagement-microservice:3.0.0-AWS-XRay-MySQLDB  |
| User Management Microservice with H2 DB and AWS X-Ray  | stacksimplify/kube-usermanagement-microservice:4.0.0-AWS-XRay-H2DB  |
| Notification Microservice V1  | stacksimplify/kube-notifications-microservice:1.0.0  |
| Notification Microservice V2  | stacksimplify/kube-notifications-microservice:2.0.0  |
| Notification Microservice V1 with AWS X-Ray  | stacksimplify/kube-notifications-microservice:3.0.0-AWS-XRay  |
| Notification Microservice V2 with AWS X-Ray  | stacksimplify/kube-notifications-microservice:4.0.0-AWS-XRay  |


## List of Docker Images you build in AWS ECR

| Application Name  | Docker Image Name |
| ----------------- | ----------------- |
| AWS Elastic Container Registry  | YOUR-AWS-ACCOUNT-ID.dkr.ecr.us-east-1.amazonaws.com/aws-ecr-kubenginx:DATETIME-REPOID  |
| DevOps Usecase  | YOUR-AWS-ACCOUNT-ID.dkr.ecr.us-east-1.amazonaws.com/eks-devops-nginx:DATETIME-REPOID  |


## Sample Applications
- User Management Microservice
- Notification Miroservice
- Nginx Applications