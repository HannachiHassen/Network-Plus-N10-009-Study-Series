# 📝 Practice Questions — Chapter 2
### *Networking Appliances, Applications & Functions | Network+ N10-009 Study Series*

![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B%20N10--009-FF0000?style=for-the-badge&logo=comptia&logoColor=white)
![Chapter](https://img.shields.io/badge/Chapter-02%20Appliances%2C%20Apps%20%26%20Functions-6F42C1?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-55-28A745?style=for-the-badge)
![Difficulty](https://img.shields.io/badge/Difficulty-Mixed-FF6B35?style=for-the-badge)

> 📌 55 practice questions covering networking appliances (Router, Switch, Hub, Firewall,
> IDS/IPS, Load Balancer, Proxy, NAS, SAN, Wireless AP), networking applications (CDN),
> and networking functions (VPN, QoS, TTL).
> Answers and detailed explanations are at the bottom — attempt all questions first!

---

## 📑 Table of Contents

1. [Multiple Choice — Single Answer (Q1–Q35)](#-multiple-choice--single-answer)
2. [Multiple Choice — Multiple Answer (Q36–Q45)](#-multiple-choice--multiple-answer-select-all-that-apply)
3. [Scenario-Based Questions (Q46–Q52)](#-scenario-based-questions)
4. [Fill in the Blank (Q53–Q55)](#-fill-in-the-blank)
5. [Answer Key & Explanations](#-answer-key--explanations)
6. [Score Tracker](#-score-tracker)

---

## 🔵 Multiple Choice — Single Answer

*Select the single best answer for each question.*

---

**Q1.** A network administrator needs to connect two separate IP subnets so they can communicate with each other. Which device is BEST suited for this task?

- A) Switch
- B) Hub
- C) **Router**
- D) Wireless access point

---

**Q2.** Which of the following devices operates at Layer 2 of the OSI model and uses MAC addresses to make forwarding decisions?

- A) Router
- B) Hub
- C) **Switch**
- D) Proxy server

---

**Q3.** A technician plugs a laptop into an older network device and notices that all other devices on the segment experience significant slowdowns whenever the laptop transfers large files. The device creates a single shared collision domain. Which device is MOST likely being used?

- A) Managed switch
- B) **Hub**
- C) Router
- D) Bridge

---

**Q4.** Which of the following BEST describes the primary function of a stateful firewall?

- A) It filters traffic based only on IP addresses and port numbers without tracking sessions
- B) **It tracks the state of active connections and makes filtering decisions based on connection state**
- C) It inspects application-layer payloads to identify threats
- D) It distributes incoming traffic across multiple servers

---

**Q5.** A security team wants to detect malicious traffic on the network but does NOT want to risk blocking legitimate traffic. Which solution is MOST appropriate?

- A) IPS deployed inline
- B) Next-Generation Firewall
- C) **IDS deployed out-of-band**
- D) UTM appliance

---

**Q6.** A company hosts a popular web application across five identical servers. They want to ensure no single server becomes overloaded. Which device should they deploy?

- A) Proxy server
- B) **Load balancer**
- C) Router
- D) IDS

---

**Q7.** Which of the following BEST describes how a forward proxy server functions?

- A) It protects backend servers by intercepting inbound internet requests on their behalf
- B) It distributes client requests across multiple servers
- C) **It intercepts client requests and forwards them to the internet on the client's behalf**
- D) It encrypts traffic between two network sites

---

**Q8.** A network engineer is configuring a device that will provide shared file storage to Windows clients using SMB and can be accessed directly over the corporate Ethernet network. Which storage technology is being configured?

- A) SAN
- B) **NAS**
- C) DAS
- D) iSCSI target

---

**Q9.** Which of the following storage technologies provides block-level access and is typically connected via iSCSI or Fibre Channel over a dedicated storage network?

- A) NAS
- B) **SAN**
- C) DAS
- D) RAID array

---

**Q10.** An engineer is deploying wireless access points throughout a corporate office. Which IEEE standard provides the fastest speeds and supports the 2.4 GHz, 5 GHz, AND 6 GHz frequency bands?

- A) 802.11ac (Wi-Fi 5)
- B) 802.11n (Wi-Fi 4)
- C) **802.11ax (Wi-Fi 6/6E)**
- D) 802.11a

---

**Q11.** A content provider wants to reduce latency for users around the world by caching video content at servers geographically close to their users. Which technology should they implement?

- A) Reverse proxy
- B) Load balancer
- C) **CDN**
- D) SAN

---

**Q12.** A remote employee needs to securely access the corporate network over the public internet. The company wants all traffic encrypted during transit. Which solution BEST meets this requirement?

- A) VLAN
- B) **VPN**
- C) NAT
- D) DHCP

---

**Q13.** A network engineer is configuring QoS policies on a router. VoIP traffic must be given the highest priority. Which traffic marking standard operates at Layer 3 and is used to classify QoS priority?

- A) 802.1p (CoS)
- B) **DSCP**
- C) 802.1Q
- D) STP

---

**Q14.** A packet is sent from a host with an initial TTL of 64. The packet passes through 10 routers before reaching its destination. What is the TTL value when the packet arrives?

- A) 64
- B) 10
- C) 0
- D) **54**

---

**Q15.** Which of the following BEST describes the difference between an IDS and an IPS?

- A) An IDS blocks traffic; an IPS only generates alerts
- B) An IDS inspects Layer 7; an IPS inspects Layer 4 only
- C) **An IDS detects and alerts; an IPS detects and actively blocks**
- D) An IDS is host-based only; an IPS is network-based only

---

**Q16.** A switch receives a frame with a destination MAC address it does not recognize in its MAC address table. What action does the switch take?

- A) Drops the frame silently
- B) Sends the frame back to the sender
- C) **Floods the frame out all ports except the port it was received on**
- D) Forwards the frame to the default gateway

---

**Q17.** Which VPN protocol is considered legacy and insecure due to known vulnerabilities in its encryption implementation?

- A) OpenVPN
- B) IPsec/IKEv2
- C) WireGuard
- D) **PPTP**

---

**Q18.** A company's web servers are overwhelmed with HTTPS requests. An administrator wants to offload the SSL decryption process from the web servers to a dedicated device. Which feature of a load balancer handles this?

- A) Round-robin scheduling
- B) Sticky sessions
- C) **SSL/TLS termination**
- D) Health checking

---

**Q19.** Which of the following is a characteristic of a hub that makes it LESS preferable than a switch?

- A) Hubs operate at Layer 3 and are slower than switches
- B) Hubs require complex configuration to function
- C) **Hubs create a single collision domain shared by all connected devices**
- D) Hubs cannot support full-duplex connections because they use IP addressing

---

**Q20.** Which IPsec mode encrypts only the payload of the original IP packet and is typically used for end-to-end communications between two hosts?

- A) **Transport mode**
- B) Tunnel mode
- C) AH mode
- D) ESP mode

---

**Q21.** A network administrator wants to ensure that a specific client always connects to the same backend server when visiting the company's website. Which load balancing method achieves this?

- A) Round-robin
- B) Least connections
- C) **Sticky sessions / session persistence**
- D) Weighted distribution

---

**Q22.** At which OSI layer does a wireless access point primarily operate?

- A) Layer 3
- B) Layer 4
- C) **Layer 2**
- D) Layer 1 only

---

**Q23.** Which of the following statements about a reverse proxy is TRUE?

- A) It hides the identity of clients from web servers
- B) **It hides the identity of backend servers from external clients**
- C) It routes traffic between two different IP networks
- D) It provides wireless access to clients

---

**Q24.** A packet with TTL=1 arrives at a router. The router cannot forward it to the destination in one hop. What does the router do?

- A) Forwards the packet and decrements TTL to 0
- B) Returns the packet to the source without modification
- C) **Drops the packet and sends an ICMP "Time Exceeded" message to the source**
- D) Holds the packet until the TTL is reset

---

**Q25.** Which of the following BEST describes the function of a UTM (Unified Threat Management) appliance?

- A) It is a dedicated firewall with no other features
- B) It distributes traffic across multiple servers
- C) It provides only VPN and NAT functionality
- D) **It combines multiple security functions — firewall, IPS, antivirus, content filtering, and VPN — in one device**

---

**Q26.** A NAS device is being added to a corporate network. Which protocol would Windows clients use to access files stored on the NAS?

- A) iSCSI
- B) Fibre Channel
- C) **SMB (Server Message Block)**
- D) FTP

---

**Q27.** Which of the following BEST describes how a CDN reduces latency?

- A) It compresses all web traffic using advanced algorithms
- B) It blocks malicious requests before they reach the origin server
- C) **It caches content at geographically distributed edge servers closer to end users**
- D) It prioritizes web traffic using QoS policies

---

**Q28.** A network uses 802.11ac wireless access points. A new employee's laptop only supports 802.11n. Which of the following is TRUE?

- A) The laptop cannot connect to the network at all
- B) The laptop will connect but only at 802.11a speeds
- C) **The laptop will connect at 802.11n speeds — the AP is backward compatible**
- D) The laptop will connect at 802.11ac speeds automatically

---

**Q29.** Which of the following is a key difference between a managed switch and an unmanaged switch?

- A) Managed switches operate at Layer 3; unmanaged switches operate at Layer 2
- B) **Managed switches support VLANs, port security, and remote configuration; unmanaged switches are plug-and-play with no configuration options**
- C) Managed switches use MAC addresses; unmanaged switches use IP addresses
- D) Unmanaged switches support STP; managed switches do not

---

**Q30.** An administrator is configuring IPsec for a site-to-site VPN between two office locations. Which IPsec mode should they use?

- A) Transport mode
- B) **Tunnel mode**
- C) AH-only mode
- D) ESP-only mode

---

**Q31.** Which QoS marking standard operates at Layer 2 and is used on Ethernet frames to indicate traffic priority?

- A) DSCP
- B) **802.1p (CoS)**
- C) 802.1X
- D) MPLS

---

**Q32.** A network engineer runs `traceroute` to a remote server. The tool uses which IP header field to discover each router hop along the path?

- A) Protocol field
- B) Fragment offset
- C) **TTL (Time to Live)**
- D) ToS (Type of Service)

---

**Q33.** Which of the following BEST describes the function of STP (Spanning Tree Protocol) on a switch?

- A) It encrypts traffic between switches
- B) It assigns IP addresses to connected clients
- C) It prioritizes VoIP traffic over data traffic
- D) **It prevents Layer 2 switching loops in redundant network topologies**

---

**Q34.** Which of the following storage protocols transmits block-level storage commands over a standard IP/Ethernet network?

- A) SMB
- B) NFS
- C) Fibre Channel
- D) **iSCSI**

---

**Q35.** A company wants to implement the MOST secure current wireless security protocol for their enterprise network. Which should they choose?

- A) WEP
- B) WPA
- C) WPA2-Personal
- D) **WPA3-Enterprise**

---

## 🟡 Multiple Choice — Multiple Answer (Select ALL that apply)

*These questions may have 2 or more correct answers.*

---

**Q36.** Which of the following are TRUE about a network hub? *(Select TWO)*

- A) It uses MAC addresses to make intelligent forwarding decisions
- B) **It broadcasts all received traffic to every connected port**
- C) It supports full-duplex communications
- D) **It creates a single collision domain for all connected devices**
- E) It operates at Layer 2 of the OSI model

---

**Q37.** Which of the following are valid VPN protocols used to create secure tunnels? *(Select THREE)*

- A) PPTP (though considered insecure)
- B) **IPsec**
- C) **OpenVPN**
- D) SNMP
- E) **WireGuard**
- F) OSPF

---

**Q38.** Which of the following are features commonly found on a Next-Generation Firewall (NGFW)? *(Select THREE)*

- A) **Application-layer (Layer 7) traffic inspection**
- B) Layer 2 MAC address filtering only
- C) **Intrusion Prevention System (IPS) integration**
- D) **SSL/TLS traffic inspection and decryption**
- E) Storage area network management

---

**Q39.** Which of the following describe differences between NAS and SAN? *(Select TWO)*

- A) NAS uses block-level access; SAN uses file-level access
- B) **NAS uses file-level access via SMB or NFS over standard Ethernet**
- C) Both NAS and SAN require a dedicated Fibre Channel network
- D) **SAN uses block-level access via iSCSI or Fibre Channel over a dedicated storage network**
- E) NAS is only used in data centers; SAN is used in home networks

---

**Q40.** Which of the following are TRUE about load balancers? *(Select TWO)*

- A) Load balancers can only operate at Layer 4 of the OSI model
- B) **Load balancers can perform SSL/TLS termination to offload decryption from web servers**
- C) Load balancers assign IP addresses to servers dynamically
- D) **Load balancers perform health checks to remove failed servers from the pool**
- E) Load balancers replace the need for a firewall

---

**Q41.** Which of the following are TRUE about QoS? *(Select THREE)*

- A) QoS guarantees that all traffic is delivered at the same speed
- B) **QoS classifies and prioritizes traffic to prevent congestion from starving critical applications**
- C) **VoIP traffic is typically given the highest QoS priority due to its real-time sensitivity**
- D) **DSCP operates at Layer 3 to mark packets for QoS treatment**
- E) QoS is only configurable on wireless access points

---

**Q42.** Which of the following are TRUE about wireless access points? *(Select TWO)*

- A) A wireless AP operates at Layer 3 and requires an IP address to forward frames
- B) **A wireless AP bridges wireless clients to the wired network at Layer 2**
- C) A wireless AP and a wireless router are the same device with identical functions
- D) **A wireless AP can be managed centrally by a wireless controller in enterprise deployments**
- E) Wireless APs cannot support WPA3

---

**Q43.** Which of the following statements about TTL are TRUE? *(Select TWO)*

- A) TTL is a Layer 4 field found in the TCP header
- B) **TTL is a Layer 3 field in the IP header, decremented by 1 at each router hop**
- C) When TTL reaches 0, the packet is forwarded to the destination with a warning
- D) **When TTL reaches 0, the router drops the packet and sends an ICMP Time Exceeded message back to the source**
- E) The default TTL value is the same on all operating systems

---

**Q44.** A company is evaluating IDS vs IPS deployment. Which of the following statements are TRUE? *(Select TWO)*

- A) **An IDS is typically deployed out-of-band (passive tap) and cannot block traffic on its own**
- B) An IPS can only use signature-based detection, not anomaly-based
- C) **An IPS is deployed inline and can actively block malicious traffic in real time**
- D) IDS and IPS both require a dedicated Fibre Channel connection
- E) An IDS is always more effective than an IPS because it never causes false positives

---

**Q45.** Which of the following are TRUE about a CDN? *(Select TWO)*

- A) A CDN stores the origin server's database and processes dynamic content
- B) **A CDN caches static content at geographically distributed Points of Presence (PoPs)**
- C) A CDN increases latency for users far from the origin server
- D) **A CDN reduces load on the origin server by serving cached content from edge nodes**
- E) A CDN replaces the need for a web server entirely

---

## 🟠 Scenario-Based Questions

*Read each scenario carefully and select the BEST answer.*

---

**Q46.** A junior technician reports that users on a network segment complain that the network is slow whenever anyone runs a large file transfer. Checking the wiring closet, the technician discovers all devices are connected to a single 8-port device with no configuration interface. When a file transfer begins, a collision light flashes on all ports. Which device is causing the problem, and what should replace it?

- A) A router — it should be replaced with a switch
- B) A firewall — it should be replaced with a UTM
- C) **A hub — it should be replaced with a managed switch**
- D) A NAS — it should be replaced with a SAN

---

**Q47.** A company runs a high-traffic e-commerce website on three web servers. During peak shopping hours, one server frequently maxes out its CPU while the other two sit at 20% utilization. The load balancer is configured using round-robin. A network engineer wants to fix the imbalance so that servers receiving more requests get fewer new ones. Which load balancing algorithm should they switch to?

- A) IP hash
- B) Round-robin weighted
- C) **Least connections**
- D) Sticky sessions

---

**Q48.** An organization's security team is alerted that malware is beaconing out to an external IP address over port 443. The security team cannot determine which internal host is responsible because all HTTPS traffic appears encrypted in the firewall logs. Which device, properly configured, would allow the team to decrypt and inspect that traffic?

- A) IDS deployed in tap mode
- B) Standard stateful firewall
- C) Load balancer with SSL termination
- D) **Next-Generation Firewall with SSL/TLS inspection enabled**

---

**Q49.** A network administrator is designing storage for a database server that requires the absolute lowest possible latency and needs the operating system to treat the storage as a local hard drive. The storage will be shared among multiple servers in the data center. Which storage solution BEST meets these requirements?

- A) NAS using SMB
- B) NAS using NFS
- C) **SAN using iSCSI or Fibre Channel**
- D) A cloud-based object storage service

---

**Q50.** A video streaming company notices that users in Europe experience buffering when content is served from servers in the United States. Users in the US have no issues. The CTO wants to resolve the issue with minimal changes to the origin infrastructure. Which solution BEST addresses this?

- A) Deploy additional firewalls in Europe
- B) Increase the TTL value in DNS records
- C) Implement QoS policies to prioritize video traffic
- D) **Deploy a CDN with edge servers (PoPs) in Europe**

---

**Q51.** A company's VoIP system is experiencing call quality issues — users report choppy audio and dropped words during calls. The network engineer checks the router and sees that a large file backup job runs at the same time as business hours calls, consuming nearly all available bandwidth. Which technology should the engineer implement to resolve this?

- A) VPN
- B) STP
- C) **QoS with VoIP traffic given highest priority**
- D) IDS

---

**Q52.** A network security engineer is deploying a solution to protect internal servers from direct exposure to the internet. The solution should intercept all inbound requests, check them, and forward only legitimate traffic to the appropriate backend server — while hiding the backend server's real IP address from external clients. Which solution BEST fits this requirement?

- A) Forward proxy
- B) IDS
- C) NAS
- D) **Reverse proxy**

---

## 🟢 Fill in the Blank

*Complete each statement with the correct term.*

---

**Q53.** A ______________ is a network storage device that provides file-level access over a standard Ethernet network using protocols like SMB and NFS, while a ______________ provides block-level access over a dedicated storage fabric using iSCSI or Fibre Channel.

---

**Q54.** The ______________ field in an IPv4 packet header is decremented by one at each router hop, and when it reaches zero, the packet is dropped and an ICMP ______________ message is sent back to the source.

---

**Q55.** A ______________ proxy intercepts requests from internal clients heading to the internet, while a ______________ proxy sits in front of web servers and intercepts inbound requests from external clients on the servers' behalf.

---

---
---

# ✅ Answer Key & Explanations

> ⚠️ **Attempt all 55 questions before reading the answers!**

---

## Single Answer — Q1 through Q35

---

**Q1. Answer: C — Router**
> Routers operate at Layer 3 (Network) and connect separate IP subnets, making routing decisions based on IP addresses. Switches connect devices within the same subnet at Layer 2. Hubs are Layer 1 and have no routing capability.

---

**Q2. Answer: C — Switch**
> Switches operate at Layer 2 (Data Link) and build a MAC address table by learning source MAC addresses from incoming frames. They use this table to forward frames to the correct port. Routers use IP addresses (Layer 3). Hubs don't make forwarding decisions at all.

---

**Q3. Answer: B — Hub**
> A hub creates a single shared collision domain — all devices share the same bandwidth and any transmission from one device is sent to all others. Large file transfers consume the shared bandwidth and cause collisions, degrading performance for everyone. The absence of a configuration interface is also a hub characteristic.

---

**Q4. Answer: B — Tracks state of active connections**
> A stateful firewall maintains a state table that tracks the state of TCP/UDP sessions. It makes decisions based on whether traffic is part of an established, expected session — not just on static rules. Option A describes a stateless (packet-filtering) firewall. Option C describes an NGFW. Option D describes a load balancer.

---

**Q5. Answer: C — IDS deployed out-of-band**
> An IDS (Intrusion Detection System) is a passive device that monitors traffic and generates alerts without interfering with traffic flow. It cannot block traffic, which makes it ideal when the team wants visibility without the risk of blocking legitimate sessions. An IPS would block — but carries the risk of false positives disrupting traffic.

---

**Q6. Answer: B — Load balancer**
> A load balancer distributes incoming client requests across multiple servers to prevent any single server from being overwhelmed. This is its core function — ensuring even traffic distribution and high availability.

---

**Q7. Answer: C — Intercepts client requests and forwards them to the internet**
> A forward proxy sits between internal clients and the internet. Clients send requests to the proxy, which forwards them on their behalf — often for content filtering, caching, or anonymity. Option A describes a reverse proxy. Option B describes a load balancer. Option D describes a VPN.

---

**Q8. Answer: B — NAS**
> NAS (Network Attached Storage) provides file-level access over standard Ethernet using protocols like SMB (for Windows clients), NFS (for Linux/Unix), and AFP (for legacy macOS). It appears as a shared network drive. SAN provides block-level access over a dedicated storage network.

---

**Q9. Answer: B — SAN**
> A SAN (Storage Area Network) provides block-level storage access, making it appear to the operating system as a locally attached disk. It uses iSCSI (over IP/Ethernet) or Fibre Channel (over a dedicated fabric). NAS uses file-level access over standard Ethernet.

---

**Q10. Answer: C — 802.11ax (Wi-Fi 6/6E)**
> 802.11ax (Wi-Fi 6/6E) is the only standard that supports all three frequency bands: 2.4 GHz, 5 GHz, and 6 GHz (the 6 GHz band added in Wi-Fi 6E). 802.11ac (Wi-Fi 5) only uses 5 GHz. 802.11n uses 2.4 and 5 GHz. 802.11a uses only 5 GHz.

---

**Q11. Answer: C — CDN**
> A CDN (Content Delivery Network) caches content at geographically distributed Points of Presence (PoPs) close to users, reducing round-trip time and latency. A reverse proxy protects backend servers but doesn't distribute content globally. A load balancer distributes requests but doesn't cache geographically.

---

**Q12. Answer: B — VPN**
> A VPN (Virtual Private Network) creates an encrypted tunnel over the public internet, allowing remote users to securely access corporate resources as if they were on the local network. NAT translates addresses but doesn't encrypt. VLANs segment local networks. DHCP assigns IP addresses.

---

**Q13. Answer: B — DSCP**
> DSCP (Differentiated Services Code Point) is a Layer 3 mechanism that marks IP packet headers to indicate QoS priority. It replaces the older IP Precedence field. 802.1p (CoS) operates at Layer 2 for Ethernet frames. 802.1Q is for VLAN tagging. STP prevents switching loops.

---

**Q14. Answer: D — 54**
> TTL starts at 64 and is decremented by 1 at each router hop. After 10 hops: 64 − 10 = **54**. The packet is dropped only when TTL reaches 0. In this case, it reaches the destination before that happens.

---

**Q15. Answer: C — IDS detects and alerts; IPS detects and actively blocks**
> This is a critical exam distinction. An IDS is passive — it detects threats and generates alerts but does not block traffic. An IPS is active (inline) — it detects threats AND actively drops or blocks malicious packets in real time. Both can use signature-based and anomaly-based detection. Both can be host-based (HIDS/HIPS) or network-based (NIDS/NIPS).

---

**Q16. Answer: C — Floods the frame out all ports except the receiving port**
> When a switch receives a frame with an unknown destination MAC, it floods the frame out all ports except the one it was received on (this is called unknown unicast flooding). The correct device will respond, and the switch will then learn the MAC-to-port mapping and update its MAC address table. Dropping the frame would break connectivity.

---

**Q17. Answer: D — PPTP**
> PPTP (Point-to-Point Tunneling Protocol) is considered legacy and insecure due to serious weaknesses in its MS-CHAPv2 authentication and MPPE encryption. It is deprecated in favor of IPsec, OpenVPN, and WireGuard. This is a frequently tested exam point.

---

**Q18. Answer: C — SSL/TLS termination**
> SSL/TLS termination (also called SSL offloading) allows the load balancer to decrypt HTTPS traffic instead of the web servers, freeing up CPU resources on the servers. The load balancer then communicates with the backend servers over plain HTTP (or re-encrypts with a new TLS session).

---

**Q19. Answer: C — Single collision domain**
> Hubs create a single collision domain — all devices share the same medium and must take turns transmitting. Collisions are common and performance degrades significantly as devices are added. Hubs are Layer 1 devices (not Layer 3). They don't support full-duplex connections because collisions would prevent proper operation.

---

**Q20. Answer: A — Transport mode**
> IPsec Transport mode encrypts only the payload (data) of the original IP packet while leaving the original IP header intact. It is used for end-to-end encryption between two hosts. Tunnel mode (used for site-to-site VPNs) encapsulates and encrypts the entire original IP packet inside a new IP packet.

---

**Q21. Answer: C — Sticky sessions / session persistence**
> Sticky sessions (also called session persistence or affinity) ensure that requests from a specific client always go to the same backend server — important for applications that store session state locally on the server. Round-robin and least connections distribute requests without regard for which server a client previously connected to.

---

**Q22. Answer: C — Layer 2**
> A wireless access point primarily operates at Layer 2 (Data Link). It bridges wireless clients to the wired network at the MAC frame level. The AP itself may have an IP address for management purposes, but its core forwarding function is at Layer 2. (Note: some advanced APs can operate at Layer 3 for inter-VLAN routing, but the base answer for the exam is Layer 2.)

---

**Q23. Answer: B — It hides the identity of backend servers from external clients**
> A reverse proxy sits in front of web servers and intercepts inbound requests from the internet. External clients see only the proxy's IP address — the backend servers' real IPs are hidden. This improves security, enables load balancing, and allows SSL termination. Option A describes a forward proxy's effect on client anonymity.

---

**Q24. Answer: C — Drops the packet and sends ICMP Time Exceeded**
> When a router receives a packet with TTL=1, it decrements TTL to 0. Since it cannot forward a packet with TTL=0 (that would create a loop), it drops the packet and sends an ICMP "Time Exceeded" (Type 11) message back to the source. This is exactly how `traceroute` works — it exploits this behavior to map each hop.

---

**Q25. Answer: D — Combines multiple security functions in one device**
> A UTM (Unified Threat Management) appliance consolidates multiple security services into a single device: firewall, IPS, antivirus, content filtering, VPN, antispam, and more. It simplifies management but can become a single point of failure. It is popular in small-to-medium business environments.

---

**Q26. Answer: C — SMB**
> Windows clients use SMB (Server Message Block) to access shared files and printers on a NAS or Windows file server. SMB runs over TCP port 445. Linux/Unix clients use NFS. iSCSI and Fibre Channel are SAN protocols for block-level access, not file access.

---

**Q27. Answer: C — Caches content at geographically distributed edge servers**
> A CDN's core mechanism is geographic caching at edge nodes (PoPs). When a user requests content, it is served from the nearest edge server rather than the distant origin server. This dramatically reduces latency and round-trip time. CDNs do not primarily compress traffic, block attacks (though some CDNs have WAF features), or apply QoS.

---

**Q28. Answer: C — The laptop will connect at 802.11n speeds**
> IEEE 802.11 standards are backward compatible. An 802.11ac AP can communicate with 802.11n clients at 802.11n speeds. The laptop will connect successfully but at the lower 802.11n data rates, not 802.11ac speeds. The AP negotiates the highest mutually supported standard.

---

**Q29. Answer: B — Managed supports VLANs, port security, remote config; unmanaged is plug-and-play**
> Managed switches offer advanced features: VLAN configuration, port security (restricting by MAC), STP, SNMP monitoring, remote management (SSH/Telnet), QoS, and more. Unmanaged switches are plug-and-play with no configuration options — suitable for simple home/small office environments. Both operate at Layer 2.

---

**Q30. Answer: B — Tunnel mode**
> IPsec Tunnel mode encrypts the entire original IP packet (including its header) and encapsulates it inside a new IP packet with new source/destination IP addresses. This is used for site-to-site VPNs where traffic between two networks is routed through the internet. Transport mode is for host-to-host communications.

---

**Q31. Answer: B — 802.1p (CoS)**
> 802.1p (Class of Service) is a Layer 2 standard that adds a 3-bit priority field to 802.1Q VLAN-tagged Ethernet frames. It allows Layer 2 switches to prioritize traffic. DSCP is the Layer 3 equivalent used in IP packet headers. 802.1X is a port-based network access control standard. MPLS is a separate traffic engineering technology.

---

**Q32. Answer: C — TTL (Time to Live)**
> `traceroute` (or `tracert` on Windows) works by sending packets with incrementally increasing TTL values (starting at 1). Each router that decrements TTL to 0 sends back an ICMP Time Exceeded message, revealing its IP address. By incrementing TTL by 1 for each probe, traceroute maps every hop between source and destination.

---

**Q33. Answer: D — Prevents Layer 2 switching loops**
> STP (Spanning Tree Protocol — IEEE 802.1D) and its variants (RSTP 802.1w, MSTP 802.1s) prevent Layer 2 loops in redundant switch topologies by blocking redundant paths and electing a root bridge. Without STP, a loop would cause broadcast storms that bring down the network. STP has nothing to do with encryption, IP assignment, or QoS.

---

**Q34. Answer: D — iSCSI**
> iSCSI (Internet Small Computer System Interface) encapsulates SCSI block-level storage commands inside TCP/IP packets, allowing SAN storage to be transmitted over standard Ethernet networks. SMB and NFS are file-level protocols used by NAS. Fibre Channel is a dedicated physical SAN fabric, not an IP-based protocol.

---

**Q35. Answer: D — WPA3-Enterprise**
> WPA3 is the most current and secure wireless security standard. WPA3-Enterprise uses 192-bit encryption (CNSA suite) and individual authentication via 802.1X/RADIUS. WEP and WPA are deprecated with known vulnerabilities. WPA2-Personal uses a pre-shared key (PSK) which is less secure than certificate-based enterprise authentication.

---

## Multiple Answer — Q36 through Q45

---

**Q36. Answer: B — Broadcasts to every port, D — Single collision domain**
> Hubs operate at Layer 1 and have no intelligence — they simply repeat every received signal to all ports. This creates one large collision domain. They do NOT use MAC addresses (that's switches), do NOT support full-duplex (collisions prevent this), and operate at Layer 1, not Layer 2.

---

**Q37. Answer: A — PPTP, B — IPsec, C — OpenVPN, E — WireGuard**
> Wait — the question asks for THREE. The correct three are **IPsec, OpenVPN, and WireGuard** — the current and secure VPN protocols. PPTP is a VPN protocol but is considered insecure (not a recommended answer). SNMP is a network management protocol. OSPF is a routing protocol. On the exam, choose the three secure ones: IPsec, OpenVPN, WireGuard.

---

**Q38. Answer: A — L7 inspection, C — IPS integration, D — SSL/TLS inspection**
> NGFWs go beyond traditional firewalls by adding: deep packet inspection at Layer 7 (application awareness), built-in IPS for threat detection and blocking, and SSL/TLS inspection to decrypt and inspect encrypted traffic. MAC address filtering is a Layer 2 switch feature. SAN management is unrelated to firewalls.

---

**Q39. Answer: B — NAS = file-level over Ethernet, D — SAN = block-level over dedicated fabric**
> NAS provides file-level access (files and folders) over standard Ethernet using SMB or NFS. SAN provides block-level access (raw disk blocks) over a dedicated storage network using iSCSI or Fibre Channel. The options are inverted in A. Both NAS and SAN are used in enterprise and data center environments.

---

**Q40. Answer: B — SSL/TLS termination, D — Health checks**
> Load balancers can offload SSL/TLS decryption (SSL termination) from backend servers, reducing their CPU load. They also perform health checks — regularly probing servers and removing failed ones from the pool to ensure requests only go to healthy servers. Load balancers can operate at L4 OR L7 (not only L4). They don't assign IPs or replace firewalls.

---

**Q41. Answer: B — Classifies/prioritizes traffic, C — VoIP gets highest priority, D — DSCP is L3**
> QoS classifies traffic and prioritizes it so critical applications (especially VoIP) get bandwidth even under congestion. VoIP is real-time and extremely sensitive to delay/jitter, so it always gets highest priority. DSCP marks L3 IP packet headers for QoS treatment. QoS does NOT guarantee equal speed — it intentionally creates unequal treatment. It is configurable on routers, switches, and APs.

---

**Q42. Answer: B — Bridges wireless to wired at L2, D — Managed by wireless controller**
> A wireless AP bridges wireless clients to the wired network at Layer 2 using MAC addresses — it doesn't route at Layer 3. In enterprise deployments, multiple APs are managed centrally by a Wireless LAN Controller (WLC), which handles configuration, roaming, and RF management. An AP and a wireless router are NOT the same — a router also has routing and NAT functions. WPA3 is fully supported by modern APs.

---

**Q43. Answer: B — TTL is L3 in IP header decremented per hop, D — TTL=0 drops and sends ICMP**
> TTL is a field in the IPv4 header (Layer 3), not in TCP (Layer 4). Each router decrements it by 1. When it reaches 0, the router drops the packet and sends ICMP Type 11 (Time Exceeded) back to the source. The packet is NOT forwarded with a warning. Default TTL values DIFFER by OS: Windows=128, Linux/macOS=64, Cisco IOS=255.

---

**Q44. Answer: A — IDS is passive/out-of-band, C — IPS is inline and blocks**
> An IDS is deployed in tap/span mode (passive, out-of-band) — it sees a copy of traffic and can alert but cannot block. An IPS is deployed inline — all traffic flows through it, allowing it to drop malicious packets in real time. Both IDS and IPS can use signature AND anomaly-based detection. Neither requires Fibre Channel. IDS is not inherently more effective — IPS offers active protection at the cost of potential false-positive blocking.

---

**Q45. Answer: B — Caches static content at PoPs, D — Reduces origin server load**
> A CDN caches static content (images, videos, CSS, JavaScript) at distributed PoPs close to users. When a user requests cached content, it is served from the nearest edge node — reducing load on the origin server and lowering latency. CDNs do NOT process dynamic database content (that stays at the origin). They do NOT increase latency — they reduce it. They do NOT replace web servers.

---

## Scenario-Based — Q46 through Q52

---

**Q46. Answer: C — Hub — replace with a managed switch**
> The key clues: no configuration interface (unmanaged), collision lights on ALL ports (single collision domain), and performance degradation during file transfers. These all point to a hub. A managed switch eliminates the shared collision domain by giving each port its own collision domain, supports full-duplex, and allows VLANs, port security, and monitoring.

---

**Q47. Answer: C — Least connections**
> The problem is uneven server utilization — one server gets overwhelmed while others are idle. Round-robin distributes requests evenly by count but ignores server load. Least connections solves this by always routing new requests to the server with the fewest active connections, naturally balancing the load based on actual server activity. IP hash and sticky sessions would make the imbalance worse by binding clients to specific servers.

---

**Q48. Answer: D — NGFW with SSL/TLS inspection**
> Standard firewalls and IDS/IPS cannot inspect encrypted HTTPS traffic without decrypting it first. An NGFW with SSL/TLS inspection (also called SSL interception or HTTPS inspection) acts as a man-in-the-middle — decrypting traffic for inspection, then re-encrypting it before forwarding. This allows the team to inspect the beaconing traffic and identify the compromised host. A load balancer's SSL termination is for performance, not security inspection.

---

**Q49. Answer: C — SAN using iSCSI or Fibre Channel**
> The requirements — lowest latency, OS treats storage as local disk (block-level), shared among multiple servers — all point to a SAN. NAS provides file-level access (SMB/NFS), which adds overhead and doesn't present storage as a local disk. Cloud object storage introduces internet latency, which is the opposite of what's needed for a database requiring lowest possible latency.

---

**Q50. Answer: D — CDN with edge servers in Europe**
> The problem is geographic — users in Europe experience buffering because content must travel across the Atlantic from US servers. A CDN with PoPs (Points of Presence) in Europe solves this by caching content at European edge servers, dramatically reducing round-trip time. Firewalls don't reduce latency. Increasing DNS TTL affects caching but not delivery speed. QoS helps with congestion but not geographic distance.

---

**Q51. Answer: C — QoS with VoIP traffic given highest priority**
> The root cause is bandwidth contention — a backup job consumes bandwidth needed for VoIP calls. QoS solves this by classifying VoIP traffic and giving it highest priority in the router's queues, ensuring VoIP packets are forwarded before backup traffic. This guarantees the low latency, low jitter, and low packet loss that voice traffic requires for clear audio. VPN doesn't prioritize traffic. STP prevents switching loops. IDS detects threats.

---

**Q52. Answer: D — Reverse proxy**
> A reverse proxy sits in front of backend servers, intercepts all inbound requests from external clients, inspects them, and forwards legitimate ones to the appropriate server — all while hiding the real IP addresses and existence of backend servers from the internet. A forward proxy serves internal clients accessing the internet. An IDS detects threats but doesn't intercept or forward requests. NAS is a storage device.

---

## Fill in the Blank — Q53 through Q55

---

**Q53. Answer: NAS / SAN**
> A **NAS** (Network Attached Storage) provides file-level access over Ethernet using SMB/NFS. A **SAN** (Storage Area Network) provides block-level access over a dedicated storage fabric using iSCSI or Fibre Channel. The key exam distinction: NAS = files, SAN = blocks.

---

**Q54. Answer: TTL (Time to Live) / Time Exceeded**
> The **TTL** (Time to Live) field in the IPv4 header is decremented by 1 at each router hop. When it reaches 0, the router drops the packet and sends an ICMP **Time Exceeded** (Type 11) message back to the original source. Traceroute exploits this mechanism to discover each hop along a path.

---

**Q55. Answer: Forward / Reverse**
> A **forward** proxy intercepts outbound requests from internal clients heading to the internet (used for content filtering, caching, and anonymity). A **reverse** proxy intercepts inbound requests from external clients heading to backend servers (used for load balancing, SSL termination, and hiding server identity).

---

## 📊 Score Tracker

| Section | Total Q's | Your Score | Percentage | Status |
|---------|-----------|------------|------------|--------|
| Single Answer (Q1–Q35) | 35 | /35 | % | ⬜ |
| Multiple Answer (Q36–Q45) | 10 | /10 | % | ⬜ |
| Scenario-Based (Q46–Q52) | 7 | /7 | % | ⬜ |
| Fill in the Blank (Q53–Q55) | 3 | /3 | % | ⬜ |
| **TOTAL** | **55** | **/55** | **%** | ⬜ |

### Score Guide

| Score | Percentage | Readiness |
|-------|------------|-----------|
| 50–55 | 90–100% | ✅ Excellent — Chapter 2 mastered |
| 41–49 | 75–89% | 🟡 Good — review wrong answers and re-test |
| 33–40 | 60–74% | 🟠 Fair — revisit Chapter 2 notes and diagrams |
| Below 33 | < 60% | 🔴 Needs Work — re-read the chapter and retry |

### Topic Weakness Identifier

| If you missed… | Review this topic |
|----------------|-------------------|
| Q1–Q3, Q16, Q19, Q29 | Hub vs Switch vs Router fundamentals |
| Q4–Q5, Q15, Q25, Q38, Q44 | Firewall types and IDS vs IPS |
| Q6, Q18, Q21, Q40, Q47 | Load balancer features and algorithms |
| Q7, Q23, Q52, Q55 | Forward proxy vs reverse proxy |
| Q8–Q9, Q26, Q34, Q39, Q49, Q53 | NAS vs SAN |
| Q10, Q22, Q28, Q35, Q42 | Wireless AP and 802.11 standards |
| Q11, Q27, Q45, Q50 | CDN function and deployment |
| Q12, Q17, Q20, Q30, Q37 | VPN protocols and IPsec modes |
| Q13, Q31, Q41, Q51 | QoS, DSCP, and 802.1p |
| Q14, Q24, Q32, Q43, Q54 | TTL behavior and ICMP |

---

> 💡 **Study Tip:** Scenario questions (Q46–Q52) are the closest to real exam PBQs. If you missed any, re-read the scenario carefully and identify the key clues — the correct answer is always justified by specific details in the question, not general knowledge alone.

---

*📁 Part of the Network+ N10-009 Study Series | `Chapter-02-Networking-Appliances/practice-questions.md`*
