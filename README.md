## About Me

Hi, I’m Jerry — a career-changer with a passion for IT and cybersecurity. After working in Education for nearly a decade, my curiosity about technology grew into a hands-on learning journey. To turn my interest into real-world skills, I’ve built a home lab to:

- Explore network security fundamentals.
- Practice threat detection and incident response.
- Document my learning and share my progress with others.


# 🏡 Home Network & Cybersecurity Lab Project

## 📖 Overview

This repository documents my personal **home lab project**, designed to develop and showcase my hands-on skills in **Blue Team operations, network security, threat detection, log analysis, and incident response**.

The goal is to **secure my home network**, build a **virtualized attack/defense lab**, and simulate real-world threats — all while documenting each phase to demonstrate my practical knowledge to recruiters, hiring managers, and the broader cybersecurity community.

| [Phase 1 - Home Lab Installation & Documentation](./phase-1-installation/README.md) | ✅ Completed | Set up the Kali Linux VM, configured network adapters, installed tools, and documented the environment. |
| [Phase 2 - Home Network Mapping & Security](./phase-2-home-network/README.md) | 🚧 In Progress | Identify all devices on my home network, map open ports, and document device profiles. |
| [Phase 3 - Network Traffic Monitoring](./phase-3-traffic-analysis/README.md) | 🚧 Planned | Capture and analyze baseline traffic patterns using Wireshark. |
| [Phase 4 - Vulnerability Scanning](./phase-4-vulnerability-scanning/README.md) | 🚧 Planned | Scan for open ports and vulnerabilities on network devices. |
| [Phase 5 - Attack Simulations](./phase-5-attack-simulation/README.md) | 🚧 Planned | Simulate attacks between VMs (brute force, directory scans) and practice detection. |
| [Phase 6 - Log Collection & SIEM Setup](./phase-6-log-collection/README.md) | 🚧 Planned | Forward logs from Kali and other VMs to a centralized ELK stack for monitoring. |
| [Phase 7 - Incident Response Documentation](./phase-7-incident-response/README.md) | 🚧 Planned | Write a full incident response report based on a simulated attack. |
| [Phase 8 - Final Summary & Lessons Learned](./phase-8-summary/README.md) | 🚧 Planned | Summarize key takeaways, skills learned, and future improvements.


## ⚙️ Project Phases

### 1️⃣ Phase 1 - Home Lab Installation & Documentation

- Installed Kali Linux in VirtualBox as primary attack and analysis platform.
- Documented virtual machine specs, network settings, and initial updates.
- Created baseline system snapshot.
- Installed essential tools for network scanning, traffic analysis, and vulnerability assessment.

| Component | Specification |
|---|---|
| Host OS | Windows 11 |
| Virtualization Platform | Oracle VirtualBox 7.x |
| Kali Linux VM | 2 CPUs, 4GB RAM, 40GB disk |
| Network Adapter | NAT (for updates) + Host-Only (for internal traffic) |

NOTE: I haven't enabled the second adapter yet as I'm still setting up. I'll enable it later when I do simulations on a separate VM.
---


