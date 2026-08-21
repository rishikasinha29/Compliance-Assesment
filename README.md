# Compliance Assessment

A cybersecurity compliance and system-hardening assessment project focused on evaluating and improving the security posture of Windows, macOS, Linux, email, BYOD, and cloud environments.

## 📌 Overview

This project was developed around a simulated enterprise environment, **Fed F1rst Control Systems**, undergoing a transformation involving Windows environments, MacBooks, cloud technologies, and enhanced cybersecurity controls.

The project focuses on identifying security weaknesses, developing hardening strategies, creating security policies, evaluating compliance against established frameworks, and improving cloud security.

## 🎯 Objectives

* Identify and remediate endpoint security vulnerabilities.
* Develop Windows and macOS hardening strategies.
* Create security policies for corporate email and BYOD environments.
* Assess Windows desktop compliance against NIST SP 800-53 Rev. 5 controls.
* Evaluate Linux VM security against CMMC controls.
* Develop a secure Windows web-server build sheet for cloud environments.
* Analyze the security benefits of Cloud Access Security Brokers (CASBs).

## 🛡️ Project Sections

### 1. Windows 10/11 Hardening

The Windows hardening assessment identified six major security issues:

* Outdated system updates
* Weak or default passwords
* Disabled firewall
* Lack of endpoint protection
* Unrestricted user account privileges
* AutoRun/AutoPlay enabled

Remediation strategies included enabling automatic updates, enforcing strong password policies, enabling Windows Defender Firewall and Antivirus, configuring UAC, and disabling AutoRun/AutoPlay.

### 2. macOS Hardening

Six security configurations were identified for corporate MacBooks:

* FileVault disk encryption
* macOS Firewall
* Strong passwords and automatic locking
* Disabled automatic login and guest accounts
* Gatekeeper and XProtect
* Full Disk Access for security applications

### 3. Email Security Policy

The proposed corporate email policy covers:

* Multi-Factor Authentication (MFA)
* Prohibition of external email forwarding
* Encryption of confidential information
* Phishing awareness and reporting
* Attachment and link restrictions

### 4. BYOD Security Policy

The BYOD security section addresses:

* Device registration
* Mandatory device encryption
* Remote wipe capability
* Company-approved security software
* Restricted access to corporate data
* Incident reporting requirements

The policy covers Apple and Android smartphones as well as Windows 11 and macOS laptops.

### 5. Windows Desktop Compliance

A Windows 10 desktop was evaluated against selected **NIST SP 800-53 Rev. 5** controls.

The assessment covered areas including:

* Administrator account configuration
* Windows Firewall
* Automatic updates
* UAC
* Password policies
* Guest account
* System logging and auditing
* Windows Defender Antivirus
* Remote Desktop Services
* USB restrictions
* Network access controls
* Remote Registry

Controls were classified as **Met**, **Not Met**, or **Not Applicable**.

Identified gaps included weak password policies, insecure Remote Desktop configuration, unrestricted USB access, and insufficient network access controls.

### 6. Linux Compliance

A Linux VM was evaluated against a set of **CMMC controls**.

The assessment included:

* Security updates
* `/var` partitioning
* Automount configuration
* AIDE installation
* Unnecessary network services
* CUPS
* DHCP
* FTP
* Samba
* TCP Wrappers
* DCCP
* iptables
* Audit log storage
* Audit log retention

The documented assessment marked the listed controls as **Met**.

### 7. Cloud Security

A secure Windows web-server build sheet was developed covering:

1. Operating system and version
2. Security patching and updates
3. Web-server software and configuration
4. Firewall and network security
5. Identity and access management
6. Secure remote access
7. SSL/TLS certificates
8. Logging and monitoring
9. Backup and disaster recovery
10. Hardening and compliance checks

### 8. Cloud Access Security Broker (CASB)

Five key CASB benefits were analyzed:

* Cloud usage visibility
* Data Loss Prevention (DLP)
* Threat detection and incident response
* Access control and identity management
* Compliance monitoring and reporting

## 🔐 Security Concepts Covered

* Endpoint Hardening
* Access Control
* Least Privilege
* Multi-Factor Authentication
* Encryption
* Security Policies
* NIST SP 800-53
* CMMC
* Cloud Security
* CASB
* DLP
* Security Auditing
* Logging and Monitoring
* Backup and Disaster Recovery

## 📂 Project Structure

```text
Compliance-Assessment/
│
├── README.md
├── Windows-Hardening/
├── macOS-Hardening/
├── Email-Policy/
├── BYOD-Policy/
├── Windows-NIST-Compliance/
├── Linux-CMMC-Compliance/
├── Cloud-Server-Build-Sheet/
├── CASB-Analysis/
└── screenshots/
```

## 📚 Frameworks & Technologies

* Windows 10/11
* macOS
* Linux
* NIST SP 800-53 Rev. 5
* CMMC
* Microsoft security controls
* Cloud security concepts
* CASB
* DLP

## 📄 Documentation

The complete project documentation and assessment evidence are available in the accompanying project presentation.

## 👩‍💻 Author

**Rishika Sinha**

Cybersecurity Project — Compliance Assessment
