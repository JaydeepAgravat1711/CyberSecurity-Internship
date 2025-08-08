# Firewall Configuration Summary

## Rule Implemented
- **Name:** Block Telnet
- **Type:** Inbound Rule
- **Protocol:** TCP
- **Port:** 23
- **Action:** Block the connection
- **Profiles:** Domain, Private, Public

## Testing
- Enabled Telnet Client.
- Attempted to connect to `127.0.0.1` on port 23 using Telnet.
- Connection failed, confirming the firewall block was successful.

## Optional Configuration
- Created an allow rule for TCP port 22 (SSH) to permit remote secure connections.

## Outcome
The firewall successfully blocked unwanted Telnet traffic while allowing other services to function normally.
