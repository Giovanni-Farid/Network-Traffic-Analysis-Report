# **Network Traffic Analysis Project**

This repository contains a professional Network Traffic Analysis Report created as part of a cybersecurity internship project. The report details the detection and analysis of several simulated network attacks.

## **Project Overview**

The objective of this project was to perform a hands-on network security exercise. This involved setting up a controlled lab environment with an attacker machine (Kali Linux) and a target machine (Windows). From the attacker machine, I launched a series of common network attacks, while simultaneously capturing the traffic on the target machine using Wireshark.

The captured traffic was then analyzed to identify the unique signatures of each attack, demonstrating the core principles of network forensics and threat detection.

### **Tools and Techniques Used**

* **Packet Capture & Analysis:** Wireshark  
* **Attack Simulation:** Nmap, hping3, Ettercap  
* **Attacks Performed:**  
  * TCP SYN & Comprehensive Port Scans  
  * ICMP & UDP Floods (DoS)  
  * Nmap XMAS & hping3 FIN Scans (Stealth Reconnaissance)

## **Report Contents**

The [PDF report](Network-Traffic-Analysis-Report.pdf) in this repository includes:

* An Executive Summary for a high-level overview.  
* A detailed breakdown of the 6+ simulated attacks that were successfully identified.  
* Technical analysis for each finding, including the Wireshark filters used for detection.  
* Actionable recommendations for mitigating each type of attack.

## **Disclaimer**

This report and the assessment activities were conducted for **educational and portfolio purposes only**. All activities were performed in a controlled lab environment against machines that I own.

## **License**

Copyright (c) 2025 Giovanni Farid Shawki. All Rights Reserved.

See the [LICENSE](LICENSE.md) file for details.
