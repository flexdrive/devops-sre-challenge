# DevOps / SRE Challenge

## The Challenge
You are the new member of a dynamic engineering team who is preparing to split a monolith application and deploy microservices. The team has chosen AWS as a cloud provider and Kubernetes as a container orchestration platform.

You are tasked with provisioning the Kubernetes cluster to an AWS account with the following considerations:
- Cluster does not require any nodes be available on public network
- Cluster state and resources should be declarative and stored in Github
- A bastion should be configured to allow access to cluster nodes
- Access Permissions should be considered. Be prepared to discuss how to only provide cluster resources with the necessary AWS API access
- A centralized logging solution should be enabled in the cluster
- A centralized monitoring solution should be deployed

## Guidelines
To aid in reducing the time required to complete the challenge, please consider the following guidelines:
- use KOPs as K8s cluster deployment tool
- limit time needed to complete; we will discuss any items not able to be completed

## Next Steps
If considered for in-face interview, please be prepared to deploy cluster and recommend best practices for packaging applications for deployment to cluster.  We will also discuss the choices made to fulfill the challenge requirements and understand what you might do differently with more time.
