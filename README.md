# 🔍 Windows Digital Forensics & Incident Response (DFIR)
## Official Training Labs | Pakistan Cyber Security Defense Foundation (PCSDF)

[![PCSDF](https://img.shields.io/badge/Organization-PCSDF-green)](https://github.com/pcsdf)
[![Domain](https://img.shields.io/badge/Domain-Digital%20Forensics-blue)](#-projects-overview)
[![Level](https://img.shields.io/badge/Level-Beginner-orange)](#-getting-started)

> **A series of high-impact, hands-on forensic investigation labs. This repository is designed to train PCSDF members in the art of extracting digital evidence, analyzing artifacts, and reconstructing security incidents on Windows environments.**

---

## 📂 Projects Overview

These labs focus on the most critical artifacts found during a Windows forensic investigation.

### 1. [Security Event Log Investigation](https://github.com/pcsdf/Windows-Forensics/blob/main/project-1-investigating-windows-event-logs-for-security-incidents.md)
Learn to parse and analyze Windows Event Logs (EVTX) to identify unauthorized logins, brute-force attacks, and lateral movement.

### 2. [Windows Registry Analysis](https://github.com/pcsdf/Windows-Forensics/blob/main/project-2-Analyzing-Windows-registry-for-evidences.md)
Extract evidence of malicious activity from the Registry, including persistence mechanisms, recently run programs (UserAssist), and connected USB devices.

### 3. [File System & Artifact Analysis](https://github.com/pcsdf/Windows-Forensics/blob/main/project-3-Forensic-analysis-of-Windows-file-system-and-artifacts.md)
Deep dive into the Master File Table (MFT), Prefetch files, and Shimcache to reconstruct a timeline of attacker activity.

### 4. [Browser Forensic Analysis](https://github.com/pcsdf/Windows-Forensics/blob/main/project-4-extracting-and-interpreting-browser-artifacts-on-windows.md)
Extract and interpret history, cache, and session data from Chrome, Firefox, and Edge to track web-based entry points.

### 5. [Data Recovery & Deleted File Analysis](https://github.com/pcsdf/Windows-Forensics/blob/main/project-5-Recovering-and-Analyzing-Deleted-Files-on-Windows-Systems.md)
Techniques for recovering files deleted by attackers to hide their tracks, using carving tools and slack space analysis.

---

## 🚀 Getting Started

To begin these labs, ensure you are working in a **secure, isolated virtual machine (VM)**.

### 1. Prepare your Environment
Clone the official PCSDF lab files to your forensic workstation:
```bash
git clone [https://github.com/pcsdf/Windows-Forensics.git](https://github.com/pcsdf/Windows-Forensics.git)
cd Windows-Forensics
