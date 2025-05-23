# -cybersecurity-incident-dns-icmp

# Cybersecurity Incident Report – DNS and ICMP Analysis

This project contains a real-world exercise in analyzing network traffic using `tcpdump`.  
It identifies a DNS resolution issue caused by UDP port 53 being unreachable.

## 🕵️‍♂️ Scenario
Multiple users failed to access `www.yummyrecipesforme.com`, receiving a "destination port unreachable" error.

## 🔍 Key Findings
- Protocols used: **UDP** (for DNS queries) and **ICMP** (error messages)
- DNS server IP: `203.0.113.2`
- Issue: ICMP messages confirm **UDP port 53 unreachable**

## 📄 Files
- `incident-report.pdf`: Full incident analysis
- `tcpdump-log.txt`: Captured traffic used in the investigation
- `screenshots/`: Visual evidence from the investigation

## ✍️ Author
Gabriel Pereira – QA Engineer focused on transitioning to Cybersecurity
