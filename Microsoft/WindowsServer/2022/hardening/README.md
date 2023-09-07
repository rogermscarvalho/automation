Automated Compute Resources Deployment and Management - Microsoft Windows Server 2022 - Device Hardening
===========================

### Description:

Scripts for server device hardening of Windows Server 2022-based systems.

# Table of Contents

- [CIS Microsoft Windows Server 2022 Benchmark v2.0.0](#cis-microsoft-windows-server-2022-benchmark-v2.0.0)
    - [Overview](#overview)
        - [Consensus Guidance](#consensus-guidance)
    - [Profile Definitions](#profile-definitions)
    - [Recommendations](#recommendations)
        - [1 Account Policies](#1-account-policies)
            - [1.1 Password Policy](#11-password-policy)
        - [2 Local Policies]()
        - [3 Event Log]()
        - [4 Restricted Groups]()
        - [5 System Services]()
        - [6 Registry]()
        - [7 File System]()
        - [8 Wired Network (IEEE 802.3) Policies]()
        - [9 Windows Defender Firewall with Advanced Security]()
        - [10 Network List Manager Policies]()
        - [11 Wireless Network (IEEE 802.11) Policies]()
        - [12 Public Key Policies]()
        - [13 Software Restriction Policies]()
        - [14 Network Access Protection NAP Client Configuration]()
        - [15 Application Control Policies]()
        - [16 IP Security Policies]()
        - [17 Advanced Audit Policy Configuration]()
        - [18 Administrative Templates (Computer)]()
        - [19 Administrative Templates (User)]()

# CIS Microsoft Windows Server 2022 Benchmark v2.0.0

## Overview

All CIS Benchmarks focus on technical configuration settings used to maintain and/or increase the security of the addressed technology, and they should be used in conjunction with other essential cyber hygiene tasks like:
- Monitoring the base operating system for vulnerabilities and quickly updating with the latest security patches
- Monitoring applications and libraries for vulnerabilities and quickly updating with the latest security patches
In the end, the CIS Benchmarks are designed as a key component of a comprehensive cybersecurity program.
This document provides prescriptive guidance for establishing a secure configuration posture for Microsoft Windows.
This secure configuration guide is based on Microsoft Server 2022 and is intended for all versions of the Server 2022 operating system, including older versions.

To obtain the latest version of this secure configuration guide, please visit [https://www.cisecurity.org/cis-benchmarks](https://www.cisecurity.org/cis-benchmarks).

### Consensus Guidance

This CIS Benchmark was created using a consensus review process comprised of a global community of subject matter experts. The process combines real world experience with data-based information to create technology specific guidance to assist users to secure their environments. Consensus participants provide perspective from a diverse set of backgrounds including consulting, software development, audit and compliance, security research, operations, government, and legal.
Each CIS Benchmark undergoes two phases of consensus review. The first phase occurs during initial Benchmark development. During this phase, subject matter experts convene to discuss, create, and test working drafts of the Benchmark. This discussion occurs until consensus has been reached on Benchmark recommendations. The second phase begins after the Benchmark has been published. During this phase, all feedback provided by the Internet community is reviewed by the consensus team for incorporation in the Benchmark. If you are interested in participating in the consensus process, please visit [https://workbench.cisecurity.org](https://workbench.cisecurity.org/).

## Profile Definitions

The following configuration profiles are defined by this Benchmark:
- **Level 1 - Domain Controller**
    
    Items in this profile apply to Domain Controllers and intend to:
    - be practical and prudent;
    - provide a clear security benefit; and
    - not inhibit the utility of the technology beyond acceptable means.

- **Level 1 - Member Server**
    
    Items in this profile apply to Member Servers and intend to:
    - be practical and prudent;
    - provide a clear security benefit; and
    - not inhibit the utility of the technology beyond acceptable means.

    Items in this profile also apply to Member Servers that have the following Roles enabled:
    - AD Certificate Services
    - DHCP Server
    - DNS Server
    - File Server
    - Hyper-V
    - Network Policy and Access Services
    - Print Server
    - Remote Access Services
    - Remote Desktop Services
    - Web Server

- **Level 2 - Domain Controller**
    
    This profile extends the "Level 1 - Domain Controller" profile. Items in this profile exhibit one or more of the following characteristics:
    - are intended for environments or use cases where security is paramount
    - acts as defense in depth measure
    - may negatively inhibit the utility or performance of the technology

- **Level 2 - Member Server**
    
    This profile extends the "Level 1 - Member Server" profile. Items in this profile exhibit one or more of the following characteristics:
    - are intended for environments or use cases where security is paramount
    - acts as defense in depth measure
    - may negatively inhibit the utility or performance of the technology

- **Next Generation Windows Security - Domain Controller**

This profile contains advanced Windows security features that have specific configuration dependencies, and may not be compatible with all systems. It therefore requires special attention to detail and testing before implementation. If your environment supports these features, they are highly recommended as they have tangible security benefits. This profile is intended to be an optional "add-on" to the Level 1 or Level 2 profiles.

- **Next Generation Windows Security - Member Server**

This profile contains advanced Windows security features that have specific configuration dependencies, and may not be compatible with all systems. It therefore requires special attention to detail and testing before implementation. If your environment supports these features, they are highly recommended as they have tangible security benefits. This profile is intended to be an optional "add-on" to the Level 1 or Level 2 profiles.

## Recommendations

### 1 Account Policies

This section contains recommendations for account policies.

#### 1.1 Password Policy

This section contains recommendations for password policy.

### 2 Local Policies



### 3 Event Log



### 4 Restricted Groups



### 5 System Services



### 6 Registry



### 7 File System



### 8 Wired Network (IEEE 802.3) Policies



### 9 Windows Defender Firewall with Advanced Security



### 10 Network List Manager Policies



### 11 Wireless Network (IEEE 802.11) Policies



### 12 Public Key Policies



### 13 Software Restriction Policies



### 14 Network Access Protection NAP Client Configuration



### 15 Application Control Policies



### 16 IP Security Policies



### 17 Advanced Audit Policy Configuration



### 18 Administrative Templates (Computer)



### 19 Administrative Templates (User)


