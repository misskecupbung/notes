## AWS User Group Meetup September 2023 - Workshop

### Components of Amazon EKS
1. API Server
  - serves the kubernetes api and acts as the entry point
2. Etcd
  - Consistent and highly-available key value store for all cluster data
3. Controller Manager
  - Ensures the desired state of the system matches the actual state.
4. Scheduler
  - Assigns work, in the form of pods, to worker nodes

### Materials
- https://github.com/badri-k7/aws-devops
- https://github.com/badri-k7/aws-devops/tree/main/module-aws-application-serices/eks/

### Components of Amazon EKS
- Managed Node Groups
  - these are groups of amazon ec2 instances that are registered with a kubernetes cluster.
  - managed automatically by eks. this includes updates, patching, and scaling
  - can be easily integrated with other aws services like auto scaling group
  - simplifies the node provisioning process for users.

### EKS Storage Overview
- EKS Storage with EFS
  - intro to kubernetes storage and its importance
  - persistent volumes (pvs) in kubernetes
  - aws storage integrations with eks

