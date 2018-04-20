# DevOps / SRE Challenge

## The Challenge
You are the new member of a dynamic engineering team who is preparing to split a monolith application and deploy microservices. The team has chosen AWS as a cloud provider and Kubernetes as a container orchestration platform.

You are tasked with provisioning the Kubernetes cluster to an AWS account with the following considerations:
- Cluster does not require any nodes be available on public network
- Cluster resources should be exposed through some type of Ingress
- Access Permissions should be considered. Provide ability to set specific IAM roles on K8s pods
- A centralized logging solution should be enabled in the cluster
- A centralized monitoring solution should be deployed

## Sample Applications to Deploy


Keep in mind, this is just an assessment and should not a production system.  KISS principle.

Please implement as much of a solution with the considerations above, commit it to a repo and share it with us.
