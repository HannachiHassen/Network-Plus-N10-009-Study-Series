# 🔌 Port Number Cheat Sheet
### *Network+ N10-009 Study Series — Resources*

![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B%20N10--009-FF0000?style=for-the-badge&logo=comptia&logoColor=white)
![Category](https://img.shields.io/badge/Category-Port%20Reference-6F42C1?style=for-the-badge)

> 📌 A complete reference of port numbers organized by category and range.  
> Ports are heavily tested on the N10-009 — know the well-known ports (0–1023) cold.

---

## 📑 Table of Contents

1. [Port Range Overview](#-port-range-overview)
2. [Well-Known Ports (0–1023)](#-well-known-ports-0--1023)
   - [File Transfer & Remote Access](#-file-transfer--remote-access)
   - [Email Protocols](#-email-protocols)
   - [Web Protocols](#-web-protocols)
   - [Name & Address Services](#-name--address-services)
   - [Network Management & Monitoring](#-network-management--monitoring)
   - [Directory Services](#-directory-services)
   - [Authentication & Security](#-authentication--security)
3. [Registered Ports (1024–49151)](#-registered-ports-1024--49151)
4. [TCP vs. UDP Protocol Reference](#-tcp-vs-udp-protocol-reference)
5. [Ports by Protocol Type](#-ports-by-protocol-type)
6. [Master Quick-Reference Table](#-master-quick-reference-table)
7. [Exam Tips & Memory Tricks](#-exam-tips--memory-tricks)

---

## 📐 Port Range Overview

| Range | Name | Description |
|-------|------|-------------|
| **0 – 1023** | Well-Known Ports | Assigned by IANA to core internet services. Reserved for system/root processes. |
| **1024 – 49151** | Registered Ports | Assigned by IANA to specific applications upon request. |
| **49152 – 65535** | Dynamic / Ephemeral Ports | Temporarily assigned by the OS to client-side connections. Also called "private" ports. |

> 💡 The exam focuses almost entirely on **Well-Known Ports (0–1023)** and a handful of registered ports.

---

## 🌟 Well-Known Ports (0–1023)

### 📁 File Transfer & Remote Access

| Port | Protocol | Transport | Service | Notes |
|------|----------|-----------|---------|-------|
| **20** | FTP-Data | TCP | File Transfer Protocol — Data | Active mode data transfer |
| **21** | FTP-Control | TCP | File Transfer Protocol — Control | Commands and session control |
| **22** | SSH | TCP | Secure Shell | Encrypted remote CLI, also used by SFTP and SCP |
| **23** | Telnet | TCP | Telnet | Unencrypted remote CLI — **insecure, legacy** |
| **69** | TFTP | UDP | Trivial File Transfer Protocol | No auth, used for PXE boot and firmware uploads |

---

### 📧 Email Protocols

| Port | Protocol | Transport | Service | Notes |
|------|----------|-----------|---------|-------|
| **25** | SMTP | TCP | Simple Mail Transfer Protocol | Server-to-server relay; outbound mail |
| **110** | POP3 | TCP | Post Office Protocol v3 | Downloads email; deletes from server by default |
| **143** | IMAP | TCP | Internet Message Access Protocol | Syncs email; keeps messages on server |
| **465** | SMTPS | TCP | SMTP over SSL | Legacy secure SMTP — implicit TLS |
| **587** | SMTP Submission | TCP | SMTP with STARTTLS | Modern standard for client email submission |
| **993** | IMAPS | TCP | IMAP over SSL/TLS | Encrypted IMAP |
| **995** | POP3S | TCP | POP3 over SSL/TLS | Encrypted POP3 |

---

### 🌐 Web Protocols

| Port | Protocol | Transport | Service | Notes |
|------|----------|-----------|---------|-------|
| **80** | HTTP | TCP | Hypertext Transfer Protocol | Unencrypted web traffic |
| **443** | HTTPS | TCP | HTTP Secure | Encrypted via TLS; standard for all modern web |
| **8080** | HTTP-Alt | TCP | HTTP Alternate | Common for web proxies and dev servers |
| **8443** | HTTPS-Alt | TCP | HTTPS Alternate | Alternate HTTPS port — common in web apps |

---

### 🗂️ Name & Address Services

| Port | Protocol | Transport | Service | Notes |
|------|----------|-----------|---------|-------|
| **53** | DNS | TCP/UDP | Domain Name System | UDP for queries; TCP for zone transfers & large responses |
| **67** | DHCP Server | UDP | Dynamic Host Config Protocol | Server listens on 67 |
| **68** | DHCP Client | UDP | Dynamic Host Config Protocol | Client listens on 68 |
| **123** | NTP | UDP | Network Time Protocol | Clock synchronization; critical for Kerberos & logging |

---

### 📊 Network Management & Monitoring

| Port | Protocol | Transport | Service | Notes |
|------|----------|-----------|---------|-------|
| **161** | SNMP | UDP | Simple Network Management Protocol | Agent receives queries from manager |
| **162** | SNMP Trap | UDP | SNMP Trap | Agent sends unsolicited alerts to manager |
| **514** | Syslog | UDP | Syslog | System log forwarding to central log server |

---

### 🗃️ Directory Services

| Port | Protocol | Transport | Service | Notes |
|------|----------|-----------|---------|-------|
| **389** | LDAP | TCP/UDP | Lightweight Directory Access Protocol | Unencrypted directory queries (Active Directory) |
| **636** | LDAPS | TCP | LDAP over SSL/TLS | Encrypted LDAP |
| **445** | SMB | TCP | Server Message Block | Windows file/printer sharing; also used by AD |
| **88** | Kerberos | TCP/UDP | Kerberos Authentication | Used in Active Directory for ticket-based auth |

---

### 🔐 Authentication & Security

| Port | Protocol | Transport | Service | Notes |
|------|----------|-----------|---------|-------|
| **88** | Kerberos | TCP/UDP | Kerberos | Ticket-based auth; 5-min clock skew tolerance |
| **500** | IKE | UDP | Internet Key Exchange | IPsec VPN tunnel negotiation |
| **4500** | IPsec NAT-T | UDP | IPsec NAT Traversal | IPsec through NAT devices |

---

## 🔵 Registered Ports (1024–49151)

| Port | Protocol | Transport | Service | Notes |
|------|----------|-----------|---------|-------|
| **1194** | OpenVPN | UDP | OpenVPN | Default OpenVPN port |
| **1433** | MS-SQL | TCP | Microsoft SQL Server | Database queries |
| **1701** | L2TP | UDP | Layer 2 Tunneling Protocol | VPN tunneling — no built-in encryption |
| **1723** | PPTP | TCP | Point-to-Point Tunneling Protocol | Legacy VPN — **considered insecure** |
| **1812** | RADIUS Auth | UDP | RADIUS Authentication | AAA — authentication & authorization |
| **1813** | RADIUS Acct | UDP | RADIUS Accounting | AAA — session accounting |
| **3306** | MySQL | TCP | MySQL Database | Database queries |
| **3389** | RDP | TCP | Remote Desktop Protocol | Windows graphical remote access |
| **5060** | SIP | TCP/UDP | Session Initiation Protocol | VoIP call setup and signaling (unencrypted) |
| **5061** | SIP-TLS | TCP | SIP over TLS | Encrypted VoIP signaling |
| **5900** | VNC | TCP | Virtual Network Computing | Remote desktop (cross-platform) |
| **6514** | Syslog-TLS | TCP | Syslog over TLS | Encrypted log forwarding |
| **8080** | HTTP-Alt | TCP | HTTP Alternate | Proxy servers, web app dev |
| **49** | TACACS+ | TCP | TACACS+ | Cisco device admin AAA — full payload encryption |

---

## ⚖️ TCP vs. UDP Protocol Reference

### TCP — Reliable, Connection-Oriented
> Use TCP when data integrity and ordered delivery matter.

| Port | Service |
|------|---------|
| 20/21 | FTP |
| 22 | SSH / SFTP |
| 23 | Telnet |
| 25 | SMTP |
| 80 | HTTP |
| 110 | POP3 |
| 143 | IMAP |
| 179 | BGP |
| 389 | LDAP |
| 443 | HTTPS |
| 445 | SMB |
| 465 | SMTPS |
| 587 | SMTP Submission |
| 636 | LDAPS |
| 993 | IMAPS |
| 995 | POP3S |
| 1723 | PPTP |
| 3389 | RDP |
| 5900 | VNC |

### UDP — Fast, Connectionless, Best-Effort
> Use UDP when speed matters more than reliability.

| Port | Service |
|------|---------|
| 53 | DNS (queries) |
| 67/68 | DHCP |
| 69 | TFTP |
| 88 | Kerberos |
| 123 | NTP |
| 161/162 | SNMP |
| 500 | IKE (IPsec) |
| 514 | Syslog |
| 1194 | OpenVPN |
| 1701 | L2TP |
| 1812/1813 | RADIUS |
| 4500 | IPsec NAT-T |
| 5060 | SIP |

### Both TCP and UDP
| Port | Service | TCP Use | UDP Use |
|------|---------|---------|---------|
| 53 | DNS | Zone transfers, large responses | Standard queries |
| 88 | Kerberos | Reliable auth flows | Lightweight tickets |
| 123 | NTP | — | Time sync (primarily UDP) |
| 389 | LDAP | Directory queries | Lightweight lookups |

---

## 🗂️ Ports by Protocol Type

### 🔒 Secure vs. Insecure Equivalents

| Insecure | Port | Secure Replacement | Port | Encryption |
|----------|------|--------------------|------|------------|
| Telnet | 23 | SSH | 22 | TLS/AES |
| FTP | 20/21 | SFTP / FTPS | 22 / 990 | SSH / TLS |
| HTTP | 80 | HTTPS | 443 | TLS |
| SMTP | 25 | SMTPS / Submission | 465 / 587 | TLS |
| POP3 | 110 | POP3S | 995 | TLS |
| IMAP | 143 | IMAPS | 993 | TLS |
| LDAP | 389 | LDAPS | 636 | TLS |
| Syslog | 514 | Syslog-TLS | 6514 | TLS |
| SIP | 5060 | SIP-TLS | 5061 | TLS |
| SNMP v1/v2c | 161 | SNMPv3 | 161 | AES + Auth |

---

### 📞 VoIP Ports

| Port | Protocol | Transport | Purpose |
|------|----------|-----------|---------|
| 5060 | SIP | TCP/UDP | VoIP call signaling (unencrypted) |
| 5061 | SIP-TLS | TCP | VoIP call signaling (encrypted) |
| 16384–32767 | RTP | UDP | Real-time voice/video media stream |
| 2000 | SCCP (Skinny) | TCP | Cisco VoIP phone signaling |

---

### 🛡️ VPN Ports

| Port | Protocol | Transport | Purpose |
|------|----------|-----------|---------|
| 500 | IKE | UDP | IPsec key exchange and tunnel setup |
| 1194 | OpenVPN | UDP | OpenVPN default |
| 1701 | L2TP | UDP | L2TP tunnel (used with IPsec) |
| 1723 | PPTP | TCP | Legacy VPN — avoid in production |
| 4500 | IPsec NAT-T | UDP | IPsec when NAT device is present |
| 51820 | WireGuard | UDP | WireGuard VPN default |

---

## 📋 Master Quick-Reference Table

> All exam-critical ports sorted numerically.

| Port | Service | Transport | Category |
|------|---------|-----------|----------|
| 20 | FTP Data | TCP | File Transfer |
| 21 | FTP Control | TCP | File Transfer |
| 22 | SSH / SFTP / SCP | TCP | Remote Access / File Transfer |
| 23 | Telnet | TCP | Remote Access (insecure) |
| 25 | SMTP | TCP | Email |
| 49 | TACACS+ | TCP | Authentication |
| 53 | DNS | TCP/UDP | Name Resolution |
| 67 | DHCP Server | UDP | Address Assignment |
| 68 | DHCP Client | UDP | Address Assignment |
| 69 | TFTP | UDP | File Transfer (lightweight) |
| 80 | HTTP | TCP | Web |
| 88 | Kerberos | TCP/UDP | Authentication |
| 110 | POP3 | TCP | Email (receive) |
| 123 | NTP | UDP | Time Synchronization |
| 143 | IMAP | TCP | Email (receive/sync) |
| 161 | SNMP | UDP | Network Management |
| 162 | SNMP Trap | UDP | Network Management |
| 179 | BGP | TCP | Routing |
| 389 | LDAP | TCP/UDP | Directory Services |
| 443 | HTTPS | TCP | Web (secure) |
| 445 | SMB | TCP | File Sharing / AD |
| 465 | SMTPS | TCP | Email (secure, legacy) |
| 500 | IKE | UDP | VPN / IPsec |
| 514 | Syslog | UDP | Logging |
| 587 | SMTP Submission | TCP | Email (client send) |
| 636 | LDAPS | TCP | Directory Services (secure) |
| 993 | IMAPS | TCP | Email (secure sync) |
| 995 | POP3S | TCP | Email (secure download) |
| 1194 | OpenVPN | UDP | VPN |
| 1433 | MS-SQL | TCP | Database |
| 1701 | L2TP | UDP | VPN |
| 1723 | PPTP | TCP | VPN (legacy) |
| 1812 | RADIUS Auth | UDP | Authentication |
| 1813 | RADIUS Accounting | UDP | Accounting |
| 3306 | MySQL | TCP | Database |
| 3389 | RDP | TCP | Remote Desktop |
| 4500 | IPsec NAT-T | UDP | VPN |
| 5060 | SIP | TCP/UDP | VoIP |
| 5061 | SIP-TLS | TCP | VoIP (secure) |
| 5900 | VNC | TCP | Remote Desktop |
| 6514 | Syslog-TLS | TCP | Logging (secure) |
| 8080 | HTTP-Alt | TCP | Web / Proxy |
| 51820 | WireGuard | UDP | VPN |

---

## 🎯 Exam Tips & Memory Tricks

### 🧠 Memory Tricks

| Ports | Trick |
|-------|-------|
| **20/21** | FTP uses **2**0 for data, **2**1 for control — data comes before control |
| **22** | SSH = **S**ecure **S**hell = **2**2 |
| **25 / 587** | **25** = old SMTP server relay; **587** = modern client submission |
| **53** | DNS = **5**3 — "**D**o **N**ot **S**top at 53" |
| **67/68** | DHCP: **67** = server (higher authority), **68** = client |
| **80 / 443** | HTTP/**8**0 is open; HTTPS/**4**43 is locked (4 = fort) |
| **110 / 143** | POP3/**110** downloads; IMAP/**143** syncs — IMAP is newer, higher port |
| **161 / 162** | SNMP **161** = ask (poll); **162** = tell (trap) |
| **389 / 636** | LDAP/**389** → LDAPS/**636** — add TLS, jump up |
| **3389** | RDP = **R**emote **D**esktop = **3**389 |

---

### ✅ High-Priority Ports — Must Know for N10-009

```
┌─────────────────────────────────────────────────────┐
│  TIER 1 — Guaranteed on the exam                   │
├──────┬──────────────────────────────────────────────┤
│  20  │  FTP Data                                    │
│  21  │  FTP Control                                 │
│  22  │  SSH                                         │
│  23  │  Telnet                                      │
│  25  │  SMTP                                        │
│  53  │  DNS                                         │
│  67  │  DHCP Server                                 │
│  68  │  DHCP Client                                 │
│  80  │  HTTP                                        │
│ 110  │  POP3                                        │
│ 143  │  IMAP                                        │
│ 161  │  SNMP                                        │
│ 443  │  HTTPS                                       │
│ 3389 │  RDP                                         │
└──────┴──────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────┐
│  TIER 2 — Highly likely                            │
├──────┬──────────────────────────────────────────────┤
│  69  │  TFTP                                        │
│  88  │  Kerberos                                    │
│ 123  │  NTP                                         │
│ 162  │  SNMP Trap                                   │
│ 389  │  LDAP                                        │
│ 445  │  SMB                                         │
│ 514  │  Syslog                                      │
│ 587  │  SMTP Submission                             │
│ 636  │  LDAPS                                       │
│1812  │  RADIUS                                      │
└──────┴──────────────────────────────────────────────┘
```

---

### ⚠️ Common Exam Traps

| Trap | Clarification |
|------|---------------|
| FTP uses **two** ports | Port 21 = control/commands; Port 20 = actual data transfer |
| DNS uses **both** TCP and UDP | UDP for normal queries; TCP for zone transfers and responses >512 bytes |
| SFTP ≠ FTPS | SFTP runs over SSH (port 22); FTPS is FTP + TLS (port 990) |
| SMTP has **3 ports** | 25 (relay), 465 (legacy secure), 587 (modern submission with STARTTLS) |
| SNMP **161** vs **162** | 161 = manager polls agent; 162 = agent sends unsolicited trap to manager |
| RADIUS encrypts **password only** | TACACS+ encrypts the **entire** payload |
| Port **8080** ≠ HTTPS | 8080 is HTTP alternate — unencrypted; 8443 is the HTTPS alternate |
| RDP uses **TCP and UDP** | Primarily TCP 3389, but UDP 3389 is used for performance in newer versions |

---

*📁 Part of the Network+ N10-009 Study Series | `/Resources/port-number-cheat-sheet.md`*
