# HCL DevOps Test Cloud Documentation

## Overview
This repository provides documentation for deploying **HCL DevOps Test Hub** in Kubernetes-based environments.  

HCL DevOps Test Hub consolidates test data, test environments, test executions, and reporting into a single web-based interface for testers and non-testers alike. It is **Kubernetes-native**, requiring a cluster to run.  

For users without an existing cluster, we provide scripts to quickly provision a lightweight environment using **K3s**.

## Supported Platforms
- [Kubernetes (generic)](k8s/README.md)  
- [Azure Kubernetes Service (AKS)](azure/README.md)  
- [IBM Red Hat OpenShift](openshift/README.md)  
- [K3s on RHEL & Ubuntu](k3s/README.md)  

## Audience
These guides are intended for administrators and DevOps engineers who want to deploy and manage HCL DevOps Test Hub.  

Each `README.md` provides details on:  
- Prerequisites and setup  
- Deployment steps  
- Upgrades and backups  
- Uninstallation procedures  
- Security considerations  
- Known limitations  

## License
This project is licensed under the [Apache License 2.0](LICENSE).  
