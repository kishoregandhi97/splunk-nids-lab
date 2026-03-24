# splunk-nids-lab
# 🔐 Network Intrusion Detection & Monitoring System (Splunk SIEM)

## 📌 Overview

This project demonstrates a SIEM-based detection lab using Splunk to monitor and analyze cyber attacks.

## 🖥️ Lab Setup

* Windows Host (Target + Splunk Server)
* Kali Linux (Attacker)
* VirtualBox Environment

## ⚔️ Attack Simulation

* Nmap Scan (Reconnaissance)
* Hydra SMB Brute-force Attack

## 🔍 Detection

* EventCode 4625 → Failed Login Attempts
* EventCode 4688 → Process Creation

## 📊 Splunk Queries

```
index=main EventCode=4625
index=main EventCode=4688
```

## 📈 Results

* Detected brute-force attack successfully
* Correlated attack timeline with logs

## 🛡️ Recommendations

* Enable account lockout policy
* Restrict SMB access
* Create SIEM alerts

## 🧠 Skills Gained

* SIEM Monitoring
* Log Analysis
* Threat Detection
* Incident Investigation


## 🚀 Author

Kishore Gandhi
