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

```bash
nmap -sS 10.0.2.0/24 -oN scan-result.txt
