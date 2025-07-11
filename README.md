## Cyber Home Lab Project

# Overview

This repository contains a step-by-step guide and resources for building your own **Cybersecurity Virtual Home Lab** using VirtualBox and multiple virtual machines. This environment is designed to help aspiring and practicing cybersecurity professionals safely explore, experiment, and develop their skills in a controlled setting.

---

# Benefits of a Virtual Cyber Lab

- Safe environment to practice cybersecurity tools and scenarios
- Experiment with network configurations and malware analysis
- Gain hands-on experience with security tools and incident response
- Stay up to date with cybersecurity trends and tactics
- Build and showcase practical projects for your portfolio

---

# What You Can Build (Post Lab Deployment)

- Segmented networks for malware detonation
- Vulnerable web applications for ethical hacking practice
- Active Directory environment with Windows Server 2019 and Windows 10 client
- Kali Linux attacker machine
- Metasploitable 2 vulnerable Linux target
- Configurable firewalls, IDS/IPS, VPN setups
- Network scans and analysis using Nmap
- Basic honeypot implementation
- Customizable lab network with bridged adapter configurations

---

# System Requirements

| Component         | Minimum Requirement |
|:---------------- |:------------------ |
| **CPU**           | 64-bit, 2.0+ GHz processor |
| **RAM**           | 8 GB minimum |
| **Disk Space**    | 500 – 1000 GB |
| **Virtualization**| VT-x / AMD-V enabled in BIOS/UEFI |
| **Network**       | Wireless/Ethernet or compatible USB adapter |

---

# Required Downloads

| Tool / OS              | Download Link |
|:--------------------- |:-------------|
| **VirtualBox**         | [VirtualBox](https://www.virtualbox.org/wiki/Downloads) |
| **Kali Linux (OVA)**   | [Kali OVA Download](https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download/) |
| **Metasploitable 2 (OVA)** | [Metasploitable 2 Download](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/metasploitable-linux-2.0.0.zip/download) |
| **Windows 10 VM**      | [Windows 10 VM](https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/) |
| **Windows Server 2019 ISO** | [Windows Server 2019](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019) |

---

# Lab Setup Highlights

- Install and configure VirtualBox
- Import Kali Linux and Windows 10 VMs
- Manually configure Metasploitable 2 and Server 2019 virtual machines
- Set up bridged networking for VM communication
- Configure static IP addresses for each VM
- Install Active Directory and DNS roles on Windows Server 2019
- Create and manage users, groups, and organizational units with Active Directory Users and Computers (ADUC)
- Join Windows 10 client to Active Directory domain
- Test VM connectivity using `ping` and network tools
- Practice scanning, hardening, and managing systems in a realistic lab setup

---

# Project Use Cases & Exercises

- Malware detonation in isolated network segments
- Ethical hacking against vulnerable services
- Incident detection and response simulations
- Nmap scanning and vulnerability analysis
- Active Directory configuration and security testing
- Network security configuration exercises

---

# Notes

- Ensure virtualization is enabled in your system’s BIOS/UEFI settings
- Allocate sufficient RAM and CPU cores to each virtual machine as instructed
- Keep network adapters set to **Bridged Adapter** for internal lab communication
- Always verify VM IP addresses after startup using `ifconfig` or `ipconfig`
- Never expose this lab setup directly to the public internet

---

# Contributing

Contributions are welcome! Feel free to fork this repository, suggest improvements, or share additional lab exercises.

---

# License

This project is open source under the MIT License.

---

#  Acknowledgments

Thanks to the cybersecurity learning community for continued inspiration and knowledge sharing.

---

**Happy hacking and stay safe!**
















