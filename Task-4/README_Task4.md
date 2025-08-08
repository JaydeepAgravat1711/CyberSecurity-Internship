# Task 4 – Firewall Traffic Filtering (Windows 11)

## 🎯 Objective
To configure Windows Firewall to block Telnet traffic (TCP port 23), test the block, and verify that the firewall is effectively filtering network traffic.

## 🛠 Tools Used
- Windows 11 Pro
- Windows Defender Firewall with Advanced Security
- Telnet Client (enabled via Windows Features)

## 📋 Steps Performed
1. Checked existing inbound rules in Windows Defender Firewall.
2. Created a new inbound rule to block TCP port 23 (Telnet).
3. Enabled Telnet Client from Windows Features.
4. Tested the rule using Command Prompt (`telnet 127.0.0.1 23`) and confirmed the block.
5. (Optional) Created an allow rule for SSH (TCP port 22).
6. Removed the Telnet block rule and confirmed normal traffic flow.

## 📂 Output Files
- `screenshots/` – firewall configuration and test result screenshots.
- `firewall_summary.md` – summary of the configuration and results.

## ✅ Conclusion
Successfully demonstrated blocking Telnet traffic on Windows 11 using the built-in firewall, verified the block via Telnet test, and documented the process with screenshots.
