# Enterprise Linux Virtualization Lab

## Project Overview

This project documents the successful deployment of an Ubuntu Linux virtual machine using Oracle VirtualBox on a Windows host machine.

Rather than simply installing Ubuntu, this project demonstrates my understanding of virtualization, virtual machine provisioning, Linux deployment, resource allocation, and infrastructure troubleshooting.

This repository is the first project in my Cloud Engineering Portfolio, where I document my hands on infrastructure projects while learning Microsoft Azure and Amazon Web Services (AWS).

---

## Business Scenario

As a Junior Cloud Engineer, one of the first responsibilities is to prepare reliable environments for testing, administration, and future cloud deployments.

Before working with cloud platforms such as Microsoft Azure and AWS, engineers often build local virtual environments to practice Linux administration, networking, and infrastructure management.

This project simulates that process by creating a reusable Ubuntu virtual machine using Oracle VirtualBox.

---

## Project Objectives

The objectives of this project were to:

- Learn the fundamentals of virtualization.
- Install Oracle VirtualBox.
- Deploy an Ubuntu Linux virtual machine.
- Allocate compute resources (CPU, Memory, Storage).
- Configure a bootable Ubuntu ISO.
- Successfully install Ubuntu Desktop.
- Document the deployment process.
- Troubleshoot installation issues.
- Prepare a Linux environment for future cloud projects.

---

## Solution Architecture

The virtual environment created in this project consists of a Windows host operating system running Oracle VirtualBox as the virtualization platform. Oracle VirtualBox provides the resources required to host an Ubuntu Linux virtual machine, creating an isolated environment for learning Linux administration and cloud infrastructure concepts.

```text
+------------------------------------------------+
|            Physical Laptop (Host)              |
|------------------------------------------------|
| Windows 11 Operating System                    |
|                                                |
|  +------------------------------------------+  |
|  | Oracle VirtualBox (Type 2 Hypervisor)    |  |
|  |                                          |  |
|  |  +------------------------------------+  |  |
|  |  | Ubuntu Desktop Virtual Machine     |  |  |
|  |  |                                    |  |  |
|  |  | • 6 GB RAM                         |  |  |
|  |  | • 4 vCPUs                          |  |  |
|  |  | • 50 GB Virtual Disk               |  |  |
|  |  +------------------------------------+  |  |
|  +------------------------------------------+  |
+------------------------------------------------+
```
