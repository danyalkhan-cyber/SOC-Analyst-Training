# Day 01 – Network Fundamentals

## Objective
Understand basic networking concepts and perform practical network troubleshooting using Windows Command Prompt.

## Lab Environment
- Operating System: Windows 11
- Platform: VirtualBox
- Network: Wi-Fi and VirtualBox Host-Only Adapter

## Topics Covered
- IPv4 Address
- MAC Address
- Subnet Mask
- Default Gateway
- DNS
- DHCP
- Network Connectivity
- Traceroute

## Practical Tasks

### 1. Network Configuration
Command:
`ipconfig /all`

Identified network interfaces, IPv4 configuration, subnet mask, default gateway, DNS server and MAC address.

### 2. Connectivity Testing
Command:
`ping 8.8.8.8`

Result:
- Packets Sent: 4
- Packets Received: 4
- Packet Loss: 0%
- Average Response Time: 72 ms

### 3. DNS Resolution
Command:
`nslookup google.com`

Result:
Successfully resolved the domain name into IPv4 and IPv6 addresses.

### 4. Traceroute Analysis
Command:
`tracert 8.8.8.8`

Result:
The route completed successfully through 11 hops.

Observed intermediate network addresses, response times and one non-responsive probe.

## Tools Used
- Windows Command Prompt
- ipconfig
- ping
- nslookup
- tracert

## Key Learnings
- Identified network configuration details.
- Understood private IPv4 addressing.
- Tested connectivity with ICMP.
- Learned DNS resolution.
- Analyzed network paths using traceroute.

## Evidence
Screenshots are available in the Screenshots directory.

## Conclusion
Completed basic network configuration analysis and connectivity troubleshooting as part of my SOC Analyst learning journey.

**Status:** Completed

