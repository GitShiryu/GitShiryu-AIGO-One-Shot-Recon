# 🛡️ A.I.G.O. One-Shot Recon (V2.1)
> **Proprietary Automated Security Orchestrator** > *Developed by Rômulo - Magen Code Solutions*

---

## 📑 Description
**Advanced automated reconnaissance orchestrator** that integrates Nmap, Nikto, and custom intelligence layers. Features a proprietary Soft-404 validation engine to eliminate false positives in large-scale attack surface mapping.

> ⚠️ **Status:** Private source code - Not Available for public distribution.

---

## ⚡ Core Features

* **Smart Orchestration:** Seamless integration with Nmap (Port Mapping) and Nikto (Vulnerability Scanning) in a single execution flow.
* **Anti-False Positive Engine:** Proprietary hash-comparison algorithm designed to bypass modern "Catch-all" and Soft-404 defensive patterns.
* **Deep Fuzzing:** Intelligent scanning for high-value targets including `.env`, `config.php`, `.git/HEAD`, and `sftp.json`.
* **Verdict Reporting:** Automated generation of "Verdict" files, consolidating raw tool outputs with validated findings for quick decision-making.

---

## 🛠️ Architecture & Workflow



1.  **Input Phase:** Interactive CLI for target definition and sanitization.
2.  **Discovery Phase:** Rapid port discovery and service fingerprinting.
3.  **Audit Phase:** Web server misconfiguration and vulnerability assessment.
4.  **Intelligence Phase:** Post-scan validation of sensitive file accessibility using MD5 hash integrity checks.
5.  **Output Phase:** Generation of a clean, structured report (VEREDITO_TARGET.txt).

---

## 🚀 Usage

```bash
# Execute the orchestrator
python3 aigo_master.py

<img width="1344" height="768" alt="One_Shot_Recon" src="https://github.com/user-attachments/assets/dac57758-6857-4089-b2e9-94725f2e04b0" />
