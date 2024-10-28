🚀 Environment: Pilot
We can adapt this project to fit the consulting process and organize it with 16-week and 8-week timelines. This plan is designed for two people, with specific tasks to be completed each week. It focuses on hands-on exercises with assigned tasks. The two people can work together to complete these tasks.

📅 16-Week Plan
Week 1:
🔧 Kubernetes Cluster Setup:
- 5-node (1 Master + 4 Worker Nodes) Kubernetes cluster setup.
- Documentation of installation and configuration settings.
Week 2:
🏷️ Creating Namespaces:
- Creation of "test" and "production" namespaces.
Week 3:
👥 Creating Roles:
- Creating necessary roles for junior and senior groups and configuring permissions on namespaces.
Week 4:
🌐 Ingress Controller Setup:
- Installation and configuration of a chosen ingress controller (nginx, traefik, haproxy etc.).
Week 5:
🎯 Node Toleration and Affinity Setup:
- Setting node affinity and taint rules to schedule pods only on specific nodes for production.
Week 6:
💻 WordPress and MySQL Deployment - Test Environment:
- Deploying WordPress and MySQL in test namespace, defining services and persistent volumes.
Week 7:
🚀 WordPress and MySQL Deployment - Production Environment:
- Deploying WordPress and MySQL in production namespace.
Week 8:
🔄 Ingress Definitions:
- Creating ingress definitions for WordPress applications in test and production environments (testblog.example.com, companyblog.example.com).
Week 9:
⚙️ Deployment Configuration:
- Installing "ozgurozturknet/k8s:v1" deployment in production environment and adding probes.
Week 10:
⚖️ Load Balancer Setup:
- Providing external access through a load balancer type service for the deployment.
Week 11:
📈 Deployment Scale and Update Operations:
- First reducing deployment replicas to 3, then increasing to 10 and updating with v2 image.
Week 12:
📝 Fluentd DaemonSet Deployment:
- Deploying Fluentd application as a daemonset to the cluster.
Week 13:
🗄️ MongoDB StatefulSet Deployment:
- Deploying a 2-node MongoDB cluster as statefulset and verifying its operation.
Week 14:
🔑 Service Account and Pod Association:
- Creating a service account with read and list permissions and deploying a pod linked to this account. Listing cluster pods from within the pod.
Week 15:
🔄 Pod Evacuation and Node Isolation:
- Evacuating all pods from a worker node and preventing new pods from being scheduled on this node.
Week 16:
✅ Finalization and Review:
- Reviewing the entire process, fixing any deficiencies, and completing the project.

⚡ 8-Week Accelerated Plan
Week 1:
🔧 Kubernetes Cluster Setup and Namespaces:
- 5-node cluster setup and creation of "test" and "production" namespaces.
Week 2:
👥 Roles and Authorization:
- Creating roles for junior and senior groups and configuring namespace permissions.
Week 3:
🌐 Ingress Controller Setup and Node Affinity:
- Installing ingress controller and setting up node affinity for production-specific nodes.
Week 4:
💻 WordPress and MySQL Deployment:
- Deploying WordPress and MySQL in both test and production namespaces, configuring persistent volumes and services.
Week 5:
🔄 Ingress and Application Definitions:
- Setting up ingress configurations (testblog.example.com, companyblog.example.com) and defining resource limits.
Week 6:
🚀 Production Deployment:
- Installing "ozgurozturknet/k8s:v1" deployment, adding probes, and configuring load balancer.
Week 7:
📈 Scale and Update Operations:
- Decreasing and increasing deployment replicas and performing image updates. Deploying Fluentd daemonset.
Week 8:
🗄️ MongoDB Cluster and Service Account:
- Deploying MongoDB statefulset and service account, completing pod evacuation and node isolation operations.

👥 This plan is organized for a two-person team with hands-on exercises and can be completed within the specified timeframes.
