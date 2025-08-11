# Wireshark Packet Capture Summary

## Overview
This analysis was conducted using Wireshark on Ubuntu to monitor network traffic and analyze captured packets. The capture session recorded traffic on the `enp0s3` interface, including HTTP, DNS, TCP, and TLS protocols.

## Key Observations
1. **DNS Traffic**
   - Multiple DNS queries and responses were captured.
   - Example:
     - Query for domain: `location.services.mozilla.com`
     - Response included IPv4 address resolution.
   
2. **HTTP Traffic**
   - HTTP requests and responses were observed.
   - Packet details included `GET` requests and server responses.

3. **TCP & TLS**
   - Several TCP handshake and TLSv1.2 encrypted sessions detected.
   - Indicated secure communication over HTTPS.

4. **Packet Data Analysis**
   - Examined frame details including MAC addresses, IP addresses, port numbers, and payload data in both hexadecimal and ASCII representations.

## Learning Outcomes
- Identified different layers of the OSI model in packet captures.
- Learned to apply filters for targeted traffic inspection.
- Practiced extracting detailed protocol information from captured packets.
- Understood the use of `.pcapng` files for storing and sharing captures.

## Conclusion
The Wireshark analysis session provided hands-on experience with live network monitoring, traffic filtering, and deep packet inspection, which are essential skills in cybersecurity and network analysis.
