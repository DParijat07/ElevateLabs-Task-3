# Networking Basics for Cyber Security – Wireshark Analysis

## Project Overview
This project focuses on understanding core networking concepts and performing basic network traffic analysis using Wireshark. The objective is to gain hands-on experience in packet capturing, protocol analysis, and identifying secure versus insecure network communication, which are essential skills for SOC and Blue Team roles.

---

## Objective
- Understand fundamental networking concepts used in cybersecurity
- Capture and analyze live network traffic
- Identify TCP, UDP, DNS, HTTP, and HTTPS traffic
- Observe the TCP three-way handshake
- Differentiate between plain-text and encrypted communication

---

## Tools & Technologies
- **Primary Tool:** Wireshark  
- **Protocols Analyzed:** TCP, UDP, DNS, HTTP, HTTPS  
- **Environment:** Live network traffic capture

---

## Key Networking Concepts
- **IP Address:** Logical identifier of a device on a network  
- **MAC Address:** Physical address of a network interface  
- **TCP:** Connection-oriented and reliable protocol  
- **UDP:** Connectionless and faster protocol  
- **DNS:** Resolves domain names to IP addresses  

---

## Methodology
1. Installed and configured Wireshark
2. Captured live network traffic using an active interface
3. Applied protocol-based filters:
   - `tcp`
   - `dns`
   - `http`
   - `tls`
4. Observed TCP three-way handshake (SYN, SYN-ACK, ACK)
5. Analyzed DNS queries and responses
6. Compared plain-text HTTP traffic with encrypted HTTPS traffic
7. Saved packet captures for offline analysis

---

## Analysis & Observations
- TCP uses a three-way handshake to establish reliable communication
- DNS traffic primarily uses UDP port 53
- HTTP traffic transmits data in plain text and is insecure
- HTTPS encrypts data using TLS, preventing packet inspection
- Packet sniffing helps detect insecure communication and potential threats

---

## Files Included
- `task3_network_capture.pcapng` – Packet capture file
- `Network_Traffic_Analysis_Report.pdf` - Analysis report
- `README.md` – Project documentation  

---

## Security Insights
- Unencrypted traffic can expose sensitive information
- Packet sniffing is commonly used by attackers and defenders
- HTTPS significantly improves data confidentiality and integrity
- Network traffic analysis is a core SOC analyst responsibility

---

## Learning Outcome
- Practical exposure to network packet analysis
- Improved understanding of secure vs insecure protocols
- Hands-on experience with Wireshark filtering techniques
- Foundational skills for SOC and Blue Team operations

---

## Interview Relevance
This project demonstrates:
- Networking fundamentals
- Packet analysis skills
- Understanding of encryption and secure communication
- SOC-aligned practical experience

---

## Author
**Parijat Das**  
Aspiring Cyber Security Professional | B.Tech CSE
