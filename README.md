# 🔍 Windows Digital Forensics & Incident Response (DFIR)
## Official Training Labs | Pakistan Cyber Security Defense Foundation (PCSDF)

[![PCSDF](https://img.shields.io/badge/Organization-PCSDF-green)](https://github.com/pcsdf)
[![Domain](https://img.shields.io/badge/Domain-Digital%20Forensics-blue)](#-projects-overview)
[![Level](https://img.shields.io/badge/Level-Beginner-orange)](#-getting-started)

> **A series of high-impact, hands-on forensic investigation labs. This repository is designed to train PCSDF members in the art of extracting digital evidence, analyzing artifacts, and reconstructing security incidents on Windows environments.**

---

## 📂 Projects Overview

These labs focus on the most critical artifacts found during a Windows forensic investigation.

### 1. Security Event Log Investigation
Learn to parse and analyze Windows Event Logs (EVTX) to identify unauthorized logins, brute-force attacks, and lateral movement.

### 2. Windows Registry Analysis
Extract evidence of malicious activity from the Registry, including persistence mechanisms, recently run programs (UserAssist), and connected USB devices.

### 3. File System & Artifact Analysis
Deep dive into the Master File Table (MFT), Prefetch files, and Shimcache to reconstruct a timeline of attacker activity.

### 4. Browser Forensic Analysis
Extract and interpret history, cache, and session data from Chrome, Firefox, and Edge to track web-based entry points.

### 5. Data Recovery & Deleted File Analysis
Techniques for recovering files deleted by attackers to hide their tracks, using carving tools and slack space analysis.

---

## 🚀 Getting Started

To begin these labs, ensure you are working in a **secure, isolated virtual machine (VM)**.

### 1. Prepare your Environment
Clone the official PCSDF lab files to your forensic workstation:

git clone [(https://github.com/PCSDF/Windows-Forensics-Projects-for-Beginners.git)]
cd Windows-Forensics

----
### 2. Required Toolset
Each project file contains a list of specific tools needed (e.g., **Eric Zimmerman's Tools**, **Autopsy**, or **FTK Imager**). Ensure these are pre-installed in your lab environment.

---

## 🏛️ About PCSDF
The **Pakistan Cyber Security Defense Foundation** provides structured pathways for learners to master the technical skills required to defend national digital infrastructure. 

**Our Goal:** To standardize digital forensic training and incident response capabilities within the region.

---

## ⚖️ Ethical & Legal Disclaimer
* This repository is for **Educational and Authorized Professional use only**.
* Digital Forensics should only be performed on systems where you have explicit legal authority.
* **PCSDF** is not responsible for any misuse of the techniques described herein.

---
**Maintained by:** PCSDF Forensics & IR Team  
**Motto:** *Defending Digital Borders.*
