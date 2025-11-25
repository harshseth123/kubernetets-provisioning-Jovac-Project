# kubernetets-provisioning-Jovac-Project
summer internship course
# Welcome to Our Project :-

# Kubernetes Cluster Provisioning using Ansible and kubeadm

This project automates the provisioning of a **multi-node Kubernetes cluster** using **Ansible**, **kubeadm**, and **containerd**.  
It sets up one Master Node and multiple Worker Nodes, installs all required dependencies, initializes the control panel , and joins the workers automatically.

# Features

- Automated installation of:
  - containerd
  - kubeadm, kubelet, kubectl
- Swap disable + sysctl configuration
- Kubernetes master initialization
- Worker node auto-join with token
- Calico CNI networking
- Works with Multipass / cloud VMs / local VMs
- Simple, beginner-friendly Ansible setup
