# 🔐 Kali Linux Cybersecurity Lab

*Setting up a virtual environment for cybersecurity learning and ethical hacking practice.*

## 📌 Project Overview

This project documents the setup of a virtual cybersecurity lab using Oracle VirtualBox and Kali Linux.

The lab provides an environment for learning Linux administration, virtual networking, and practical cybersecurity concepts.

## 🎯 Project Objectives

- Install and configure Oracle VirtualBox.
- Set up Kali Linux as a virtual machine.
- Create a VirtualBox NAT Network.
- Configure the virtual machine's network adapter.
- Examine IP addressing and network connectivity.
- Establish a foundation for future cybersecurity exercises.

## 🏗️ Lab Environment

The lab uses the following technologies:

| Component | Configuration |
|---|---|
| Host Operating System | Windows 11 |
| Hypervisor | Oracle VirtualBox |
| Guest Operating System | Kali Linux |
| Allocated Virtual Machine RAM | 2048 MB |
| Network Mode | NAT Network |
| Network Name | NatNetwork |
| IPv4 Network | 10.0.0.0/24 |

## ⚙️ Lab Architecture

The laboratory consists of a Windows host running Oracle VirtualBox, with Kali Linux operating as a guest virtual machine.

The Kali Linux virtual machine is connected to a dedicated NAT Network. This provides a foundation for adding other virtual machines for future cybersecurity exercises.

## 🪜 Implementation Summary

### 1. VirtualBox Installation

Installed Oracle VirtualBox to provide the virtualization platform for the cybersecurity lab.

### 2. Kali Linux Deployment

Downloaded and imported Kali Linux into VirtualBox as a guest operating system.

### 3. NAT Network Configuration

Created a dedicated VirtualBox NAT Network named `NatNetwork` using the IPv4 network `10.0.0.0/24`.

The NAT Network provides connectivity for virtual machines attached to it and allows communication between participating VMs.

### 4. Virtual Machine Configuration

Configured the Kali Linux virtual machine with 2048 MB of RAM and connected its network adapter to the NAT Network.

### 5. Network Inspection

Used Linux networking commands to inspect the virtual machine's network configuration.

```bash
ip addr
ip route
```

These commands display network interface addresses and routing information.

## 🔎 Network Verification Commands

| Command | Purpose |
|---|---|
| `ip addr` | Inspect IP addresses |
| `ip route` | Display routing information |
| `ping -c 4 8.8.8.8` | Test external IP connectivity |

## 🧠 Key Learning Outcomes

Through this project, I gained practical experience with:

- Virtual machine creation and management.
- Kali Linux deployment.
- Virtual network configuration.
- Basic Linux networking commands.
- IPv4 addressing and routing concepts.
- Preparing a virtual environment for cybersecurity practice.

## 🔐 Security and Ethical Considerations

This laboratory is intended for educational purposes and authorized security testing.

- Only test systems that you own or have explicit permission to assess.
- Protect passwords, credentials, and sensitive information.
- Use controlled lab environments for practical security exercises.

## 🚀 Future Development

- Introduce additional virtual machines into the lab.
- Perform authorized network reconnaissance using Nmap.
- Practice vulnerability assessment.
- Explore packet analysis and web application security.

## 🔗 Tools and Resources

| Tool | Purpose | Official Resource |
|---|---|---|
| Oracle VirtualBox | Virtualization platform | [VirtualBox](https://www.virtualbox.org/wiki/Downloads) |
| Kali Linux | Cybersecurity operating system | [Kali Linux](https://www.kali.org/get-kali/) |
| GitHub | Project hosting and version control | [GitHub](https://github.com/) |

## 👤 Author

**Kasum Damilola**  
Cybersecurity student/enthusiasts 

**LinkedIn:** www.linkedin.com/in/damilola-kasum

## 📌 Project Information

- **Program:** Cybersecurity at Networkwalks
- **Week:** 01
- **Project:** Cybersecurity and Penetration Testing Lab Setup
- **Platform:** GitHub

---

*This project establishes a foundation for practical cybersecurity learning and future security assessment exercises.*
