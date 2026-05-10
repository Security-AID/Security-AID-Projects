# Security-AID-Projects
All of my group and personal projects listed.

# Chuma Ejekute-Obi | Cybersecurity & Computer Science Portfolio

Welcome to my professional project portfolio. This repository highlights the academic, cybersecurity, software development, networking, cloud security, and research-based projects I completed throughout school and personal technical development.

I recently graduated with a degree in Cybersecurity, and my work focuses on practical security analysis, defensive security, secure coding, cloud compliance, malware scanning, system hardening, networking, scripting, and software development.

---

## About Me

I am a cybersecurity graduate with hands-on experience in security labs, vulnerability research, secure system configuration, network analysis, Linux environments, scripting, and software development. My academic and personal projects helped me build a strong foundation in cybersecurity operations, system administration, secure coding, cloud security, and practical attack/defense concepts.

My main interests include:

- Security Operations Center analysis
- Network security
- Vulnerability assessment
- Cloud security and compliance
- Malware detection and file scanning
- Secure software development
- Digital forensics and packet analysis
- Red team and blue team lab environments
- Automation using Python, PowerShell, C++, and Bash

---

# Project Categories

## Cybersecurity Projects

### 1. VirusTotal Mini Scanner

**Category:** Cybersecurity / Malware Analysis / DevSecOps  
**Tools Used:** C++, libcurl, OpenSSL, VirusTotal API, Linux

This project is a lightweight malware scanning tool built in C++ that calculates the SHA-256 hash of a file and checks the file reputation using the VirusTotal API.

**Main Features:**

- Computes file SHA-256 hashes
- Sends hash queries to VirusTotal
- Supports file upload or report lookup workflow
- Parses scan results from VirusTotal
- Classifies results as malicious, suspicious, harmless, or undetected
- Generates security logs and JSON reports
- Supports defensive decision-making such as ALLOW, REVIEW, or BLOCK

**Cybersecurity Skills Demonstrated:**

- Malware analysis fundamentals
- API-based threat intelligence
- Secure file hashing
- C++ security tooling
- DevSecOps security automation
- Logging and reporting for security workflows

---

### 2. CEPR8 Compliance Monitor using OpenSCAP

**Category:** Cloud Security / Compliance / DevSecOps  
**Tools Used:** OpenSCAP, Linux, Bash, Security Compliance Profiles

This project focused on building a compliance monitoring tool using OpenSCAP to scan systems against security baselines and generate compliance reports.

**Main Features:**

- Runs OpenSCAP security scans
- Checks system compliance against selected benchmarks
- Generates compliance scan reports
- Supports security auditing workflows
- Helps identify misconfigurations and weak system settings

**Cybersecurity Skills Demonstrated:**

- Compliance monitoring
- Cloud security controls
- Security auditing
- Linux hardening
- DevSecOps automation
- Risk and control validation

---

### 3. LLMNR / NetBIOS Attack and Defense Automation Tool

**Category:** Network Security / Windows Security / PowerShell Automation  
**Tools Used:** Kali Linux, Windows Server, PowerShell, Responder, Wireshark

This project demonstrated how LLMNR and NetBIOS name resolution can be abused in a local network attack scenario. I also created a PowerShell-based defense tool to enable or disable security settings.

**Main Features:**

- Demonstrated LLMNR poisoning concepts in a controlled lab
- Used Kali Linux and Responder for attack simulation
- Used Windows as the victim machine
- Built PowerShell functions to enable and disable protections
- Included menu-based options for easier user interaction
- Controlled Windows firewall and NetBIOS settings

**Cybersecurity Skills Demonstrated:**

- Windows network security
- LLMNR and NetBIOS misconfiguration awareness
- PowerShell automation
- Defensive security hardening
- Attack simulation in a lab environment
- Wireshark packet analysis

---

### 4. RDP Security Lab

**Category:** Network Security / Windows Security / Remote Access  
**Tools Used:** FreeRDP, Windows Server, Kali Linux, Wireshark

This project focused on Remote Desktop Protocol access, authentication behavior, and network traffic observation in a lab environment.

**Main Features:**

- Configured RDP access between systems
- Tested login behavior and authentication issues
- Used FreeRDP commands from Linux
- Analyzed RDP traffic flow
- Practiced troubleshooting remote access failures

**Cybersecurity Skills Demonstrated:**

- Remote access security
- Windows account configuration
- Authentication troubleshooting
- Network protocol analysis
- Lab-based attack and defense practice

---

### 5. Cryptography Replay Attack Lab

**Category:** Cryptography / Secure Communication / Network Security  
**Tools Used:** Python, Flask, AES-GCM, AES-CTR, HMAC, Wireshark

This project explored secure communication between a client and server using encryption and message authentication. I tested how replay attacks can still work if freshness checks are not used.

**Main Features:**

- Built a client-server communication lab
- Used AES-GCM encryption
- Used AES-CTR and HMAC concepts
- Captured encrypted responses as binary files
- Replayed saved server responses
- Added timestamp freshness checks to block replay attacks
- Verified encrypted packet behavior in Wireshark

**Cybersecurity Skills Demonstrated:**

- Symmetric encryption
- Authentication tags
- Replay attack understanding
- Secure API design
- Freshness validation
- Wireshark packet inspection
- Python security scripting

---

### 6. CSRF Security Lab

**Category:** Web Security / Secure Coding  
**Tools Used:** Python, Flask, Flask-WTF, HTML

This project demonstrated Cross-Site Request Forgery and how CSRF protection prevents unauthorized form submissions.

**Main Features:**

- Built a vulnerable web form
- Created a fake attacker page
- Demonstrated CSRF attack behavior
- Implemented CSRF protection using Flask-WTF
- Compared protected and unprotected requests

**Cybersecurity Skills Demonstrated:**

- Web application security
- CSRF attack prevention
- Secure form handling
- Flask security features
- Secure coding practices

---

### 7. JWT Exploitation Practice Lab

**Category:** Web Security / Authentication Security  
**Tools Used:** JSON Web Tokens, Web Application Testing Tools, Browser Developer Tools

This project focused on understanding how JWT authentication works and how weak JWT implementations can become vulnerable.

**Main Features:**

- Studied JWT structure
- Practiced analyzing token headers and payloads
- Learned common JWT security mistakes
- Explored authentication bypass concepts in a lab setting

**Cybersecurity Skills Demonstrated:**

- Authentication security
- Token-based access control
- Web security testing
- Secure session design
- API security fundamentals

---

### 8. XSS Web Security Lab

**Category:** Web Security / Application Security  
**Tools Used:** HTML, JavaScript, Browser Developer Tools, Vulnerable Web Apps

This project focused on learning Cross-Site Scripting from the ground up using lab-based examples.

**Main Features:**

- Practiced reflected and stored XSS concepts
- Studied how unsafe input handling causes vulnerabilities
- Tested JavaScript payload behavior in safe lab environments
- Learned how output encoding and validation reduce XSS risk

**Cybersecurity Skills Demonstrated:**

- Web application security
- JavaScript behavior analysis
- Input validation
- Output encoding
- Secure coding awareness

---

### 9. DVWA / Vulnerable Web Application Lab

**Category:** Web Security / Ethical Hacking Lab  
**Tools Used:** Kali Linux, DVWA, Apache, MySQL, PHP

This project involved setting up a vulnerable web application lab to practice common web security vulnerabilities in a legal and controlled environment.

**Main Features:**

- Installed and configured DVWA
- Practiced web vulnerability testing
- Studied SQL injection, XSS, CSRF, and authentication issues
- Used Kali Linux as the attacker/testing environment

**Cybersecurity Skills Demonstrated:**

- Ethical hacking fundamentals
- Web vulnerability testing
- Kali Linux lab setup
- Secure coding awareness
- Vulnerability documentation

---

### 10. Network Detection Script

**Category:** Networking / Cybersecurity Automation  
**Tools Used:** Python, Linux, Local Network Scanning

This project involved creating a script that scans devices on the same Wi-Fi/local network to identify active hosts.

**Main Features:**

- Detects devices on a local network
- Scans IP address ranges
- Helps identify active systems
- Supports basic network visibility

**Cybersecurity Skills Demonstrated:**

- Network discovery
- Python scripting
- IP addressing
- Local network analysis
- Blue team visibility concepts

---

### 11. Wireshark Packet Analysis Labs

**Category:** Network Security / Digital Forensics  
**Tools Used:** Wireshark, Linux, Windows, TCP/IP, DNS, HTTP, RDP

These labs focused on capturing and analyzing network packets to better understand communication between systems.

**Main Features:**

- Captured live packets
- Analyzed DNS traffic
- Reviewed TCP/IP behavior
- Inspected request and response packets
- Studied suspicious or unusual network communication
- Used packet details to explain what was happening on the network

**Cybersecurity Skills Demonstrated:**

- Packet analysis
- Network troubleshooting
- Protocol analysis
- Digital forensics basics
- Security investigation skills

---

### 12. Pixhawk Flight Control System Vulnerability Research

**Category:** Embedded Security / Reverse Engineering / Drone Security  
**Tools Used:** ArduPilot Copter Firmware, Pixhawk, Mission Planner, IDA Pro

This project focused on researching potential security concerns in Pixhawk flight control systems and analyzing firmware behavior.

**Main Features:**

- Studied ArduPilot Copter firmware
- Explored Pixhawk flight control system behavior
- Reviewed firmware code structure
- Used reverse engineering concepts
- Investigated possible attack surfaces in drone systems

**Cybersecurity Skills Demonstrated:**

- Embedded systems security
- Firmware analysis
- Reverse engineering fundamentals
- Drone security research
- Secure system analysis

---

# Computer Science Projects

## 13. Custom Linux Shell Project

**Category:** Computer Science / Operating Systems / C Programming  
**Tools Used:** C, Linux, GCC, Unix System Calls

This project involved building parts of a custom shell in C, including directory navigation and input/output redirection.

**Main Features:**

- Implemented a built-in `cd` command
- Added input and output redirection
- Used Linux system calls
- Managed process execution
- Practiced shell behavior and command parsing

**Computer Science Skills Demonstrated:**

- C programming
- Operating systems concepts
- Linux process management
- File descriptors
- Input/output redirection
- Shell implementation

---

## 14. Pipes and Redirection Assignment

**Category:** Computer Science / Operating Systems / C Programming  
**Tools Used:** C, Linux, `pipe()`, `dup2()`, `close()`

This project focused on interprocess communication using pipes and redirection in C.

**Main Features:**

- Created programs using Unix pipes
- Used `dup2()` to redirect file descriptors
- Used `close()` to manage resources
- Connected processes together through pipe communication

**Computer Science Skills Demonstrated:**

- Interprocess communication
- Unix system programming
- Process control
- File descriptor management
- C programming fundamentals

---

## 15. Docker System Monitoring Lab

**Category:** Computer Science / Cloud / System Administration  
**Tools Used:** Docker, Linux, Command Line

This lab focused on observing running containers and system resource usage.

**Main Features:**

- Ran Docker containers
- Used `docker ps` to view active containers
- Used `docker stats` to monitor live CPU, memory, and network usage
- Practiced troubleshooting permission issues with Docker commands

**Computer Science Skills Demonstrated:**

- Container basics
- Linux command line
- Resource monitoring
- System administration
- Cloud computing fundamentals

---

## 16. Python Quiz Game / Coding Logic Practice

**Category:** Computer Science / Python Programming  
**Tools Used:** Python

This project focused on strengthening Python programming logic through a quiz-style application.

**Main Features:**

- Used loops and conditional statements
- Practiced `enumerate()` in for loops
- Worked with lists and question/answer structures
- Improved understanding of program flow

**Computer Science Skills Demonstrated:**

- Python fundamentals
- Loop logic
- Conditional statements
- Data structures
- Beginner software design

---

# Software Development Projects

## 17. LVLCRAFT iOS Game App

**Category:** Software Development / iOS Development / Game Design  
**Tools Used:** SwiftUI, Xcode, AVFoundation, StoreKit, UserDefaults, Firebase concepts

LVLCRAFT is a retro RPG-style habit tracking and self-improvement iOS game. The app turns real-life activities into game progression, stats, EXP, trophies, skins, and missions.

**Main Features:**

- Retro pixel-style user interface
- Character creation system
- Activity completion system
- EXP and leveling system
- Stat tracking system
- Daily objectives
- Nutrition room
- Trophy room
- Treasure room
- Skin unlock system
- StoreKit in-app purchase concepts
- Background music and animated video backgrounds
- Responsive SwiftUI layouts for different iPhone screen sizes

**Software Development Skills Demonstrated:**

- SwiftUI app development
- Mobile UI design
- Game logic
- Local data persistence
- StoreKit integration concepts
- Responsive design
- App architecture
- User experience design

---

## 18. Luxury E-Commerce Website

**Category:** Web Development / E-Commerce  
**Tools Used:** HTML, CSS, JavaScript, Stripe, Vercel Concepts

This project focused on building a luxury-style e-commerce website with payment navigation and styled product pages.

**Main Features:**

- Multi-page website structure
- Product/card pages
- About and contact pages
- Stripe payment page integration
- Thank-you pages after purchase
- Mobile hamburger menu
- Styled animations and consistent branding

**Software Development Skills Demonstrated:**

- Front-end development
- Website layout design
- Payment integration concepts
- Mobile responsive navigation
- User experience design

---

## 19. CHIMOAI AI Video Generation Concept

**Category:** AI / Automation / Product Development  
**Tools Used:** n8n, AI APIs, No-Code Automation Concepts

CHIMOAI is an AI video generation platform concept designed to help users generate videos from prompts using automated workflows.

**Main Features:**

- Prompt-based video generation concept
- AI asset generation workflow
- Potential YouTube or Google Drive output options
- No-code automation using n8n
- Explored integration with AI models and video tools

**Software Development Skills Demonstrated:**

- AI workflow planning
- Product design
- Automation logic
- No-code development
- API integration planning

---

# Security and Technical Skills

## Cybersecurity Skills

- Network security
- Web application security
- Malware scanning
- Threat intelligence
- Vulnerability assessment
- Compliance monitoring
- Secure coding
- Packet analysis
- Windows security hardening
- Linux security
- Cryptography fundamentals
- Authentication security
- SOC analyst fundamentals

## Programming and Scripting

- Python
- C
- C++
- PowerShell
- Bash
- JavaScript
- HTML
- CSS
- Swift / SwiftUI

## Tools and Platforms

- Kali Linux
- Ubuntu
- Windows Server
- Wireshark
- Docker
- OpenSCAP
- VirusTotal API
- Responder
- FreeRDP
- Flask
- DVWA
- Xcode
- GitLab
- VS Code
- IDA Pro concepts
- Mission Planner
- OpenSSL

---

# Academic Focus Areas

My school projects covered several major areas of cybersecurity and computer science, including:

- Operating systems
- Computer networks
- Secure electronic commerce
- Cryptography
- Web application security
- Cloud security
- Compliance and auditing
- Malware analysis
- DevSecOps
- Digital forensics
- Reverse engineering
- System administration
- Software development

---

# Professional Summary

This portfolio represents my growth as a cybersecurity graduate and technical problem solver. Through academic labs, security research, programming assignments, and personal projects, I developed hands-on experience with both offensive and defensive cybersecurity concepts.

My strongest areas include network security, secure system configuration, vulnerability analysis, malware scanning, web security, Linux environments, PowerShell automation, and practical security documentation.

I am continuing to grow toward roles such as:

- Junior Security Analyst
- SOC Analyst
- Cybersecurity Analyst
- Information Security Analyst
- Vulnerability Management Analyst
- Cloud Security Analyst
- GRC / Compliance Analyst
- Security Operations Intern or New Graduate Analyst
- Entry-Level DevSecOps Analyst

---

# Contact

**Name:** Chuma Ejekute-Obi  
**Email:** chumaejekuteobi@gmail.com  
**Portfolio:** GitLab Project Portfolio  
**Focus:** Cybersecurity, Security Operations, Secure Software Development, and Cloud Security
