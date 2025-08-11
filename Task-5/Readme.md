# Task 5 - Wireshark Packet Capture and Analysis

## Objective
The objective of this task is to use Wireshark to capture and analyze network packets, identify protocols in use, and inspect packet-level data for better understanding of network communication.

## Tools Used
- **Wireshark** (v3.2.3) on Ubuntu
- Network Interface: `enp0s3`

## Steps Performed
1. Launched Wireshark and selected the active network interface (`enp0s3`).
2. Started capturing packets in real-time.
3. Applied display filters for specific protocols (e.g., HTTP, DNS, TCP).
4. Inspected packet details at different layers:
   - **Ethernet II** (MAC addresses)
   - **IP (IPv4/IPv6)** (Source & Destination IPs)
   - **TCP/UDP** (Ports and Flags)
   - **Application Layer** (HTTP requests, DNS queries/responses)
5. Saved the captured packets to a `.pcapng` file for submission.
6. Took relevant screenshots during the capture and analysis process.

## Files in This Folder
- `capture.pcapng` → Packet capture file
- `Screenshot ` → perform task screenshots
- `wireshark_summary.md` → Summary report of findings
- `Readme.md` → Describing the performed task


## Outcome
Successfully captured and analyzed live network traffic, gaining practical skills in packet inspection, protocol analysis, and identifying network communication patterns.
