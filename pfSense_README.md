# pfSense Firewall Configuration Lab

## Overview

This project is part of the **Cyber Home Lab** repository. It walks through the step-by-step process of installing and configuring a **pfSense open-source firewall appliance** inside your virtual lab environment. This lab teaches you how to deploy a firewall, manage network traffic rules, and enforce security policies between your virtual machines and the internet.

---

## What is pfSense?

A **firewall** is a network security device that monitors and filters incoming and outgoing traffic based on an organization's previously established security policies.  
**pfSense** is one of the most widely used, free, and open-source firewall solutions in the industry.

---

## Lab Features

- Download and install pfSense in VirtualBox
- Connect pfSense to your existing virtual lab network via Bridged Adapter
- Configure network interfaces (WAN, optional LAN)
- Access the pfSense WebGUI
- Set static IP, DNS, and default gateway settings
- Create and enforce a custom firewall rule to block access to a specific domain
- Test the rule implementation from your Windows 10 virtual machine

---

## Prerequisites

- **VirtualBox** installed and configured (see [Cyber Home Lab Guide](./README.md))
- Existing virtual machines (Windows 10, Kali Linux, Metasploitable)
- ISO image for pfSense downloaded from:  
  [https://www.pfsense.org/download/](https://www.pfsense.org/download/)

---

## Lab Setup Process

1. Download pfSense ISO and 7-Zip utility for file extraction
2. Import pfSense into VirtualBox as a new virtual machine
3. Configure virtual hardware and network adapters
4. Install pfSense using Auto (UFS) BIOS partitioning
5. Remove ISO attachment post-installation to prevent boot loops
6. Finalize installation and skip VLAN configuration for simplicity
7. Set WAN interface and IP address settings via WebGUI
8. Create a firewall alias for `defendtheweb.net`
9. Add a firewall rule to block outbound traffic to that IP
10. Update your physical host’s network settings to route through the pfSense firewall
11. Test the rule by attempting to visit the blocked domain from your Windows 10 VM

---

## Key Commands

From Windows 10 VM:
```bash
nslookup defendtheweb.net
ping [pfSense IP]
