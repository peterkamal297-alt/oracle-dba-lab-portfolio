# 🐧 01 — Linux Administration (Foundation Layer)

## 📌 Overview
This module establishes the secure, enterprise-grade Linux operating system foundation required to host high-performance Oracle Database 19c environments. It focuses on OS hardening, resource management, and storage architecture.

## 🛠️ Key Technical Tasks & Implementation
* **OS Installation & Partitioning:** Deployed Oracle Linux 8 with customized partition schemes optimized for database workloads (`/u01`, swap, and root).
* **Security Hardening:** Configured strict user/group access models, SSH security parameters, and firewall rules (`firewalld`).
* **Kernel & Resource Limits:** Tuned system parameters (`sysctl.conf`) and resource limits (`security/limits.conf`) to meet Oracle prerequisites.
* **Storage Management (LVM):** Implemented Logical Volume Management for dynamic storage allocation and scalable filesystems.

## 📁 Files & Documentation
* [Linux Installation Guide (PDF)](./linux-installation.pdf)
* [Linux Administration Guide (PDF)](./linux-administration.pdf)
