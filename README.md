# ids-vs-honeypot
# 🛡️ Comparative Analysis of Intrusion Detection and Honeypot Systems

**Author**: Zoltán Török  
**University**: Óbuda University, Neumann Faculty of Informatics  
**Year**: 2025  
**Thesis Grade**: Excellent (5)

---

## 📘 Project Overview

This GitHub repository presents the practical implementation and evaluation of Intrusion Detection Systems (IDS) and honeypot technologies, based on my cybersecurity engineering thesis titled:

> *“Comparative analysis of intrusion detection and honeypot systems”*

The goal was to compare traditional defense tools with proactive threat monitoring methods by deploying real systems in a lab environment.

---

## 🎯 Objectives

- Introduce and categorize IDS and honeypot systems
- Analyze their effectiveness, resource usage, and detection capability
- Implement selected tools in virtual environments
- Compare behavior across protocols (SSH, Telnet, FTP)
- Identify future development opportunities (e.g., AI, hybrid systems)

---

## ⚙️ Tools and Technologies

| Tool        | Type     | Protocols Tested | Notes                                 |
|-------------|----------|------------------|----------------------------------------|
| Suricata    | IDS (NIDS) | SSH              | Fast, multi-threaded, advanced decoding |
| Snort       | IDS (NIDS) | FTP              | Widely used, flexible rule system      |
| Cowrie      | Honeypot | SSH, Telnet       | Medium/high-interaction Python-based   |
| Valhala     | Honeypot | Telnet, FTP       | Lightweight, FTP-targeted emulation    |

---

## 🧪 Implementation Examples

- **Cowrie honeypot:** Brute-force detection with realistic Linux shell
- **Valhala honeypot:** Captured credential attempts on fake FTP service
- **Suricata:** Custom SSH detection rules and alert logging
- **Snort:** Rule-based FTP traffic inspection

Logs, configs and screenshots are included in the `/implementation` folder.

---

## 📊 Key Insights

- Honeypots offer **rich attacker profiling** with minimal false positives
- IDS tools are better at **wide-scale detection**, but prone to false alerts
- Combining both systems can create a **multi-layered defense strategy**
- Emerging trends include **machine learning** and **honeynet architectures**

---

## 🛠️ Future Improvements

- Deploy machine learning models to analyze honeypot logs
- Use real-time log visualization (e.g., ELK stack)
- Expand tests to include IoT and cloud environments
- Automate attack classification and response

---

## 📁 Repository Contents

```plaintext
📁 /implementation
├── cowrie_ssh_config.txt
├── cowrie_telnet_log.txt
├── valhala_ftp_output.txt
├── suricata_ssh_rules.yaml
📄 Torok_Dolgozat.pdf
📄 README.md
