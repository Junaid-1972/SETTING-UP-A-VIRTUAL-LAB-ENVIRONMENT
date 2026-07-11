# SETTING-UP-A-VIRTUAL-LAB-ENVIRONMENT
In this project i created 3 different virtual machines 
- Windows server
- 2 windows 8 client

Setting up a virtual lab environment aligns with the NIST Cybersecurity Framework (CSF) PROTECT function, specifically PR.AC (Access Control) and PR.PT (Protective Technology) categories using segmentation, virtualization, and monitoring to protect systems. In ISO/IEC 27001:2022, it maps most closely to Annex A.5 (Organizational Controls) Policies for testing, segregation of environments, and governance of lab use and Annex A.8 (Technological Controls) Covers technical measures like access control, system isolation, secure configurations, and monitoring—all core to virtual labs.


# Setting Up a Virtual Lab Environment

**Project Overview**  
In this project, I built a virtual lab environment using Oracle VirtualBox, featuring one **Windows Server 2022** and two **Windows 8** client machines.

---

## Table of Contents

- [Virtualization Overview]
- [Virtualization Technologies & Tools]
- [Virtualization Software]
- [Downloading ISOs]
- [Creating Virtual Machines]
- [Configurations]
- [Conclusion]

---

## Virtualization Overview

Virtualization involves abstracting physical hardware resources to create multiple virtual instances (virtual machines or VMs) that operate independently on a single physical host machine. Each VM behaves like a separate computer with its own virtual CPU, memory, storage, and network interfaces, while running its own operating system and applications.

Virtualization is a foundational technology in modern computing, enabling efficient use of servers, storage, networks, and operating systems.

### Key Aspects of Virtualization

1. **Resource Optimization** — Better utilization of physical hardware by hosting multiple VMs on one host.
2. **Isolation** — VMs are isolated from each other and the host, improving security and stability.
3. **Flexibility & Agility** — Easy creation, cloning, and migration of VMs for testing and deployment.
4. **Cost Efficiency** — Reduced hardware needs lower costs for space, power, and equipment.
5. **Disaster Recovery** — Snapshots and backups make recovery faster and more reliable.
6. **Testing & Development** — Safe environment for development and testing without affecting production systems.

---

## Virtualization Technologies & Tools

- **Hypervisors**: Software that manages virtual machines.
  - **Type 1 (Bare-metal)**: Runs directly on hardware (e.g., VMware ESXi, Microsoft Hyper-V).
  - **Type 2 (Hosted)**: Runs on top of a host OS (e.g., Oracle VirtualBox, VMware Workstation).
- **Containers**: Lightweight virtualization (e.g., Docker, LXC).

### Tools & Platform Used
- **Oracle VirtualBox**: Primary virtualization software.
- **Host System**: Windows (running VirtualBox).
- **Guest Operating Systems**: Windows 8 (x64) and Windows Server 2022.

---

## Virtual Machines — Computers Within Your Computer

Virtual machines behave like real physical computers but run as software on your host system. You can install operating systems, applications, restart, or shut them down just like physical machines.

This flexibility makes VMs ideal for building personal IT labs, allowing safe experimentation, learning, and testing without additional hardware.

---

## Virtualization Software

For this project, I used **Oracle VM VirtualBox** because it is free, cross-platform (Windows/Linux), and user-friendly. Most setup steps are similar across other Type 
