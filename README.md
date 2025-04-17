# Lab 4: Network Sniffing with Wireshark  
**Student Name:** William Adams  
**Course:** IS 3513-002  
**Professor:** Wooldridge  
**Date:** November 28, 2023  

## Overview  
This lab focused on network sniffing using the powerful tool Wireshark. The goal was to gain practical experience in capturing and analyzing network traffic and to understand how different protocols behave during real-time network communication.

## Tools Used  
- **Wireshark**: A network protocol analyzer used to capture and interactively browse traffic running on a computer network.

## Objectives  
- Capture and analyze packets using Wireshark  
- Understand how different protocols behave, including:  
  - ARP  
  - TCP  
  - UDP  
  - HTTP  
  - HTTPS (TLS)  
  - FTP  
  - ICMP  
  - DNS  
- Learn how packet data reveals authentication and communication details  
- Observe real-world traffic and identify potential security implications  

## Steps Performed  
1. Launched Wireshark and captured packets on a wireless connection  
2. Visited specific websites and authenticated into remote services to observe packet behavior  
3. Filtered and analyzed different protocols  
4. Captured long-running network traffic for over an hour to observe live devices and communications  
5. Reflected on implications of HTTP vs HTTPS traffic and the visibility of sensitive data  

## Key Learnings  
- Wireshark captures detailed protocol-level traffic, which can be used to troubleshoot or investigate security events  
- Protocols like HTTP transmit in plaintext and can expose data if not encrypted  
- Using filters makes analysis significantly easier  
- Even passive monitoring reveals a lot about network activity  

## Challenges  
- Encountered difficulties capturing FTP traffic, possibly due to differences in operating system (macOS vs Windows)  
- Misread instructions at one step, causing minor confusion before correction  

## Reflection  
This lab was highly educational and reinforced the importance of encryption, proper network monitoring, and traffic analysis in cybersecurity. Wireshark is a crucial tool for security professionals, and this lab improved my familiarity and confidence with it.  

## References  
- Porup, J.M. (2018). *How to use Wireshark, the best packet analyzer around*. CSO Online.  
- OT (2021). *How cybersecurity professionals use Wireshark*. 
