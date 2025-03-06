## About Me

My name is [Your Name], and I’m a career-changer with a passion for technology, problem-solving, and cybersecurity. After working in [Previous Industry], I decided to pursue a hands-on learning approach to network security and incident response by building my own home lab.

This project is not just a technical exercise — it’s part of my personal journey into the world of Blue Team operations, where I hope to apply my curiosity, attention to detail, and analytical mindset to help organizations detect and respond to cyber threats.

I’m documenting my learning to:
- Track my progress.
- Share with others who are also learning.
- Demonstrate my practical skills to future employers.


# 🏡 Home Network & Cybersecurity Lab Project

## 📖 Overview

This repository documents my personal **home lab project**, designed to develop and showcase my hands-on skills in **Blue Team operations, network security, threat detection, log analysis, and incident response**.

The goal is to **secure my home network**, build a **virtualized attack/defense lab**, and simulate real-world threats — all while documenting each phase to demonstrate my practical knowledge to recruiters, hiring managers, and the broader cybersecurity community.

---

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

---

### 2️⃣ Phase 2 - Home Network Mapping & Security (Core Fundamentals)

- Performed full **asset inventory** of my home network.
- Used tools like **Nmap** and **ARP-scan** to identify:
    - IP addresses
    - MAC addresses
    - Operating systems
    - Open ports and services
- Applied basic **router hardening** and network segmentation.

| Device | IP Address | MAC Address | OS | Open Ports |
|---|---|---|---|---|
| Main Laptop | 192.168.1.100 | xx:xx:xx:xx | Windows 11 | 22, 445 |
| Smart TV | 192.168.1.102 | xx:xx:xx:xx | Linux | 443 |

### Home Network Hardening Checklist
- ✅ Changed default router credentials
- ✅ Disabled remote administration
- ✅ Enabled WPA3 for Wi-Fi
- ✅ Segmented IoT devices into **Guest Network**
- ✅ Enabled DNS filtering using OpenDNS

---

### 3️⃣ Phase 3 - Network Traffic Monitoring & Baseline Analysis

- Captured real-time traffic using **Wireshark**.
- Documented normal traffic patterns for home devices.
- Analyzed:
    - DHCP traffic (device discovery)
    - DNS queries (device lookups)
    - Typical traffic from smart TVs, laptops, phones, etc.
- Created comparison table of **normal vs suspicious traffic**.

| Protocol | Source | Destination | Notes |
|---|---|---|---|
| DNS | Smart TV | External DNS | Normal |
| SSH | Unknown Device | Router | 🚨 Suspicious |

---

### 4️⃣ Phase 4 - Vulnerability Scanning of Home Network Devices

- Used **Nmap**, **Nikto**, and **OpenVAS** to assess vulnerabilities.
- Focused on **router web interfaces**, **smart devices**, and internal VMs.
- Documented identified risks and recommended mitigations.

| Device | Finding | Severity | Recommendation |
|---|---|---|---|
| Home Router | Outdated firmware | High | Apply firmware update |
| Windows VM | SMBv1 enabled | Critical | Disable SMBv1 |

---

### 5️⃣ Phase 5 - Simulated Attacks Against Lab VMs (Red Team Exercise)

- Deployed **Windows 10 VM** as vulnerable target.
- Used Kali to perform simulated attacks:
    - **Nmap scanning**
    - **Hydra SSH brute force**
    - **Gobuster directory brute force**
    - Basic **phishing simulation (future phase)**

| Attack Type | Tool | Target | Outcome |
|---|---|---|---|
| Network Recon | Nmap | Windows VM | Detected |
| SSH Brute Force | Hydra | Windows VM | Blocked by Fail2Ban |
| Directory Brute Force | Gobuster | Web server VM | Discovered `/backup.zip` |

---

### 6️⃣ Phase 6 - Centralized Log Collection & Analysis

- Set up **Elastic Stack (Elasticsearch, Logstash, Kibana)** to collect:
    - Windows logs via **Winlogbeat** + **Sysmon**.
    - Linux logs via **Auditd** + **Filebeat**.
- Configured **dashboards** and **alerts** to monitor for suspicious activity.

| Log Source | Collection Tool | Destination |
|---|---|---|
| Windows VM | Sysmon + Winlogbeat | ElasticSearch |
| Kali Linux | Auditd + Filebeat | ElasticSearch |
| Home Router (future) | Syslog (if supported) | ElasticSearch |

---

### 7️⃣ Phase 7 - Incident Response Documentation (Blue Team Reporting)

-

