# 📝 Practice Questions — Chapter 4
### *Networking Ports, Protocols & Services | Network+ N10-009 Study Series*

![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B%20N10--009-FF0000?style=for-the-badge&logo=comptia&logoColor=white)
![Chapter](https://img.shields.io/badge/Chapter-04%20Ports%2C%20Protocols%20%26%20Services-FF6B35?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-60-28A745?style=for-the-badge)
![Difficulty](https://img.shields.io/badge/Difficulty-Mixed-6F42C1?style=for-the-badge)

> 📌 60 practice questions covering all exam-critical ports and protocols — file transfer,
> email, web, remote access, directory services, network management, authentication,
> VoIP, routing protocols, TCP vs UDP, and port number identification.
> Ports are among the most heavily tested topics on the N10-009 — know them cold.
> Answers and detailed explanations are at the bottom — attempt all questions first!

---

## 📑 Table of Contents

1. [Multiple Choice — Single Answer (Q1–Q38)](#-multiple-choice--single-answer)
2. [Multiple Choice — Multiple Answer (Q39–Q48)](#-multiple-choice--multiple-answer-select-all-that-apply)
3. [Scenario-Based Questions (Q49–Q56)](#-scenario-based-questions)
4. [Port Identification (Q57–Q60)](#-port-identification)
5. [Answer Key & Explanations](#-answer-key--explanations)
6. [Score Tracker](#-score-tracker)

---

## 🔵 Multiple Choice — Single Answer

*Select the single best answer for each question.*

---

**Q1.** Which port does SSH use by default?

- A) 21
- B) 23
- C) **22**
- D) 443

---

**Q2.** A mail server needs to receive incoming email from other mail servers on the internet. Which protocol and port combination handles server-to-server email relay?

- A) POP3 — port 110
- B) IMAP — port 143
- C) **SMTP — port 25**
- D) SMTP — port 587

---

**Q3.** Which port does DNS use for standard queries?

- A) 80
- B) **53**
- C) 123
- D) 443

---

**Q4.** A user wants to retrieve email from a server and have the messages downloaded and removed from the server. Which protocol is MOST appropriate?

- A) SMTP
- B) IMAP
- C) **POP3**
- D) SNMP

---

**Q5.** Which protocol allows email clients to synchronize messages across multiple devices while keeping mail stored on the server?

- A) POP3
- B) SMTP
- C) **IMAP**
- D) Telnet

---

**Q6.** An administrator needs to transfer a Cisco router's configuration file to a TFTP server. Which port does TFTP use?

- A) 20
- B) 21
- C) 22
- D) **69**

---

**Q7.** Which of the following protocols transmits data — including usernames and passwords — in plaintext and should be replaced with SSH?

- A) FTP
- B) **Telnet**
- C) SFTP
- D) RDP

---

**Q8.** A network engineer needs to remotely manage a Windows server's graphical desktop interface from another Windows machine. Which protocol and port should they use?

- A) SSH — port 22
- B) VNC — port 5900
- C) Telnet — port 23
- D) **RDP — port 3389**

---

**Q9.** Which protocol and port does HTTPS use?

- A) TCP port 80
- B) UDP port 443
- C) **TCP port 443**
- D) TCP port 8080

---

**Q10.** Which of the following correctly describes the difference between FTP active mode and FTP passive mode?

- A) Active mode is encrypted; passive mode is unencrypted
- B) **In active mode the server initiates the data connection back to the client; in passive mode the client initiates both the control and data connections**
- C) Active mode uses port 21; passive mode uses port 20
- D) Active mode uses UDP; passive mode uses TCP

---

**Q11.** Which DHCP message does a client send first when it has no IP address and needs to discover available DHCP servers?

- A) DHCP Offer
- B) DHCP Request
- C) DHCP Acknowledge
- D) **DHCP Discover**

---

**Q12.** A network administrator is configuring centralized authentication for all wireless users using 802.1X. Which protocol handles the AAA (Authentication, Authorization, and Accounting) function and uses UDP ports 1812 and 1813?

- A) TACACS+
- B) Kerberos
- C) LDAP
- D) **RADIUS**

---

**Q13.** Which protocol uses TCP port 49 and is preferred over RADIUS for authenticating administrators to network devices because it encrypts the entire payload?

- A) RADIUS
- B) Kerberos
- C) **TACACS+**
- D) LDAP

---

**Q14.** An administrator wants to monitor network devices and receive automatic alerts when a device goes down or exceeds a threshold. Which protocol is used for the agent to send unsolicited notifications to the management station?

- A) SNMP GET
- B) SNMP SET
- C) **SNMP Trap (port 162)**
- D) SNMP Walk

---

**Q15.** Which of the following protocols provides time synchronization across network devices and uses UDP port 123?

- A) SNMP
- B) DNS
- C) DHCP
- D) **NTP**

---

**Q16.** A junior administrator is setting up a syslog server to collect log messages from routers and switches. Which port does syslog use by default?

- A) 161
- B) 162
- C) **514**
- D) 123

---

**Q17.** Which protocol provides directory services for user authentication in a Windows Active Directory environment and uses TCP/UDP port 389 for unencrypted queries?

- A) RADIUS
- B) Kerberos
- C) TACACS+
- D) **LDAP**

---

**Q18.** A company's security policy requires that all directory service queries be encrypted. Which port should LDAP use with TLS enabled?

- A) 389
- B) 88
- C) **636**
- D) 443

---

**Q19.** Which of the following protocols does Kerberos use for network authentication, and what port does it run on?

- A) UDP port 88 only
- B) TCP port 88 only
- C) **TCP and UDP port 88**
- D) TCP port 389

---

**Q20.** A network engineer is setting up file and printer sharing between Windows computers. Which protocol and port handles Windows file sharing?

- A) NFS — port 2049
- B) FTP — port 21
- C) SFTP — port 22
- D) **SMB — port 445**

---

**Q21.** Which of the following is the secure version of FTP that uses SSL/TLS for encryption and uses implicit TLS on port 990?

- A) SFTP
- B) SCP
- C) **FTPS**
- D) TFTP

---

**Q22.** Which SMTP port is the modern standard for client email submission with STARTTLS encryption?

- A) Port 25
- B) Port 110
- C) Port 465
- D) **Port 587**

---

**Q23.** Which protocol resolves a known IP address to its corresponding MAC address on a local network segment?

- A) DNS
- B) RARP
- C) DHCP
- D) **ARP**

---

**Q24.** A user reports they can access websites by IP address but not by domain name. Which protocol and port is MOST likely failing?

- A) HTTP — port 80
- B) HTTPS — port 443
- C) **DNS — port 53**
- D) DHCP — port 67

---

**Q25.** Which of the following transport protocols provides reliable, ordered, and error-checked delivery and requires a three-way handshake before data transfer?

- A) UDP
- B) ICMP
- C) IP
- D) **TCP**

---

**Q26.** Which transport protocol is connectionless, provides no error recovery, and is preferred for real-time applications like VoIP and live streaming?

- A) TCP
- B) ICMP
- C) **UDP**
- D) ARP

---

**Q27.** What is the correct order of the TCP three-way handshake?

- A) SYN → ACK → SYN-ACK
- B) ACK → SYN → SYN-ACK
- C) SYN-ACK → SYN → ACK
- D) **SYN → SYN-ACK → ACK**

---

**Q28.** Which protocol is used by the `ping` command to test connectivity between two hosts?

- A) TCP
- B) UDP
- C) ARP
- D) **ICMP**

---

**Q29.** A VoIP system uses SIP for call setup and signaling. Which port does unencrypted SIP use?

- A) 5061
- B) 443
- C) 1720
- D) **5060**

---

**Q30.** Which of the following routing protocols is a link-state IGP that uses cost (based on bandwidth) as its metric and is defined in an open standard (RFC 2328)?

- A) RIP
- B) EIGRP
- C) BGP
- D) **OSPF**

---

**Q31.** Which routing protocol is classified as an EGP (Exterior Gateway Protocol) and is used to route traffic between different autonomous systems on the internet? It uses TCP port 179.

- A) OSPF
- B) EIGRP
- C) RIP
- D) **BGP**

---

**Q32.** Which protocol version of SNMP added authentication and encryption, making it the only version recommended for production use?

- A) SNMPv1
- B) SNMPv2c
- C) **SNMPv3**
- D) SNMPv4

---

**Q33.** DNS uses UDP for standard queries. In which situation does DNS switch to TCP instead?

- A) When querying an internal DNS server
- B) When resolving IPv6 addresses
- C) **When performing zone transfers or when the response exceeds 512 bytes**
- D) When using DNSSEC

---

**Q34.** Which of the following ports is used by the IMAP protocol when secured with SSL/TLS (IMAPS)?

- A) 143
- B) 110
- C) 993
- D) **993**

---

**Q35.** A network administrator needs to use a protocol to pull configuration files to network devices during PXE boot or for firmware upgrades. The protocol requires no authentication and uses UDP. Which protocol should they use?

- A) FTP
- B) SFTP
- C) SCP
- D) **TFTP**

---

**Q36.** Which of the following is TRUE about the difference between SFTP and FTPS?

- A) SFTP uses TLS; FTPS uses SSH
- B) SFTP uses ports 20/21; FTPS uses port 22
- C) SFTP and FTPS both use port 990
- D) **SFTP is built on SSH and uses port 22; FTPS is FTP with TLS and uses ports 20/21 or 990**

---

**Q37.** Which protocol maps domain names to IP addresses and operates at the Application layer? It uses a hierarchical, distributed database structure.

- A) ARP
- B) DHCP
- C) NTP
- D) **DNS**

---

**Q38.** A network engineer is reviewing firewall logs and sees traffic on port 3389 coming from an external IP address. Which protocol is MOST likely being targeted, and what is the security risk?

- A) SSH — brute force attempts on Linux servers
- B) SMTP — email relay abuse
- C) **RDP — unauthorized remote desktop access attempts**
- D) SNMP — network device enumeration

---

## 🟡 Multiple Choice — Multiple Answer (Select ALL that apply)

*These questions may have 2 or more correct answers.*

---

**Q39.** Which of the following protocols use TCP as their transport? *(Select THREE)*

- A) **SSH (port 22)**
- B) DNS queries (port 53)
- C) **SMTP (port 25)**
- D) DHCP (port 67/68)
- E) **HTTPS (port 443)**
- F) TFTP (port 69)

---

**Q40.** Which of the following protocols use UDP as their transport? *(Select THREE)*

- A) FTP (port 20/21)
- B) **DHCP (port 67/68)**
- C) Telnet (port 23)
- D) **TFTP (port 69)**
- E) **SNMP (port 161/162)**
- F) LDAP (port 389)

---

**Q41.** Which of the following statements about DHCP are TRUE? *(Select TWO)*

- A) **The DHCP DORA process stands for Discover, Offer, Request, Acknowledge**
- B) DHCP uses TCP for reliable delivery of IP address assignments
- C) **DHCP Discover and DHCP Request messages are sent as broadcasts**
- D) DHCP assigns permanent IP addresses that never change
- E) DHCP operates at the Network layer (Layer 3)

---

**Q42.** Which of the following are TRUE about DNS record types? *(Select THREE)*

- A) **An A record maps a hostname to an IPv4 address**
- B) A PTR record maps a hostname to a MAC address
- C) **An MX record identifies the mail server for a domain**
- D) **An AAAA record maps a hostname to an IPv6 address**
- E) A CNAME record maps an IP address to a hostname

---

**Q43.** Which of the following are TRUE about the difference between RADIUS and TACACS+? *(Select TWO)*

- A) RADIUS encrypts the entire authentication payload; TACACS+ encrypts only the password
- B) **RADIUS encrypts only the password; TACACS+ encrypts the entire payload**
- C) Both RADIUS and TACACS+ use UDP for transport
- D) **RADIUS uses UDP ports 1812/1813; TACACS+ uses TCP port 49**
- E) RADIUS is preferred for device administration; TACACS+ is preferred for network access

---

**Q44.** Which of the following statements about SNMPv3 are TRUE? *(Select TWO)*

- A) SNMPv3 uses community strings for authentication
- B) **SNMPv3 supports authentication using MD5 or SHA**
- C) SNMPv3 does not support encryption
- D) **SNMPv3 supports encryption using AES or DES for data privacy**
- E) SNMPv3 uses TCP for all operations

---

**Q45.** Which of the following statements about FTP are TRUE? *(Select TWO)*

- A) FTP encrypts all data transfers by default
- B) **FTP uses two separate connections — port 21 for control and port 20 for data (in active mode)**
- C) FTP uses a single UDP port for all operations
- D) **FTP sends credentials in plaintext and should be replaced by SFTP or FTPS in production**
- E) FTP passive mode requires the server to initiate the data connection

---

**Q46.** A network administrator is reviewing which protocols use both TCP and UDP. Which of the following use BOTH TCP and UDP? *(Select TWO)*

- A) HTTP
- B) **DNS (port 53)**
- C) DHCP
- D) **Kerberos (port 88)**
- E) FTP

---

**Q47.** Which of the following are TRUE about NTP? *(Select TWO)*

- A) NTP uses TCP port 123 for time synchronization
- B) **NTP uses UDP port 123 for time synchronization**
- C) **Accurate time synchronization is critical for Kerberos authentication, which has a maximum 5-minute clock skew tolerance**
- D) NTP operates at Layer 2 of the OSI model
- E) NTP replaces DNS for hostname resolution

---

**Q48.** Which of the following are TRUE about ICMP? *(Select TWO)*

- A) ICMP uses port 80 for echo requests
- B) **ICMP is used by `ping` (echo request/reply) and `traceroute` (TTL exceeded)**
- C) ICMP guarantees reliable delivery of error messages
- D) **ICMP operates at Layer 3 and does not use port numbers**
- E) ICMP requires a TCP handshake before sending error messages

---

## 🟠 Scenario-Based Questions

*Read each scenario carefully and select the BEST answer.*

---

**Q49.** A help desk technician receives a call from a user who says they can send emails but cannot receive any new ones. The technician checks and finds that the user's email client is configured to connect to the mail server on port 25. What is the MOST likely cause of the problem, and how should it be fixed?

- A) Port 25 is correct for receiving email; the ISP is blocking the connection
- B) The user needs to switch from TCP to UDP for email retrieval
- C) Port 25 should be changed to port 443 for secure email retrieval
- D) **Port 25 is for sending (SMTP relay), not receiving; the client should be reconfigured to use IMAP (port 143/993) or POP3 (port 110/995) for incoming mail**

---

**Q50.** A security analyst is reviewing firewall rules and notices that UDP port 161 is open inbound from the internet to internal network devices. The SNMP community string is set to "public." What is the security risk, and what should the analyst recommend?

- A) No risk — SNMP is read-only and cannot change device configurations
- B) Port 161 uses TCP, not UDP, so the rule is ineffective anyway
- C) **Serious risk — port 161 inbound from the internet exposes device management data; the analyst should block inbound UDP 161 from the internet and upgrade to SNMPv3 with strong authentication**
- D) The risk is low because "public" is a standard community string that all vendors support

---

**Q51.** A junior network engineer is troubleshooting a connectivity issue. A workstation can ping the gateway (10.0.0.1) successfully but cannot reach any internet websites. The engineer runs `nslookup google.com` and gets a timeout. However, pinging `8.8.8.8` directly works. What is the MOST likely cause?

- A) The default gateway is misconfigured
- B) The firewall is blocking ICMP traffic
- C) The workstation has an incorrect subnet mask
- D) **DNS resolution is failing — UDP/TCP port 53 traffic to the DNS server is likely blocked or the DNS server is unreachable**

---

**Q52.** An administrator is configuring a new email server. They want outbound emails from the server to be relayed to other mail servers, and they also want users to submit email from their clients using authenticated, encrypted STARTTLS. Which two ports should be open on the mail server?

- A) Port 110 and port 143
- B) Port 993 and port 995
- C) **Port 25 (server-to-server relay) and port 587 (authenticated client submission with STARTTLS)**
- D) Port 80 and port 443

---

**Q53.** A network engineer runs `traceroute 8.8.8.8` from a workstation. The first 3 hops reply normally, but hop 4 shows `* * *` (no reply). Which of the following BEST explains this behavior?

- A) The destination host (8.8.8.8) is offline
- B) The workstation has an incorrect default gateway
- C) **A router or firewall at hop 4 is filtering ICMP TTL-exceeded messages — the route may still work, but that hop is not responding to ICMP**
- D) The DNS server at hop 4 is not resolving the IP address

---

**Q54.** During a security audit, an auditor finds that an organization uses Telnet to manage its network switches and routers. The auditor flags this as a critical finding. What is the PRIMARY reason, and what should replace it?

- A) Telnet is too slow for modern networks; it should be replaced with HTTPS
- B) Telnet is deprecated and no longer supported by modern operating systems
- C) **Telnet transmits all data including credentials in plaintext — it should be replaced with SSH (port 22) which encrypts the entire session**
- D) Telnet uses UDP which is unreliable; it should be replaced with a TCP-based protocol

---

**Q55.** A systems administrator needs to transfer a large database backup file from a Linux server to another Linux server securely. They want authentication via SSH keys and encryption in transit. Which protocol should they use?

- A) FTP — it supports encryption with AUTH TLS
- B) TFTP — it is lightweight and fast
- C) FTPS — it provides TLS encryption over FTP
- D) **SCP or SFTP — both run over SSH (port 22), providing key-based authentication and full encryption**

---

**Q56.** A network team is deploying a new VoIP system. The voice quality engineer wants to ensure that SIP signaling is encrypted and that media traffic (actual voice audio) uses the appropriate transport protocol. Which combination is correct?

- A) SIP over TCP port 5060 for signaling; TCP for RTP voice streams
- B) SIP over UDP port 5060 for signaling; TCP for all voice data
- C) **SIP-TLS over TCP port 5061 for encrypted signaling; RTP/SRTP over UDP for voice media streams**
- D) SIP over UDP port 443; RTP over TCP for voice media

---

## 🟢 Port Identification

*Match the port number to its protocol and function.*

---

**Q57.** Match each port number to its correct protocol:

| Port | Protocol |
|------|----------|
| A) 20 | ① LDAPS |
| B) 22 | ② TFTP |
| C) 53 | ③ FTP Data |
| D) 69 | ④ SSH / SFTP |
| E) 88 | ⑤ DNS |
| F) 389 | ⑥ Kerberos |
| G) 636 | ⑦ LDAP |

*What is the correct matching?*

- A) A-③, B-④, C-⑤, D-②, E-⑥, F-⑦, G-①
- B) A-②, B-④, C-⑤, D-③, E-⑥, F-①, G-⑦
- C) A-③, B-④, C-⑤, D-②, E-⑦, F-⑥, G-①
- **D) A-③, B-④, C-⑤, D-②, E-⑥, F-⑦, G-①**

---

**Q58.** A firewall administrator sees the following destination ports in traffic logs. Which traffic type corresponds to each port?

| Port | Traffic Type |
|------|-------------|
| A) 25 | ① Encrypted web traffic |
| B) 80 | ② SNMP device monitoring |
| C) 161 | ③ Unencrypted web traffic |
| D) 443 | ④ Remote desktop (Windows) |
| E) 514 | ⑤ SMTP email relay |
| F) 3389 | ⑥ Syslog |

*What is the correct matching?*

- A) A-⑤, B-①, C-②, D-③, E-⑥, F-④
- **B) A-⑤, B-③, C-②, D-①, E-⑥, F-④**
- C) A-②, B-③, C-⑤, D-①, E-⑥, F-④
- D) A-⑤, B-③, C-①, D-②, E-④, F-⑥

---

**Q59.** Which of the following port-to-protocol assignments is INCORRECT?

- A) Port 22 — SSH
- B) Port 67 — DHCP Server
- C) Port 123 — NTP
- D) **Port 143 — POP3**

---

**Q60.** A network technician is given a list of ports and asked to categorize each as "well-known" (0–1023) or "registered" (1024–49151). Which of the following is a REGISTERED port (not well-known)?

- A) Port 22 (SSH)
- B) Port 443 (HTTPS)
- C) Port 53 (DNS)
- D) **Port 3389 (RDP)**

---

---
---

# ✅ Answer Key & Explanations

> ⚠️ **Attempt all 60 questions before reading the answers!**

---

## Single Answer — Q1 through Q38

---

**Q1. Answer: C — Port 22**
> SSH (Secure Shell) uses TCP port 22. It replaced Telnet as the standard for encrypted remote CLI access. Port 22 is also used by SFTP and SCP, which tunnel file transfer over SSH. Port 21 = FTP control. Port 23 = Telnet. Port 443 = HTTPS.

---

**Q2. Answer: C — SMTP — port 25**
> SMTP (Simple Mail Transfer Protocol) on port 25 is used for server-to-server email relay — when one mail server sends email to another on the internet. Port 587 is for client-to-server submission (authenticated clients sending email). POP3 (110) and IMAP (143) are for retrieving mail, not sending or relaying it.

---

**Q3. Answer: B — Port 53**
> DNS (Domain Name System) uses port 53 for both TCP and UDP. Standard queries use UDP port 53 (fast, low overhead). Zone transfers and responses larger than 512 bytes use TCP port 53. Port 80 = HTTP. Port 123 = NTP. Port 443 = HTTPS.

---

**Q4. Answer: C — POP3**
> POP3 (Post Office Protocol version 3) downloads email from the server to the local client and by default deletes it from the server. It is best suited for single-device use where the user wants local copies of all mail. IMAP keeps mail on the server and syncs across devices. SMTP sends mail. SNMP manages network devices.

---

**Q5. Answer: C — IMAP**
> IMAP (Internet Message Access Protocol) stores email on the server and synchronizes the mailbox state across all client devices (phone, laptop, tablet). When you read or delete a message on one device, it is reflected on all others. POP3 downloads and (usually) removes mail from the server, making multi-device sync impossible. SMTP sends mail.

---

**Q6. Answer: D — Port 69**
> TFTP (Trivial File Transfer Protocol) uses UDP port 69. It requires no authentication and is intentionally simple — used for PXE network booting, transferring router/switch configuration files, and firmware upgrades. Its lack of authentication is a deliberate design choice for simple device bootstrapping environments. FTP uses ports 20/21. SSH/SFTP uses port 22.

---

**Q7. Answer: B — Telnet**
> Telnet (port 23) transmits everything — including the username and password — in clear plaintext. Anyone with network access can capture Telnet credentials with a packet sniffer. SSH (port 22) replaced Telnet by providing an encrypted channel for remote CLI access. FTP also sends credentials in plaintext but the question specifies "should be replaced with SSH" specifically. SFTP and RDP have their own encrypted mechanisms.

---

**Q8. Answer: D — RDP — port 3389**
> RDP (Remote Desktop Protocol) uses TCP port 3389 (and also UDP 3389 in newer versions for performance optimization). It provides full graphical desktop access to Windows systems. SSH (22) provides CLI access. VNC (5900) provides graphical access but is cross-platform and less feature-rich than RDP. Telnet (23) is plaintext CLI only.

---

**Q9. Answer: C — TCP port 443**
> HTTPS (HTTP Secure) uses TCP port 443. It is HTTP encrypted with TLS. The "S" in HTTPS = TLS encryption. It uses TCP (not UDP) for reliable delivery. Port 80 = plain HTTP. Port 8080 is an alternate HTTP port commonly used for proxy servers and development.

---

**Q10. Answer: B — Active = server initiates data connection; passive = client initiates both**
> FTP uses two connections: port 21 for control (commands) and port 20 for data transfer. In active mode, the client opens a random high port and tells the server; the server then initiates the data connection FROM port 20 back to the client. In passive mode, the server opens a random high port and tells the client; the client initiates the data connection TO the server. Passive mode is firewall-friendly because the client always initiates. Neither mode provides encryption — that requires SFTP or FTPS.

---

**Q11. Answer: D — DHCP Discover**
> The DHCP DORA process: (1) **D**iscover — client broadcasts to find DHCP servers (source IP: 0.0.0.0, destination: 255.255.255.255), (2) **O**ffer — server offers an IP address, (3) **R**equest — client requests the offered IP, (4) **A**cknowledge — server confirms the lease. The Discover is always the first step when a client has no IP address.

---

**Q12. Answer: D — RADIUS**
> RADIUS (Remote Authentication Dial-In User Service) uses UDP port 1812 for authentication/authorization and UDP port 1813 for accounting. It is the standard AAA protocol for 802.1X wireless and VPN authentication. TACACS+ (TCP port 49) is preferred for device administration. Kerberos (TCP/UDP port 88) is used in Active Directory. LDAP (port 389) provides directory lookups.

---

**Q13. Answer: C — TACACS+**
> TACACS+ uses TCP port 49 and encrypts the ENTIRE payload (not just the password). It separates Authentication, Authorization, and Accounting into independent functions. It is Cisco-proprietary but widely adopted. TACACS+ is preferred for authenticating administrators to network devices. RADIUS encrypts only the password field and is preferred for network access (VPN, wireless).

---

**Q14. Answer: C — SNMP Trap (port 162)**
> An SNMP Trap is an unsolicited notification sent FROM an agent (network device) TO a management station (NMS) when a threshold is exceeded or an event occurs (e.g., interface down). SNMP agents listen on UDP port 161 for queries from the manager. The manager receives traps on UDP port 162. SNMP GET retrieves a specific OID value. SNMP SET changes a value.

---

**Q15. Answer: D — NTP**
> NTP (Network Time Protocol) uses UDP port 123 to synchronize clocks across all network devices. Accurate time is critical for: log correlation (events must be in order), Kerberos authentication (5-minute clock skew tolerance), certificate validity, and forensics. NTP uses a hierarchical stratum model (Stratum 0 = atomic clock reference).

---

**Q16. Answer: C — Port 514**
> Syslog uses UDP port 514 for sending system log messages from devices to a centralized syslog server. Syslog-TLS uses TCP port 6514 for encrypted log forwarding. Port 161 = SNMP agent queries. Port 162 = SNMP Traps. Port 123 = NTP.

---

**Q17. Answer: D — LDAP**
> LDAP (Lightweight Directory Access Protocol) uses TCP/UDP port 389 for unencrypted directory service queries. It is the standard protocol for accessing Active Directory. When secured with TLS, it becomes LDAPS and uses port 636. RADIUS handles AAA. Kerberos handles ticket-based authentication. TACACS+ handles device administration authentication.

---

**Q18. Answer: C — Port 636**
> LDAPS (LDAP over SSL/TLS) uses TCP port 636. It encrypts the entire LDAP session, protecting directory queries including usernames, passwords, and group membership data in transit. Port 389 = unencrypted LDAP. Port 88 = Kerberos. Port 443 = HTTPS.

---

**Q19. Answer: C — TCP and UDP port 88**
> Kerberos uses BOTH TCP port 88 AND UDP port 88. UDP is used for lightweight ticket requests. TCP is used when Kerberos messages are too large for UDP (e.g., when a user is a member of many groups, the Privilege Attribute Certificate (PAC) can be large). Kerberos is the default authentication protocol in Microsoft Active Directory environments.

---

**Q20. Answer: D — SMB — port 445**
> SMB (Server Message Block) uses TCP port 445 for Windows file and printer sharing. It is the protocol used when you access a shared folder like `\\server\share` on a Windows network. It is also used by Active Directory for SYSVOL and NETLOGON shares. NFS (port 2049) is the Linux/Unix equivalent. FTP and SFTP are for explicit file transfers, not network drive sharing.

---

**Q21. Answer: C — FTPS**
> FTPS (FTP Secure) is FTP extended with TLS/SSL encryption. Implicit FTPS (the original version) uses port 990 — the TLS handshake begins immediately. Explicit FTPS uses port 21 with the `AUTH TLS` command upgrading the connection. SFTP is a completely different protocol based on SSH (port 22) — it is NOT an extension of FTP. SCP also runs over SSH but is a simpler single-file copy tool.

---

**Q22. Answer: D — Port 587**
> Port 587 with STARTTLS is the modern standard for email client submission. The client connects on port 587, then issues the `STARTTLS` command to upgrade to an encrypted TLS session before sending credentials. Port 25 is for server-to-server relay (not client submission, often blocked by ISPs for residential users). Port 465 is the legacy SMTPS implicit SSL port (still used by some providers but 587 is preferred).

---

**Q23. Answer: D — ARP**
> ARP (Address Resolution Protocol) resolves a known IPv4 address to the corresponding MAC address on the same local subnet. The process: host broadcasts "Who has IP x.x.x.x?" → The device with that IP replies "I have it — here's my MAC." The result is stored in the ARP cache. DNS resolves domain names to IP addresses. RARP was the reverse (MAC to IP — now replaced by DHCP). DHCP assigns IP addresses dynamically.

---

**Q24. Answer: C — DNS — port 53**
> The key clue: websites work by IP but not by name. This isolates the failure to name resolution — the process of converting domain names to IP addresses. DNS (port 53) handles this. HTTP/HTTPS (80/443) are working because pinging by IP succeeds and presumably web browsing by IP works too. DHCP (67) assigns IPs — since the host has connectivity by IP, DHCP worked fine.

---

**Q25. Answer: D — TCP**
> TCP (Transmission Control Protocol) provides: reliable delivery (acknowledgments + retransmission), ordered delivery (sequence numbers), error checking (checksums), flow control (sliding window), and connection establishment (three-way handshake: SYN-SYN/ACK-ACK). TCP is used by HTTP/S, FTP, SSH, SMTP, and other protocols where data integrity is critical.

---

**Q26. Answer: C — UDP**
> UDP (User Datagram Protocol) is connectionless — no handshake, no acknowledgments, no retransmissions. It is "best-effort" delivery. Its low overhead makes it ideal for real-time applications (VoIP, video streaming, online gaming, DNS queries, DHCP) where a small amount of loss is acceptable but latency must be minimal. A retransmitted voice packet arriving 500ms late is useless.

---

**Q27. Answer: D — SYN → SYN-ACK → ACK**
> The TCP three-way handshake: (1) Client sends **SYN** (synchronize — "I want to connect, here's my sequence number"), (2) Server responds with **SYN-ACK** (synchronize-acknowledge — "Acknowledged, here's my sequence number"), (3) Client sends **ACK** (acknowledge — "Got it, connection established"). After this, data transfer begins.

---

**Q28. Answer: D — ICMP**
> The `ping` command uses ICMP (Internet Control Message Protocol) Echo Request (Type 8) and Echo Reply (Type 0) messages to test reachability. `traceroute` uses ICMP TTL-Exceeded (Type 11) messages. ICMP does not use port numbers — it is a Layer 3 protocol embedded in IP packets. ARP resolves MAC addresses. TCP and UDP carry application data.

---

**Q29. Answer: D — Port 5060**
> SIP (Session Initiation Protocol) uses TCP/UDP port 5060 for unencrypted VoIP signaling (call setup, teardown, registration). SIP-TLS uses TCP port 5061 for encrypted signaling. The actual voice/video data stream travels separately using RTP (Real-time Transport Protocol) over UDP ports 16384–32767. Port 1720 is H.323 (an older VoIP signaling protocol).

---

**Q30. Answer: D — OSPF**
> OSPF (Open Shortest Path First) is a link-state IGP (Interior Gateway Protocol) that builds a complete topology map of the network using LSAs (Link State Advertisements) and the Dijkstra algorithm. Its metric is cost (inversely proportional to bandwidth — higher bandwidth = lower cost). It is an open standard (RFC 2328 for OSPFv2, RFC 5340 for OSPFv3/IPv6). EIGRP is Cisco proprietary hybrid. RIP uses hop count. BGP is an EGP.

---

**Q31. Answer: D — BGP**
> BGP (Border Gateway Protocol) is the EGP (Exterior Gateway Protocol) of the internet — the protocol that routes traffic between different autonomous systems (AS). It uses TCP port 179. It is the routing protocol of the internet backbone. OSPF and EIGRP are IGPs (interior — within one AS). BGP uses path vector routing with AS-path attributes, not simple metric-based routing.

---

**Q32. Answer: C — SNMPv3**
> SNMPv1 and SNMPv2c use community strings (plaintext passwords) for authentication with no encryption. SNMPv3 added: authentication (MD5 or SHA-based HMAC), privacy/encryption (AES or DES), and access control. SNMPv3 is the only version recommended for production environments. There is no SNMPv4. On the exam: always recommend SNMPv3 when security is a concern.

---

**Q33. Answer: C — Zone transfers or responses exceeding 512 bytes**
> DNS defaults to UDP for its speed and low overhead. UDP is limited to 512-byte payloads (for standard DNS). DNS switches to TCP when: (1) performing zone transfers (copying entire DNS zone data between servers), (2) when a response exceeds 512 bytes (e.g., large DNSSEC records), or (3) when EDNS0 buffer sizes are exceeded. This is a frequently tested nuance.

---

**Q34. Answer: C/D — Port 993**
> IMAPS (IMAP over SSL/TLS) uses TCP port 993. The "S" suffix indicates the secure version. Unencrypted IMAP = port 143. POP3S (secure POP3) = port 995. Unencrypted POP3 = port 110. Note: Both C and D say 993 — the correct answer is 993.

---

**Q35. Answer: D — TFTP**
> TFTP (Trivial File Transfer Protocol, UDP port 69) requires no authentication, has no directory browsing capability, and provides only basic file transfer. It is intentionally limited for simplicity. Common uses: PXE boot (network booting thin clients), uploading/downloading router and switch configuration files, and pushing firmware updates to network devices. FTP and SFTP require login credentials.

---

**Q36. Answer: D — SFTP uses SSH/port 22; FTPS is FTP + TLS using ports 20/21 or 990**
> This is a classic exam trap. SFTP and FTPS are completely different protocols despite similar names. SFTP = SSH File Transfer Protocol — not related to FTP at all; it runs entirely over SSH on port 22 and is a separate subsystem of the SSH protocol suite. FTPS = FTP Secure — standard FTP extended with TLS/SSL; uses ports 20/21 (explicit) or 990 (implicit TLS). When asked "which is more secure?" — both are encrypted, but SFTP is simpler (single port, single connection).

---

**Q37. Answer: D — DNS**
> DNS (Domain Name System) is the internet's phone book — it translates human-readable domain names (www.google.com) to IP addresses (142.250.80.36). It uses a hierarchical distributed database of nameservers. ARP resolves IP addresses to MAC addresses (not domain names). DHCP assigns IP addresses. NTP synchronizes time.

---

**Q38. Answer: C — RDP — unauthorized remote desktop access attempts**
> Port 3389 is RDP (Remote Desktop Protocol). Seeing inbound traffic from external IPs on port 3389 indicates brute-force or credential-stuffing attempts against Windows Remote Desktop. RDP exposure to the internet is a major attack vector (BlueKeep, DejaBlue vulnerabilities). Best practice: RDP should only be accessible via VPN, or at minimum, protected by network-level authentication and IP allowlisting.

---

## Multiple Answer — Q39 through Q48

---

**Q39. Answer: A — SSH, C — SMTP, E — HTTPS**
> TCP protocols include: SSH (22), FTP (20/21), Telnet (23), SMTP (25), HTTP (80), HTTPS (443), RDP (3389), LDAP (389), SMB (445), POP3 (110), IMAP (143), and many others requiring reliable delivery. DNS queries (53) use UDP by default (TCP for zone transfers). DHCP (67/68) uses UDP. TFTP (69) uses UDP.

---

**Q40. Answer: B — DHCP, D — TFTP, E — SNMP**
> UDP protocols include: DNS queries (53), DHCP (67/68), TFTP (69), SNMP (161/162), Syslog (514), NTP (123), RADIUS (1812/1813), RIP, and VoIP protocols (SIP on 5060, RTP media). FTP (20/21), Telnet (23), and LDAP (389) use TCP. The key pattern: speed-critical and stateless protocols use UDP.

---

**Q41. Answer: A — DORA process, C — Discover and Request are broadcasts**
> DORA = Discover → Offer → Request → Acknowledge. Discover and Request are sent as IPv4 broadcasts (255.255.255.255) because the client has no IP yet. DHCP uses UDP (not TCP) — port 68 (client) to port 67 (server). DHCP assigns leased (temporary) IP addresses with a configurable lease time. DHCP is an Application layer protocol, not Layer 3 (it runs over UDP/IP).

---

**Q42. Answer: A — A record (IPv4), C — MX record (mail server), D — AAAA record (IPv6)**
> DNS record types: A = hostname to IPv4, AAAA = hostname to IPv6, MX = mail exchanger for domain, CNAME = alias (hostname to hostname, NOT IP to hostname), PTR = reverse lookup (IP to hostname — NOT MAC), NS = nameserver, SOA = start of authority, TXT = text (used for SPF, DKIM, domain verification). A PTR record maps an IP address to a hostname — not a MAC address.

---

**Q43. Answer: B — RADIUS encrypts password only / TACACS+ encrypts entire payload, D — RADIUS uses UDP 1812/1813 / TACACS+ uses TCP 49**
> This is one of the most tested RADIUS vs TACACS+ distinctions: RADIUS = UDP, encrypts password field only, combines auth/authorization. TACACS+ = TCP, encrypts entire payload, separates auth/authorization/accounting into three independent functions. RADIUS is preferred for network access (VPN, wireless). TACACS+ is preferred for device administration (configuring routers/switches).

---

**Q44. Answer: B — Supports MD5/SHA authentication, D — Supports AES/DES encryption**
> SNMPv3 adds three security levels: noAuthNoPriv (no security), authNoPriv (authentication without encryption using HMAC-MD5 or HMAC-SHA), and authPriv (authentication + encryption using AES or DES). SNMPv1/v2c use community strings — essentially plaintext passwords with no real security. SNMPv3 does NOT use community strings. It uses UDP (not TCP) like previous versions.

---

**Q45. Answer: B — Two connections (port 21 control, port 20 data), D — Sends credentials in plaintext**
> FTP uses two TCP connections: port 21 for control (commands like LIST, RETR, STOR) and port 20 for data transfer (in active mode). FTP sends the username and password in plaintext — readable by any packet capture tool. In passive mode, the server opens a random high port for data instead of using port 20. FTP does NOT encrypt by default — use SFTP (SSH) or FTPS (TLS) for secure transfers.

---

**Q46. Answer: B — DNS, D — Kerberos**
> DNS uses UDP for standard queries and TCP for zone transfers/large responses. Kerberos uses UDP for short ticket requests and TCP when messages are too large for UDP (e.g., large PAC/group membership data). HTTP uses only TCP. DHCP uses only UDP. FTP uses only TCP.

---

**Q47. Answer: B — UDP port 123, C — Critical for Kerberos (5-minute clock skew)**
> NTP uses UDP port 123 (NOT TCP). Accurate time is critical for: (1) Kerberos authentication — if clock skew exceeds 5 minutes between client and KDC, authentication fails (this prevents replay attacks), (2) log correlation — events from multiple devices must have synchronized timestamps for forensics, (3) certificate validity checking. NTP is a separate protocol from DNS — they serve completely different purposes.

---

**Q48. Answer: B — Used by ping and traceroute, D — Operates at Layer 3 with no port numbers**
> ICMP (Internet Control Message Protocol) is embedded in IP at Layer 3 — it does NOT use port numbers (unlike TCP/UDP). Key ICMP message types: Type 0 = Echo Reply (ping response), Type 3 = Destination Unreachable, Type 8 = Echo Request (ping), Type 11 = Time Exceeded (traceroute). ICMP does not guarantee delivery (it's best-effort like UDP) and does not require a TCP handshake.

---

## Scenario-Based — Q49 through Q56

---

**Q49. Answer: D — Port 25 is for sending, not receiving; use IMAP or POP3**
> Port 25 (SMTP) is specifically for server-to-server mail relay and should NOT be used by email clients to retrieve incoming mail. To receive mail, clients should use: IMAP (port 143 unencrypted, 993 encrypted) for server-synced multi-device access, or POP3 (port 110 unencrypted, 995 encrypted) for downloading to a single device. This is a very common exam-style misconfig scenario.

---

**Q50. Answer: C — Block inbound UDP 161 from internet; upgrade to SNMPv3**
> SNMP port 161 open inbound from the internet is a critical vulnerability. With community string "public" (the default, equivalent to a password), anyone can enumerate device information (interfaces, routing tables, system info) using SNMP GET requests. SNMPv1/v2c with community strings is essentially unauthenticated. The fix: (1) block inbound UDP 161 at the perimeter firewall — SNMP should never be exposed to the internet, (2) upgrade to SNMPv3 with authPriv security level.

---

**Q51. Answer: D — DNS resolution failing — port 53 traffic is blocked or DNS unreachable**
> The diagnostic clues: ping by IP works (Layer 3 routing is fine, no gateway issue), ping 8.8.8.8 works (internet connectivity is fine), but `nslookup` times out. This perfectly isolates the failure to DNS name resolution. UDP/TCP port 53 to the configured DNS server is being blocked by a firewall, or the DNS server itself is down/misconfigured. The subnet mask doesn't affect name resolution. ICMP is clearly working (ping works).

---

**Q52. Answer: C — Port 25 and port 587**
> Mail servers have two distinct outbound roles: (1) Port 25 — for SMTP relay between mail servers on the internet (MTA to MTA), this must be open for sending mail to other domains, (2) Port 587 — for authenticated client submission with STARTTLS, this is where email clients (Outlook, Thunderbird) connect to submit outbound messages. Port 993/995 are for receiving mail (IMAPS/POP3S). Port 80/443 are for web traffic.

---

**Q53. Answer: C — Router/firewall at hop 4 is filtering ICMP**
> `* * *` in traceroute output means no ICMP TTL-Exceeded response was received from that hop within the timeout. This is common because many routers and firewalls are configured to not respond to ICMP (for security or performance reasons). The route itself is often still functional — traffic passes through, but the device simply does not send ICMP Time Exceeded replies back. This does NOT mean the destination is unreachable.

---

**Q54. Answer: C — Telnet sends credentials in plaintext; replace with SSH**
> Telnet (port 23) is unencrypted — everything transmitted, including login credentials, commands, and output, travels in plain ASCII text visible to any packet capture on the path. SSH (port 22) provides strong encryption (AES), public key authentication, and integrity checking. Replacing Telnet with SSH is one of the most fundamental network security hardening steps. Telnet still works on modern systems — it's not obsolete, it's just dangerously insecure.

---

**Q55. Answer: D — SCP or SFTP over SSH**
> Both SCP (Secure Copy) and SFTP (SSH File Transfer Protocol) run over SSH on port 22, providing: (1) public key authentication (passwordless, highly secure), (2) full encryption of both authentication data and file content, (3) integrity verification. FTP with `AUTH TLS` is FTPS — it encrypts but doesn't support SSH key auth by default. TFTP has no authentication or encryption at all. The question specifically requires SSH keys + encryption — that points directly to SCP/SFTP.

---

**Q56. Answer: C — SIP-TLS on TCP port 5061; RTP/SRTP over UDP**
> VoIP has two components: (1) Signaling (call setup/teardown) — uses SIP; unencrypted SIP = UDP/TCP port 5060, encrypted SIP (SIP-TLS) = TCP port 5061, (2) Media (actual voice audio) — uses RTP (Real-time Transport Protocol) over UDP ports 16384–32767; SRTP (Secure RTP) encrypts the voice stream. RTP MUST use UDP — TCP's retransmission overhead causes unacceptable latency for real-time voice. This is a critical VoIP architecture question.

---

## Port Identification — Q57 through Q60

---

**Q57. Answer: D — A-③, B-④, C-⑤, D-②, E-⑥, F-⑦, G-①**

| Port | Protocol | Explanation |
|------|----------|-------------|
| 20 | FTP Data | Active mode data transfer connection |
| 22 | SSH / SFTP | Secure Shell and SSH File Transfer Protocol |
| 53 | DNS | Domain Name System — queries and responses |
| 69 | TFTP | Trivial File Transfer Protocol — UDP, no auth |
| 88 | Kerberos | Active Directory ticket-based authentication |
| 389 | LDAP | Lightweight Directory Access Protocol (unencrypted) |
| 636 | LDAPS | LDAP over SSL/TLS (encrypted) |

---

**Q58. Answer: B — A-⑤, B-③, C-②, D-①, E-⑥, F-④**

| Port | Protocol | Traffic Type |
|------|----------|-------------|
| 25 | SMTP | Email relay between servers |
| 80 | HTTP | Unencrypted web traffic |
| 161 | SNMP | Network device monitoring queries |
| 443 | HTTPS | Encrypted web traffic (TLS) |
| 514 | Syslog | System log forwarding to log server |
| 3389 | RDP | Windows Remote Desktop Protocol |

---

**Q59. Answer: D — Port 143 is IMAP, NOT POP3**
> Port 143 is IMAP (Internet Message Access Protocol), not POP3. POP3 uses port 110 (unencrypted) and port 995 (POP3S — encrypted). All other assignments are correct: Port 22 = SSH ✓, Port 67 = DHCP Server ✓, Port 123 = NTP ✓. This is a classic exam trap — confusing port 143 (IMAP) with POP3 (110).

---

**Q60. Answer: D — Port 3389 (RDP)**
> Port ranges: 0–1023 = Well-Known Ports (assigned by IANA to core internet services). 1024–49151 = Registered Ports (assigned to specific applications). Port 3389 (RDP) falls in the registered port range (1024–49151). Port 22 (SSH) = well-known. Port 443 (HTTPS) = well-known. Port 53 (DNS) = well-known. Other registered ports to know: RADIUS (1812/1813), L2TP (1701), OpenVPN (1194), RDP (3389), SIP (5060/5061), VNC (5900).

---

## 📊 Score Tracker

| Section | Total Q's | Your Score | Percentage | Status |
|---------|-----------|------------|------------|--------|
| Single Answer (Q1–Q38) | 38 | /38 | % | ⬜ |
| Multiple Answer (Q39–Q48) | 10 | /10 | % | ⬜ |
| Scenario-Based (Q49–Q56) | 8 | /8 | % | ⬜ |
| Port Identification (Q57–Q60) | 4 | /4 | % | ⬜ |
| **TOTAL** | **60** | **/60** | **%** | ⬜ |

### Score Guide

| Score | Percentage | Readiness |
|-------|------------|-----------|
| 54–60 | 90–100% | ✅ Excellent — Chapter 4 mastered |
| 45–53 | 75–89% | 🟡 Good — review wrong answers and re-test |
| 36–44 | 60–74% | 🟠 Fair — revisit port cheat sheet and re-test |
| Below 36 | < 60% | 🔴 Needs Work — memorize port table and retry |

### Topic Weakness Identifier

| If you missed… | Review this topic |
|----------------|-------------------|
| Q1, Q7, Q8, Q38, Q54 | Remote access — SSH vs Telnet vs RDP |
| Q2, Q22, Q49, Q52 | Email protocols — SMTP ports 25 vs 587 |
| Q4–Q5 | POP3 vs IMAP differences |
| Q6, Q35 | TFTP — port 69, UDP, no auth |
| Q3, Q24, Q33, Q37, Q42, Q51 | DNS — port 53, record types, TCP vs UDP |
| Q9 | HTTPS — TCP port 443 |
| Q10, Q21, Q36, Q45, Q55 | FTP vs SFTP vs FTPS differences |
| Q11, Q41 | DHCP DORA process |
| Q12, Q13, Q43 | RADIUS vs TACACS+ |
| Q14, Q32, Q44, Q50 | SNMP versions and traps |
| Q15, Q47 | NTP — port 123, Kerberos clock skew |
| Q16 | Syslog — port 514 |
| Q17–Q19, Q46 | LDAP, LDAPS, Kerberos |
| Q20 | SMB — port 445 |
| Q23, Q28, Q48 | ARP and ICMP |
| Q25–Q27, Q39–Q40 | TCP vs UDP — protocols and handshake |
| Q29, Q56 | VoIP — SIP ports 5060/5061, RTP |
| Q30–Q31 | Routing protocols — OSPF vs BGP |
| Q57–Q60 | Port number identification and ranges |

---

> 💡 **Exam Day Tip:** As soon as your exam begins, write your port number table on the
> scratch paper provided. Jot down the critical ports — 20/21 FTP, 22 SSH, 23 Telnet,
> 25 SMTP, 53 DNS, 67/68 DHCP, 69 TFTP, 80 HTTP, 110 POP3, 143 IMAP, 161/162 SNMP,
> 443 HTTPS, 3389 RDP — before you answer a single question. This brain-dump at the
> start will save you time and prevent second-guessing on port questions throughout the exam.

---

*📁 Part of the Network+ N10-009 Study Series | `Chapter-04-Ports-Protocols-Services/practice-questions.md`*
