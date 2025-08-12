# 🔐 Cybersecurity Task 1 – Network Port Scanning

## 🎯 Objective:
To learn how to discover open ports on devices within a local network using **Nmap**, understand network exposure, and gain basic reconnaissance skills.

---

## 🛠 Tools Used:
- **Kali Linux** running on **VirtualBox**
- **Nmap v7.95**
- Terminal and `ip` command for IP range discovery

---

## 📡 Local Network Details:
- **IP Range Scanned**: `10.0.2.0/24`
- **Scanning Method**: TCP SYN Scan (`nmap -sS`)
- **Output File**: `scan-result.txt`

---

## 📋 Command Executed:

nmap -sS 10.0.2.0/24 -oN scan-result.txt

---

## ✅ Conclusion:
The task successfully demonstrated the ability to identify and analyze a phishing email.By examining sender details, suspicious links, and content inconsistencies, the phishing attempt was confirmed.This exercise improved skills in detecting fraudulent emails, reinforcing the importance of vigilance in email security.
