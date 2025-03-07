## About Me

Hi, I’m Jerry — a career-changer with a passion for IT and cybersecurity. After working in Education for nearly a decade, my curiosity about technology grew into a hands-on learning journey. To turn my interest into real-world skills, I’ve built a home lab to:

- Explore network security fundamentals.
- Practice threat detection and incident response.
- Document my learning and share my progress with others.


# 🏡 Home Network & Cybersecurity Lab Project

## 📖 Overview

# 🔐 Home Lab Cybersecurity Project

This repository documents my personal **Home Lab Cybersecurity Project**, designed to help me develop hands-on skills in **network security, threat detection, incident response, and Blue Team operations**.

The project is divided into multiple phases, starting from building the environment to simulating and detecting attacks. Each phase focuses on a **core cybersecurity skill**, and the entire journey is documented here.

---

## 📋 Project Phases Overview

The table below provides a high-level summary of the project phases, including their status and focus areas. Each phase links to its own folder containing detailed documentation, screenshots, and findings.

| Phase | Status | Description |
|---|---|---|
| [Phase 1 - Home Lab Installation & Documentation](./phase-1-installation/README.md) | ✅ Completed | Set up the Kali Linux VM, configured network adapters, installed tools, and documented the environment. |
| [Phase 2 - Home Network Mapping & Security](./phase-2-home-network/README.md) | 🚧 In Progress | Identify all devices on my home network, map open ports, and document device profiles. |
| [Phase 3 - Network Traffic Monitoring](./phase-3-traffic-analysis/README.md) | 🚧 Planned | Capture and analyze baseline traffic patterns using Wireshark. |
| [Phase 4 - Vulnerability Scanning](./phase-4-vulnerability-scanning/README.md) | 🚧 Planned | Scan for open ports and vulnerabilities on network devices. |
| [Phase 5 - Attack Simulations](./phase-5-attack-simulation/README.md) | 🚧 Planned | Simulate attacks between VMs (brute force, directory scans) and practice detection. |
| [Phase 6 - Log Collection & SIEM Setup](./phase-6-log-collection/README.md) | 🚧 Planned | Forward logs from Kali and other VMs to a centralized ELK stack for monitoring. |
| [Phase 7 - Incident Response Documentation](./phase-7-incident-response/README.md) | 🚧 Planned | Write a full incident response report based on a simulated attack. |
| [Phase 8 - Final Summary & Lessons Learned](./phase-8-summary/README.md) | 🚧 Planned | Summarize key takeaways, skills learned, and future improvements. |

---

## ⚙️ Phase 1 - Home Lab Installation & Documentation

### Overview
This phase covers the initial setup and documentation of my **Kali Linux virtual machine**, which will act as my primary attack and analysis platform.

Key steps include:
- Installing Kali Linux in **VirtualBox**.
- Configuring the **network adapters**.
- Documenting system specs and initial configurations.
- Taking a **baseline snapshot** for rollback if needed.
- Installing essential tools for **scanning, traffic analysis, and vulnerability assessment**.

---

### 🔧 System Specifications

| Component | Specification |
|---|---|
| Host OS | Windows 11 |
| Virtualization Platform | Oracle VirtualBox 7.x |
| Kali Linux VM | 2 CPUs, 4GB RAM, 40GB disk |
| Network Adapter | NAT (for updates) + Host-Only (for internal traffic, not yet enabled) |

**Note:** The Host-Only adapter is not enabled yet. It will be configured later when simulating attacks on a separate target VM. This separation keeps lab traffic isolated from my real home network.

---

### 📸 Screenshots & Documentation

- All installation and configuration screenshots for Phase 1 are stored in the folder:  
  📂 [Phase 1 Screenshots](./phase-1-installation/screenshots/)

---

## 📌 What’s Next

The next phase will focus on **scanning and documenting my home network**, identifying all devices, and mapping open ports. This will build a baseline inventory for future monitoring and analysis.

---

## 📣 About Me

Hi, I’m Jerry — a career-changer with a growing passion for IT and cybersecurity. This project is part of my **hands-on learning journey** as I transition into the field, with a focus on **Blue Team operations**, **threat detection**, and **incident response**.

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN-URL)

---

## 🏷️ Tags
`#Cybersecurity` `#HomeLab` `#SOCAnalyst` `#BlueTeam` `#IncidentResponse`
