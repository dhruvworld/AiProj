---
license: gpl-3.0
tags:
- Anomaly Detection
- Machine Learning
- Wireshark
- Network

---

# Network Traffic Dataset for Anomaly Detection

## Overview

This project presents a comprehensive network traffic dataset used for training AI models for anomaly detection in cybersecurity. The dataset was collected using Wireshark and includes both normal network traffic and various types of simulated network attacks. These attacks cover a wide range of common cybersecurity threats, providing an ideal resource for training systems to detect and respond to real-time network anomalies.

## Dataset Description

<img src="https://cdn-uploads.huggingface.co/production/uploads/678f9d410090fe62b768ee9e/JWZihHl-lxx0y0mZbKZQd.png" width="400" />

### Attack Types

To generate a diverse and comprehensive dataset, different types of attacks were simulated on test networks. The attack types are categorized as follows:

1. **Exploit (Open Target Attacks)**  
   - VulnBot
   - CVE-2020
   - SQL Injection
   - Evil Twin Attack

2. **Probe (Network Reconnaissance Attacks)**  
   - MITM Attack
   - Port Scan

3. **Flood**  
   - Slowloris
   - UDP Flood
   - HTTP Flood
   - SYN Flood
   - Amplification
   - ICMP Flood

4. **Malware (Malicious Software Attacks)**  
   - Cerber
   - GlobeImposter
   - Agent Tesla
   - FormBook
   - Redline Stealer
   - Chthonic Trojan
   - Lokibot Trojan
   - Ratinfected Trojan
   - Squirrel Waffle Trojan
   - Delf Banker Trojan

5. **Brute Force (Authorization System Attacks)**  
   - Password Cracking
   - MySQL Brute Force
   - Redis Brute Force
   - SMB Brute Force

6. **Benign (Normal Network Traffic)**  
   - Temporal and Spatial Benign Traffic (No attacks)

## Dataset Features

- Detailed network traffic logs (including timestamps, IP addresses, and port numbers)
- Rich data for multiple attack scenarios (as described above)
- Simulated attack conditions mimicking real-world cybersecurity threats
- Wireshark captures for deep packet inspection

## Applications

This dataset is ideal for:

- Training AI and machine learning models for network security
- Testing and evaluating cybersecurity tools and systems
- Developing real-time intrusion detection and anomaly detection systems
- Enhancing threat analysis and response strategies in network environments