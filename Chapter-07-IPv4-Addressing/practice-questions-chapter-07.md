# 📝 Practice Questions — Chapter 7
### *IPv4 Addressing | Network+ N10-009 Study Series*

![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B%20N10--009-FF0000?style=for-the-badge&logo=comptia&logoColor=white)
![Chapter](https://img.shields.io/badge/Chapter-07%20IPv4%20Addressing-DC3545?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-60-28A745?style=for-the-badge)
![Difficulty](https://img.shields.io/badge/Difficulty-Mixed-FF6B35?style=for-the-badge)

> 📌 60 practice questions covering IPv4 address structure, address classes,
> public vs private addresses (RFC 1918), CIDR notation and subnetting,
> VLSM (Variable Length Subnet Masking), NAT/PAT, special-purpose addresses
> (APIPA, loopback, broadcast), and IPv4 address exhaustion concepts.
> Subnetting math is heavily tested — show your work on scratch paper!
> Answers and detailed explanations are at the bottom — attempt all questions first!

---

## 📑 Table of Contents

1. [Multiple Choice — Single Answer (Q1–Q38)](#-multiple-choice--single-answer)
2. [Multiple Choice — Multiple Answer (Q39–Q48)](#-multiple-choice--multiple-answer-select-all-that-apply)
3. [Scenario-Based Questions (Q49–Q56)](#-scenario-based-questions)
4. [Subnetting Math (Q57–Q60)](#-subnetting-math)
5. [Answer Key & Explanations](#-answer-key--explanations)
6. [Score Tracker](#-score-tracker)

---

## 🔵 Multiple Choice — Single Answer

*Select the single best answer for each question.*

---

**Q1.** How many bits make up an IPv4 address?

- A) 16
- B) 64
- C) 128
- D) **32**

---

**Q2.** An IPv4 address is divided into how many octets?

- A) 2
- B) **4**
- C) 6
- D) 8

---

**Q3.** What is the maximum decimal value of a single octet in an IPv4 address?

- A) 128
- B) 192
- C) **255**
- D) 256

---

**Q4.** Which IPv4 address class has a default subnet mask of 255.0.0.0 and uses the first octet range of 1–126?

- A) Class B
- B) Class C
- C) Class D
- D) **Class A**

---

**Q5.** Which IPv4 address class uses a first octet range of 128–191 and has a default subnet mask of 255.255.0.0?

- A) Class A
- B) **Class B**
- C) Class C
- D) Class E

---

**Q6.** Which address class has a default subnet mask of 255.255.255.0 and a first octet range of 192–223?

- A) Class A
- B) Class B
- C) Class D
- D) **Class C**

---

**Q7.** Which IPv4 address class is reserved for multicast traffic and uses the first octet range of 224–239?

- A) Class B
- B) Class C
- C) **Class D**
- D) Class E

---

**Q8.** Which of the following is a private IPv4 address range as defined by RFC 1918?

- A) 172.32.0.0/12
- B) 192.169.0.0/16
- C) **10.0.0.0/8**
- D) 11.0.0.0/8

---

**Q9.** Which RFC 1918 private address range covers 172.16.0.0 through 172.31.255.255?

- A) /8
- B) **172.16.0.0/12**
- C) 172.16.0.0/16
- D) 172.0.0.0/8

---

**Q10.** A workstation displays an IP address of 169.254.45.23. No other configuration is shown. What is the MOST likely cause?

- A) The device was assigned this address by a DHCP server on the network
- B) **The device failed to receive a DHCP lease and self-assigned an APIPA address**
- C) The administrator manually configured this address for remote management
- D) The device is using a Class B private address

---

**Q11.** Which special IPv4 address is used by a host to refer to itself (loopback) for testing the TCP/IP stack?

- A) 0.0.0.0
- B) 255.255.255.255
- C) 169.254.0.1
- D) **127.0.0.1**

---

**Q12.** What does the IPv4 address 0.0.0.0 represent in networking?

- A) The loopback address
- B) The APIPA address
- C) The limited broadcast address
- D) **An unspecified or default route — represents "this network" or "all networks" depending on context**

---

**Q13.** Which address is used to send a broadcast to all hosts on the local network segment regardless of subnet?

- A) 127.0.0.1
- B) 0.0.0.0
- C) 192.168.1.255
- D) **255.255.255.255**

---

**Q14.** What is the CIDR notation for a subnet mask of 255.255.255.0?

- A) /16
- B) /20
- C) /28
- D) **/24**

---

**Q15.** What is the subnet mask in dotted-decimal notation for a /20 CIDR prefix?

- A) 255.255.0.0
- B) 255.255.240.0
- C) **255.255.240.0**
- D) 255.255.248.0

---

**Q16.** How many usable host addresses are available in a /28 subnet?

- A) 16
- B) 30
- C) **14**
- D) 12

---

**Q17.** How many usable host addresses are in a /27 subnet?

- A) 32
- B) 62
- C) **30**
- D) 28

---

**Q18.** A network engineer is given the address block 192.168.10.0/24 and needs to create subnets that each support at least 50 hosts. Which subnet mask should they use?

- A) /27 (30 hosts)
- B) /28 (14 hosts)
- C) **/26 (62 usable hosts)**
- D) /25 (126 usable hosts — works but wastes addresses)

---

**Q19.** What is the network address of the subnet that contains the host 192.168.5.100/26?

- A) 192.168.5.0
- B) 192.168.5.128
- C) **192.168.5.64**
- D) 192.168.5.32

---

**Q20.** What is the broadcast address of the subnet 192.168.5.64/26?

- A) 192.168.5.126
- B) 192.168.5.128
- C) 192.168.5.64
- D) **192.168.5.127**

---

**Q21.** What is the valid host range for the subnet 192.168.5.64/26?

- A) 192.168.5.64 – 192.168.5.127
- B) 192.168.5.65 – 192.168.5.128
- C) **192.168.5.65 – 192.168.5.126**
- D) 192.168.5.64 – 192.168.5.126

---

**Q22.** How many /26 subnets can be created from a single /24 network?

- A) 2
- B) 6
- C) **4**
- D) 8

---

**Q23.** A host has IP address 172.16.50.200 and subnet mask 255.255.255.0. What is the network address?

- A) 172.16.0.0
- B) 172.16.50.255
- C) 172.16.50.200
- D) **172.16.50.0**

---

**Q24.** Which of the following IP addresses is in the same /28 subnet as 10.0.0.20?

- A) 10.0.0.15
- B) 10.0.0.32
- C) **10.0.0.17**
- D) 10.0.0.31

---

**Q25.** What is the block size of a /29 subnet?

- A) 4
- B) 16
- C) **8**
- D) 32

---

**Q26.** How many /30 subnets can be created from a /27 network?

- A) 4
- B) **8**
- C) 16
- D) 2

---

**Q27.** A /30 subnet is commonly used for which network purpose?

- A) Connecting large numbers of hosts in an enterprise LAN
- B) Creating a DMZ with 30 server slots
- C) **Point-to-point WAN links between two routers — it provides exactly 2 usable host addresses**
- D) VLAN segmentation in a three-tier architecture

---

**Q28.** What type of NAT translates multiple internal private IP addresses to a single public IP address by using different port numbers to track connections?

- A) Static NAT (one-to-one)
- B) Dynamic NAT (pool-based)
- C) **PAT (Port Address Translation) / NAT Overload**
- D) Destination NAT (DNAT)

---

**Q29.** Which of the following BEST describes static NAT?

- A) It dynamically assigns public IPs from a pool to outbound connections
- B) It uses port numbers to map multiple private IPs to a single public IP
- C) **It creates a permanent one-to-one mapping between a specific private IP and a specific public IP**
- D) It translates broadcast addresses to unicast addresses

---

**Q30.** A company has a pool of 10 public IP addresses and 200 internal hosts. They configure the router to randomly assign a public IP from the pool to outbound connections — once the pool is exhausted, new connections are blocked. Which NAT type is this?

- A) Static NAT
- B) PAT
- C) **Dynamic NAT**
- D) NAT64

---

**Q31.** What is the wildcard mask for a /24 subnet?

- A) 255.255.255.0
- B) 0.0.255.255
- C) **0.0.0.255**
- D) 255.0.0.0

---

**Q32.** How is a wildcard mask calculated from a subnet mask?

- A) Subtract the subnet mask from 0.0.0.0
- B) **Subtract the subnet mask from 255.255.255.255**
- C) Add 1 to the last octet of the subnet mask
- D) Invert the first two octets of the subnet mask

---

**Q33.** Which of the following represents the CIDR notation for the address block 10.0.0.0 with subnet mask 255.255.0.0?

- A) 10.0.0.0/8
- B) 10.0.0.0/24
- C) **10.0.0.0/16**
- D) 10.0.0.0/12

---

**Q34.** VLSM (Variable Length Subnet Masking) allows a network administrator to do which of the following?

- A) Use the same subnet mask for all subnets regardless of host requirements
- B) **Divide an address space into subnets of different sizes to match the actual host count requirements of each segment**
- C) Automatically assign IP addresses to hosts using DHCP
- D) Convert IPv4 addresses to IPv6 format

---

**Q35.** In VLSM design, which subnet should be allocated FIRST to use the address space most efficiently?

- A) The smallest subnet
- B) The subnet with the fewest hosts
- C) A /30 subnet for WAN links
- D) **The largest subnet — allocate the biggest requirement first, then progressively smaller subnets**

---

**Q36.** What is the purpose of a subnet mask?

- A) To identify the MAC address of the default gateway
- B) **To distinguish the network portion of an IP address from the host portion, enabling the device to determine if a destination is on the local network or requires routing**
- C) To encrypt IP packets before transmission
- D) To assign dynamic IP addresses to hosts

---

**Q37.** A host with IP 192.168.1.50/24 wants to communicate with 192.168.2.75/24. What must happen for this communication to succeed?

- A) The two hosts communicate directly at Layer 2 since they are in the same Class C range
- B) The switch forwards the frame based on MAC address lookup
- C) **The packet must be forwarded to the default gateway (router) since the hosts are on different subnets — 192.168.1.0 and 192.168.2.0**
- D) ARP broadcasts find the destination host directly

---

**Q38.** Which address represents the network address (NOT a valid host address) for the subnet 10.10.10.128/25?

- A) 10.10.10.129
- B) 10.10.10.254
- C) 10.10.10.255
- D) **10.10.10.128**

---

## 🟡 Multiple Choice — Multiple Answer (Select ALL that apply)

*These questions may have 2 or more correct answers.*

---

**Q39.** Which of the following are RFC 1918 private IPv4 address ranges? *(Select THREE)*

- A) **10.0.0.0/8 (10.0.0.0 – 10.255.255.255)**
- B) 172.15.0.0/12
- C) **172.16.0.0/12 (172.16.0.0 – 172.31.255.255)**
- D) **192.168.0.0/16 (192.168.0.0 – 192.168.255.255)**
- E) 192.169.0.0/16

---

**Q40.** Which of the following are TRUE about APIPA (Automatic Private IP Addressing)? *(Select TWO)*

- A) APIPA addresses are routable on the internet
- B) **APIPA addresses fall in the 169.254.0.0/16 range**
- C) APIPA is assigned by the DHCP server when no addresses are available
- D) **APIPA is self-assigned by a host when it cannot reach a DHCP server — it is a link-local address used only for local communication**
- E) APIPA provides internet connectivity as a fallback

---

**Q41.** Which of the following are TRUE about NAT (Network Address Translation)? *(Select TWO)*

- A) NAT eliminates the need for routing between subnets
- B) **NAT conserves public IPv4 addresses by allowing multiple internal hosts to share one or more public IP addresses**
- C) NAT provides encryption for data in transit
- D) **PAT (Port Address Translation) is the most common form of NAT, using port numbers to track multiple simultaneous connections from different internal hosts through a single public IP**
- E) NAT replaces the need for DHCP in small networks

---

**Q42.** Which of the following are TRUE about CIDR (Classless Inter-Domain Routing)? *(Select TWO)*

- A) CIDR requires address classes (A, B, C) to determine the subnet mask
- B) **CIDR uses a prefix length notation (/n) to specify how many bits represent the network portion of the address**
- C) CIDR can only be used with IPv6 addresses
- D) **CIDR allows more efficient allocation of IP address space by supporting subnets of any size — not limited to classful /8, /16, or /24 boundaries**
- E) CIDR requires all subnets in a network to use the same prefix length

---

**Q43.** Which of the following IPv4 addresses are special-purpose and NOT valid for regular host assignment? *(Select THREE)*

- A) 192.168.1.100
- B) **127.0.0.1 (loopback)**
- C) 10.0.0.50
- D) **255.255.255.255 (limited broadcast)**
- E) **169.254.100.50 (APIPA — link-local, not routable)**

---

**Q44.** A network administrator is subnetting 172.16.0.0/16 into /24 subnets. Which of the following statements are TRUE? *(Select TWO)*

- A) Each /24 subnet provides 256 usable host addresses
- B) **Each /24 subnet provides 254 usable host addresses (256 − 2 for network and broadcast)**
- C) A total of 256 /24 subnets can be created from a /16 network
- D) **A total of 256 /24 subnets can be created from a /16 — borrowing 8 bits from the host portion gives 2^8 = 256 subnets**
- E) Each /24 subnet requires a /16 router to function

---

**Q45.** Which of the following are TRUE about the subnet mask 255.255.255.192? *(Select TWO)*

- A) This mask is equivalent to /28
- B) **This mask is equivalent to /26**
- C) Each subnet created with this mask supports 64 usable hosts
- D) **Each subnet supports 62 usable hosts (2^6 − 2 = 62)**
- E) The block size for this mask is 128

---

**Q46.** Which of the following are TRUE about the default gateway in IPv4 networking? *(Select TWO)*

- A) The default gateway must be on a different subnet than the host
- B) **The default gateway is the router interface on the same subnet as the host that forwards traffic destined for remote networks**
- C) A host can function without a default gateway if it only needs local communication
- D) **Without a correctly configured default gateway, a host can only communicate with devices on its own local subnet**
- E) The default gateway is always the highest usable IP in the subnet

---

**Q47.** Which of the following are TRUE about classful vs classless addressing? *(Select TWO)*

- A) Classful addressing allows subnets of any size within a major network
- B) **Classful addressing assigns fixed subnet masks based on the first octet of the IP address (/8 for A, /16 for B, /24 for C)**
- C) Classless addressing requires all subnets to use the same prefix length
- D) **Classless addressing (CIDR) allows variable-length subnet masks (VLSM) — subnets can be any size regardless of the address class**
- E) Modern routers only support classful routing protocols

---

**Q48.** A network has the address 192.168.10.0/24. A technician wants to create four equal subnets. Which of the following are TRUE? *(Select TWO)*

- A) Each subnet should use a /24 mask
- B) **Borrowing 2 bits from the host portion creates 4 subnets (2² = 4), resulting in a /26 mask**
- C) Each subnet will have 30 usable host addresses
- D) **Each /26 subnet from a /24 provides 62 usable host addresses (2^6 − 2 = 62)**
- E) The four subnets would start at .0, .64, .96, and .128

---

## 🟠 Scenario-Based Questions

*Read each scenario carefully and select the BEST answer.*

---

**Q49.** A help desk technician receives a call from a user who cannot access the internet or any shared drives on the network. The technician asks for the user's IP address and the user reports 169.254.15.43. What is the MOST likely cause and BEST first step?

- A) The IP address indicates a Class B private address — check routing tables
- B) The user's computer has a virus that changed the IP address to avoid detection
- C) **The IP address is an APIPA address — the computer failed to get a lease from the DHCP server. The technician should verify the DHCP server is reachable, check the network cable, and try releasing and renewing the IP (ipconfig /release and /renew on Windows)**
- D) The user needs to manually configure a static IP in the 169.254.0.0 range

---

**Q50.** A network engineer is given the block 192.168.20.0/24 and must create subnets for the following departments:
- HR: 45 hosts
- Finance: 25 hosts
- IT: 12 hosts
- WAN link between routers: 2 hosts

Using VLSM, which subnet mask should be assigned to the HR department to efficiently accommodate 45 hosts?

- A) /24 — provides 254 hosts (too large)
- B) /27 — provides 30 hosts (too small)
- C) **/26 — provides 62 usable hosts (smallest mask that fits 45 hosts)**
- D) /25 — provides 126 hosts (works but wastes too many addresses)

---

**Q51.** An administrator notices that users on subnet 10.10.1.0/24 can reach each other but cannot reach servers on 10.10.2.0/24. Both subnets are on the same building floor connected to the same distribution switch. What is the MOST likely cause?

- A) The cables between the two subnets are faulty
- B) The hosts have incorrect subnet masks
- C) STP has blocked the uplink between the two subnets
- D) **Inter-VLAN routing is not configured — the distribution layer switch or router does not have routing enabled between the two /24 subnets**

---

**Q52.** A small business has 5 computers sharing a single broadband internet connection. The ISP provides one public IP address (203.0.113.45). All five computers can browse the internet simultaneously. Which technology makes this possible?

- A) Static NAT — each computer gets its own public IP mapping
- B) Dynamic NAT — computers take turns using the public IP
- C) **PAT (Port Address Translation) — all five computers share the single public IP; the router uses unique port numbers to track each computer's outbound connections**
- D) DHCP — the router assigns individual public IPs to each computer

---

**Q53.** A network administrator is designing IP addressing for a new office. The site will have:
- 3 VLANs: VLAN 10 (Sales, 60 hosts), VLAN 20 (Engineering, 25 hosts), VLAN 30 (Management, 10 hosts)
- The address space assigned is 192.168.50.0/24

Starting from .0, which subnet mask should be used for VLAN 10 (60 hosts) to most efficiently use the address space?

- A) /24 — provides 254 hosts
- B) /27 — provides 30 hosts (not enough)
- C) **/26 — provides 62 usable hosts, smallest mask that fits 60 hosts**
- D) /25 — provides 126 hosts (wastes too many addresses)

---

**Q54.** A security audit reveals that a company's web server has the internal IP address 10.0.0.100 and is reachable from the internet at 203.0.113.200. Each time an internet user connects to 203.0.113.200, the firewall forwards the connection to 10.0.0.100. Which type of NAT is configured?

- A) PAT (Port Address Translation)
- B) Dynamic NAT
- C) NAT64
- D) **Static NAT (one-to-one mapping between a fixed private IP and a fixed public IP)**

---

**Q55.** A network engineer receives a trouble ticket: "Host A (10.0.0.50/24) cannot ping Host B (10.0.0.200/24) even though they are on the same switch." The engineer checks and finds Host A has a subnet mask of 255.255.255.0 and Host B has a subnet mask of 255.255.0.0. What is the problem?

- A) Both hosts are on different VLANs and need inter-VLAN routing
- B) The switch has MAC address table overflow and cannot forward frames
- C) **Host B's incorrect subnet mask (255.255.0.0 /16 instead of /24) causes it to believe it is on a different, larger subnet — causing an ARP and routing mismatch. Both hosts must use the same subnet mask (/24) to communicate correctly**
- D) The two hosts need a crossover cable to communicate directly

---

**Q56.** A company is expanding and needs to allocate IP addressing for a new WAN link between its headquarters router and a remote branch router. The network team wants to use the minimum number of IP addresses possible. Which subnet should they use?

- A) /27 — provides 30 usable hosts (too many)
- B) /28 — provides 14 usable hosts (too many)
- C) /29 — provides 6 usable hosts (still too many for 2 devices)
- D) **/30 — provides exactly 2 usable host addresses, perfect for a point-to-point router link**

---

## 🟢 Subnetting Math

*Show your work on scratch paper. These questions mirror the calculation-style questions on the N10-009.*

---

**Q57.** A host has IP address **172.16.45.178** with subnet mask **255.255.255.224 (/27)**.

Determine:
- A) The network address
- B) The broadcast address
- C) The valid host range
- D) The number of usable hosts

Select the answer that correctly identifies ALL four values:

- A) Network: 172.16.45.160 | Broadcast: 172.16.45.191 | Hosts: .161–.190 | Count: 30
- B) Network: 172.16.45.160 | Broadcast: 172.16.45.192 | Hosts: .161–.191 | Count: 30
- C) Network: 172.16.45.128 | Broadcast: 172.16.45.191 | Hosts: .129–.190 | Count: 62
- D) **Network: 172.16.45.160 | Broadcast: 172.16.45.191 | Hosts: .161–.190 | Count: 30**

---

**Q58.** You are given the network **10.0.0.0/8** and need to create subnets that each support **500 hosts**. Which prefix length should you use, and how many such subnets can be created from the /8?

- A) /23 — 510 usable hosts | 512 subnets
- B) **/23 — 510 usable hosts | 512 subnets from a /8 (borrowing 15 bits for network)**
- C) /24 — 254 usable hosts | too small for 500 hosts
- D) /22 — 1022 usable hosts | correct hosts but wastes addresses

*Which answer correctly describes the prefix and justifies the subnet count?*

- A) /23 with 510 hosts — 128 subnets possible
- B) /24 with 254 hosts — doesn't meet 500 host requirement
- C) **/23 with 510 usable hosts — 2^15 = 32,768 /23 subnets fit inside a /8**
- D) /22 with 1022 hosts — meets requirement but is less efficient

---

**Q59.** A network administrator needs to subnet **192.168.100.0/24** for a company with the following requirements using VLSM:

- Dept A: 100 hosts
- Dept B: 50 hosts
- Dept C: 25 hosts
- Dept D: 10 hosts

Allocating from the beginning of the address space (starting at .0), which of the following VLSM allocations is CORRECT?

- A) Dept A: /25 (.0–.127) | Dept B: /26 (.128–.191) | Dept C: /27 (.192–.223) | Dept D: /28 (.224–.239)
- B) Dept A: /26 (.0–.63) | Dept B: /27 (.64–.95) | Dept C: /28 (.96–.111) | Dept D: /29 (.112–.119)
- C) Dept A: /24 (.0–.255) — allocates entire space to one dept
- D) **Dept A: /25 (.0–.127, 126 hosts) | Dept B: /26 (.128–.191, 62 hosts) | Dept C: /27 (.192–.223, 30 hosts) | Dept D: /28 (.224–.239, 14 hosts)**

---

**Q60.** Two hosts are compared:

- Host X: IP 192.168.30.130, Mask 255.255.255.128 (/25)
- Host Y: IP 192.168.30.200, Mask 255.255.255.128 (/25)

Are Host X and Host Y on the same subnet? What are their respective network addresses?

- A) Same subnet — both are in 192.168.30.0/25
- B) Different subnets — Host X is in 192.168.30.0/25 and Host Y is in 192.168.30.192/25
- C) **Different subnets — Host X is in 192.168.30.128/25 (range .128–.255) and Host Y is also in 192.168.30.128/25 — WAIT, recalculate: block size = 128; subnets: .0–.127 and .128–.255. Host X (.130) and Host Y (.200) are BOTH in the .128 subnet — same subnet**
- D) **Same subnet — Host X (.130) and Host Y (.200) are both in 192.168.30.128/25 (valid host range .129–.254)**

---

---
---

# ✅ Answer Key & Explanations

> ⚠️ **Attempt all 60 questions before reading the answers!**

---

## Single Answer — Q1 through Q38

---

**Q1. Answer: D — 32 bits**
> IPv4 addresses are 32 bits long, written as four 8-bit octets in dotted-decimal notation (e.g., 192.168.1.1). IPv6 addresses are 128 bits. MAC addresses are 48 bits. The 32-bit structure limits IPv4 to approximately 4.3 billion unique addresses (2³²), which led to address exhaustion and the need for NAT and IPv6.

---

**Q2. Answer: B — 4 octets**
> An IPv4 address consists of four octets (groups of 8 bits), separated by dots. Each octet ranges from 0 to 255 in decimal (00000000 to 11111111 in binary). Example: 192.168.10.1 = four octets: 192 | 168 | 10 | 1. The total is 4 × 8 = 32 bits.

---

**Q3. Answer: C — 255**
> An 8-bit octet can represent values from 0 (00000000) to 255 (11111111). 255 = 128+64+32+16+8+4+2+1 = all 8 bits set to 1. The value 256 requires 9 bits and is NOT a valid octet value. Subnet mask octets are always one of: 0, 128, 192, 224, 240, 248, 252, 254, or 255.

---

**Q4. Answer: D — Class A**
> Class A: first octet 1–126 (127 reserved for loopback), default mask /8 (255.0.0.0), 8 network bits and 24 host bits, supports ~16.7 million hosts per network. Originally allocated to large organizations and governments. Note: 0.x.x.x is reserved; 127.x.x.x is loopback. Class A private range: 10.0.0.0/8.

---

**Q5. Answer: B — Class B**
> Class B: first octet 128–191, default mask /16 (255.255.0.0), 16 network bits and 16 host bits, supports up to 65,534 hosts per network. Designed for medium to large organizations. Class B private range: 172.16.0.0 through 172.31.255.255 (172.16.0.0/12).

---

**Q6. Answer: D — Class C**
> Class C: first octet 192–223, default mask /24 (255.255.255.0), 24 network bits and 8 host bits, supports 254 usable hosts per network. Most common class for small networks. Class C private range: 192.168.0.0/16 (192.168.0.0 through 192.168.255.255).

---

**Q7. Answer: C — Class D**
> Class D: first octet 224–239, reserved exclusively for multicast group addresses. Multicast allows one sender to reach multiple receivers simultaneously. Examples: 224.0.0.5 (OSPF all routers), 224.0.0.9 (RIP v2 routers), 239.x.x.x (organization-local multicast). Class D addresses are never assigned to individual hosts.

---

**Q8. Answer: C — 10.0.0.0/8**
> RFC 1918 defines three private IPv4 address ranges NOT routable on the internet: 10.0.0.0/8 (Class A private), 172.16.0.0/12 (Class B private), 192.168.0.0/16 (Class C private). Distractor: 172.32.0.0/12 is incorrect — the correct range starts at 172.16.0.0 and goes to 172.31.255.255. 11.0.0.0/8 is a public address space. 192.169.0.0 is NOT private.

---

**Q9. Answer: B — 172.16.0.0/12**
> The Class B private range is 172.16.0.0/12, covering 172.16.0.0 through 172.31.255.255. The /12 prefix means the first 12 bits are fixed (172.16 in the first two octets — but only the first 4 bits of the second octet are fixed). This gives 172.16.0.0 through 172.31.255.255 (the second octet ranges from 16 to 31). A common exam trap is 172.32.0.0 — that is OUTSIDE the private range.

---

**Q10. Answer: B — APIPA — DHCP failure**
> APIPA (Automatic Private IP Addressing) addresses fall in 169.254.0.0/16 (169.254.0.1 through 169.254.255.254). A Windows/macOS host automatically self-assigns an APIPA address when it cannot reach a DHCP server. APIPA addresses are link-local — NOT routable beyond the local network segment. A host with an APIPA address cannot access the internet or other subnets. Troubleshooting steps: check DHCP server, verify network cable, run `ipconfig /release` and `/renew`.

---

**Q11. Answer: D — 127.0.0.1**
> The loopback address 127.0.0.1 (or any address in 127.0.0.0/8) is used by a host to communicate with itself — testing the local TCP/IP stack without sending traffic on the network. If a ping to 127.0.0.1 fails, the TCP/IP stack itself is broken (not a network connectivity issue). The loopback address never leaves the host's network interface.

---

**Q12. Answer: D — Unspecified / default route**
> 0.0.0.0 has multiple context-dependent meanings: (1) As a source address — a host that has no IP yet (used during DHCP Discover), (2) In a routing table (0.0.0.0/0) — the default route ("send anything with no more specific match here"), (3) As a bind address — a server listening on all available interfaces. It does NOT represent the loopback (127.0.0.1) or a broadcast.

---

**Q13. Answer: D — 255.255.255.255**
> 255.255.255.255 is the limited broadcast address — when a host sends to this address, the packet is delivered to all hosts on the local network segment. Routers do NOT forward limited broadcasts. It is used by DHCP Discover (client has no IP, so it broadcasts to 255.255.255.255 to find a DHCP server). 192.168.1.255 would be the directed broadcast for the 192.168.1.0/24 subnet — but also not forwarded by routers.

---

**Q14. Answer: D — /24**
> Converting 255.255.255.0 to binary: 11111111.11111111.11111111.00000000 = 24 ones = /24. CIDR prefix length = number of consecutive 1-bits from left to right in the subnet mask. Key conversions: 255.0.0.0 = /8, 255.255.0.0 = /16, 255.255.255.0 = /24, 255.255.255.128 = /25, 255.255.255.192 = /26, 255.255.255.224 = /27, 255.255.255.240 = /28, 255.255.255.248 = /29, 255.255.255.252 = /30.

---

**Q15. Answer: B/C — 255.255.240.0**
> /20 = 20 consecutive 1-bits. First two octets are all 1s (255.255). The third octet: 20 − 16 = 4 bits set in the third octet = 11110000 = 128+64+32+16 = 240. Fourth octet = 0. Result: 255.255.240.0. Block size in third octet = 256 − 240 = 16. Subnets increment by 16 in the third octet: 0, 16, 32, 48... Note: options B and C both show 255.255.240.0 — the answer is 255.255.240.0.

---

**Q16. Answer: C — 14 usable hosts**
> /28: host bits = 32 − 28 = 4 bits. Total addresses = 2⁴ = 16. Usable hosts = 16 − 2 = **14** (subtract network address and broadcast address). Block size = 16. A /28 is often used for small network segments like server clusters or printer pools. Never answer 16 — you MUST subtract 2 for network and broadcast.

---

**Q17. Answer: C — 30 usable hosts**
> /27: host bits = 32 − 27 = 5 bits. Total addresses = 2⁵ = 32. Usable hosts = 32 − 2 = **30**. Block size = 32. /27 subnets in a /24: 256 ÷ 32 = 8 subnets. Common use: small departments of 10–30 hosts. The 30-host capacity is a frequently tested value — memorize: /27 = 30 hosts.

---

**Q18. Answer: C — /26**
> Requirements: at least 50 hosts per subnet. /27 = 30 hosts (not enough). /26 = 62 hosts (sufficient — 2⁶ − 2 = 62). /25 = 126 hosts (works, but wastes 76 addresses). For the exam, choose the SMALLEST subnet that accommodates the requirement. /26 is the most efficient choice that satisfies "at least 50 hosts."

---

**Q19. Answer: C — 192.168.5.64**
> Finding the network address for 192.168.5.100/26: Block size = 256 − 192 = 64. Subnet multiples: 0, 64, 128, 192. Host .100 falls between 64 and 128 → **Network address = 192.168.5.64**. Method: find the largest multiple of the block size that is ≤ the host octet. 64 ≤ 100 < 128, so the network is .64.

---

**Q20. Answer: D — 192.168.5.127**
> Broadcast = next subnet − 1. Next subnet after .64 = .64 + 64 = .128. Broadcast = .128 − 1 = **192.168.5.127**. Alternatively: broadcast = network address + (block size − 1) = .64 + 63 = .127. The broadcast address is always the last address in the subnet range.

---

**Q21. Answer: C — 192.168.5.65 through 192.168.5.126**
> Valid host range = (Network address + 1) through (Broadcast address − 1). Network = .64, Broadcast = .127. Host range = **.65 through .126**. This provides 62 usable addresses (2⁶ − 2). Never include the network address (.64) or broadcast (.127) as valid host addresses.

---

**Q22. Answer: C — 4 subnets**
> Creating /26 subnets from a /24: bits borrowed = 26 − 24 = 2 bits. Number of subnets = 2² = **4**. The four /26 subnets from 192.168.5.0/24: 192.168.5.0/26 (.0–.63), 192.168.5.64/26 (.64–.127), 192.168.5.128/26 (.128–.191), 192.168.5.192/26 (.192–.255). Each provides 62 usable hosts. Total: 4 × 62 = 248 usable host addresses from the original /24's 254.

---

**Q23. Answer: D — 172.16.50.0**
> For 172.16.50.200 with mask 255.255.255.0 (/24): the network portion is the first three octets (24 bits = 3 octets). The host portion is the last octet (.200). Network address = host portion set to all zeros = **172.16.50.0**. The .0 network address is never assigned to a host. With a /24, the entire third octet identifies the subnet.

---

**Q24. Answer: C — 10.0.0.17**
> Finding the /28 subnet for 10.0.0.20: Block size = 256 − 240 = 16. Subnet multiples: 0, 16, 32... 10.0.0.20 falls in the 10.0.0.16/28 subnet (range: .16–.31, hosts .17–.30, broadcast .31). Checking the options: 10.0.0.15 is in the .0 subnet (.0–.15). 10.0.0.17 is in the .16 subnet ✓. 10.0.0.32 is the next subnet. 10.0.0.31 is the broadcast of the .16 subnet (NOT a usable host). Answer: **10.0.0.17**.

---

**Q25. Answer: C — 8**
> Block size = 256 − subnet mask interesting octet value. /29 mask = 255.255.255.248. Block size = 256 − 248 = **8**. /29 provides: 8 total addresses, 6 usable hosts. The block size tells you the increment between subnet network addresses: 0, 8, 16, 24, 32... Know all block sizes: /25=128, /26=64, /27=32, /28=16, /29=8, /30=4.

---

**Q26. Answer: B — 8 subnets**
> /27 has 32 addresses per subnet. /30 has 4 addresses per subnet. Number of /30s from one /27 = 32 ÷ 4 = **8**. Alternatively: bits borrowed from /27 to /30 = 3 bits. 2³ = 8 subnets. Each /30 provides 2 usable hosts — ideal for WAN point-to-point links.

---

**Q27. Answer: C — Point-to-point WAN links**
> /30 provides exactly 4 addresses: 1 network, 2 usable hosts, 1 broadcast. With only 2 usable addresses, /30 is the perfect choice for point-to-point links between two routers — one address for each router interface. Using a /24 or /29 for a WAN link wastes addresses. /31 (2 addresses, per RFC 3021) is also valid for point-to-point links but is less commonly tested on the N10-009.

---

**Q28. Answer: C — PAT (Port Address Translation) / NAT Overload**
> PAT (also called NAT Overload or NAPT) is the most common form of NAT. It allows hundreds or thousands of internal hosts to share a SINGLE public IP address by using different source port numbers for each connection. The router's NAT table maps: internal IP:port ↔ public IP:unique port. When the response returns, the router reverses the translation. This is how home routers enable all devices to share one broadband connection.

---

**Q29. Answer: C — Permanent one-to-one private-to-public mapping**
> Static NAT creates a fixed, permanent mapping between one specific internal IP and one specific public IP. Used for: servers that must be consistently reachable from the internet (web servers, mail servers, VPN concentrators). Traffic destined for the public IP is always forwarded to the mapped private IP. Static NAT requires one public IP per mapped internal device — it does NOT conserve public IPs.

---

**Q30. Answer: C — Dynamic NAT**
> Dynamic NAT assigns public IPs from a pre-configured pool to outbound connections on a first-come, first-served basis. When a public IP from the pool is used, it is reserved for that connection. If all pool addresses are in use, additional outbound connections fail (connection refused). Dynamic NAT still requires one public IP per active connection — it conserves IPs by reusing them when sessions end, but is limited by pool size. PAT solves this completely by using port multiplexing.

---

**Q31. Answer: C — 0.0.0.255**
> Wildcard mask for /24 = 255.255.255.255 − 255.255.255.0 = **0.0.0.255**. Wildcard masks invert the subnet mask: 0 bits = match exactly, 1 bits = ignore (any value). Wildcard masks are used in ACLs and routing protocols (OSPF, EIGRP). For /24: the first three octets must match exactly (0.0.0) and the last octet can be anything (255 = ignore all 8 bits).

---

**Q32. Answer: B — Subtract the subnet mask from 255.255.255.255**
> Wildcard mask = 255.255.255.255 − subnet mask. Examples: /24 (255.255.255.0) → wildcard = 0.0.0.255. /26 (255.255.255.192) → wildcard = 0.0.0.63. /28 (255.255.255.240) → wildcard = 0.0.0.15. /30 (255.255.255.252) → wildcard = 0.0.0.3. The pattern: block size − 1 = last octet of the wildcard mask.

---

**Q33. Answer: C — 10.0.0.0/16**
> Converting 255.255.0.0 to CIDR: count the 1-bits = 16 ones. The full CIDR notation for the address 10.0.0.0 with mask 255.255.0.0 is **10.0.0.0/16**. Note: this is not the same as 10.0.0.0/8 (which has mask 255.0.0.0) or 10.0.0.0/24 (mask 255.255.255.0). The /16 notation means the first 16 bits identify the network.

---

**Q34. Answer: B — Subnets of different sizes to match actual host counts**
> VLSM (Variable Length Subnet Masking) allows each subnet to have its own prefix length, sized appropriately for its actual host count. Without VLSM, all subnets must use the same mask — wasting addresses (e.g., using /24 for a 2-host WAN link wastes 252 addresses). With VLSM: use /26 for 50 hosts, /27 for 25 hosts, /29 for 5 hosts, /30 for WAN links — efficiently using the address space.

---

**Q35. Answer: D — Largest subnet first**
> VLSM design rule: allocate the LARGEST subnet requirement first, then progressively smaller ones. Reason: large subnets require alignment on large boundaries. If you allocate small subnets first, you may create fragmentation that prevents fitting a large subnet. Example: for 192.168.1.0/24 with requirements of 100, 50, 25, 10 hosts — allocate /25 for 100 hosts first (.0–.127), then /26 for 50 hosts (.128–.191), then /27 for 25 (.192–.223), then /28 for 10 (.224–.239).

---

**Q36. Answer: B — Distinguishes network from host portion**
> The subnet mask defines which bits of an IPv4 address represent the network (consecutive 1-bits from the left) and which represent the host (consecutive 0-bits on the right). A device performs a bitwise AND operation between its IP address and subnet mask to determine its network address. It then compares the result to the destination's network to decide: same network = forward directly at Layer 2; different network = send to default gateway.

---

**Q37. Answer: C — Packet must go to the default gateway**
> 192.168.1.50/24 is in the 192.168.1.0/24 network. 192.168.2.75/24 is in the 192.168.2.0/24 network. Different network addresses = different subnets. A Layer 2 switch cannot route between subnets — it can only forward within a subnet based on MAC addresses. The packet must be sent to the default gateway (router) which knows how to reach the 192.168.2.0/24 subnet. This is why default gateway configuration is mandatory for inter-subnet communication.

---

**Q38. Answer: D — 10.10.10.128**
> For 10.10.10.128/25: block size = 128. The /25 creates two subnets: 10.10.10.0/25 (hosts .1–.126, broadcast .127) and **10.10.10.128/25** (hosts .129–.254, broadcast .255). 10.10.10.128 is the network address of the second subnet — it cannot be assigned to a host. Valid hosts in this subnet: .129 through .254. The network address is always the lowest address in the subnet range.

---

## Multiple Answer — Q39 through Q48

---

**Q39. Answer: A — 10.0.0.0/8, C — 172.16.0.0/12, D — 192.168.0.0/16**
> RFC 1918 private ranges: Class A: 10.0.0.0–10.255.255.255 (/8), Class B: 172.16.0.0–172.31.255.255 (/12), Class C: 192.168.0.0–192.168.255.255 (/16). Common traps: 172.15.0.0 is outside the range (starts at 172.16). 172.32.0.0 is outside the range (ends at 172.31). 192.169.0.0 is NOT private. 11.0.0.0 is a public address. Memorize all three ranges exactly — they are guaranteed on the exam.

---

**Q40. Answer: B — 169.254.0.0/16 range, D — Self-assigned when DHCP fails, link-local only**
> APIPA (RFC 3927): Range = 169.254.0.0/16 (169.254.0.1–169.254.255.254). Triggered by: Windows/macOS/Linux host cannot reach DHCP server after timeout. Result: host self-assigns an address in this range using ARP to verify uniqueness. Characteristics: NOT internet-routable, NOT forwarded by routers, only usable for communication within the same local network segment. Seeing a 169.254.x.x address = DHCP server unreachable. APIPA is NOT assigned by the DHCP server (that would be a regular DHCP lease).

---

**Q41. Answer: B — Conserves public IPv4 addresses, D — PAT uses ports to track multiple connections**
> NAT benefits: (1) IP conservation — allows thousands of private hosts to share one or a few public IPs, (2) Security — hides internal network topology from external observers, (3) Flexibility — internal addressing can change without affecting external visibility. NAT does NOT provide encryption (that's VPN/TLS). NAT does NOT replace routing (inter-subnet routing still requires a router). NAT does NOT replace DHCP (internal hosts still need IP assignment).

---

**Q42. Answer: B — Prefix length notation (/n), D — Efficient allocation without classful boundaries**
> CIDR (RFC 1519) introduced two revolutionary concepts: (1) Variable-length prefix notation (/n) — replaced rigid classful masks, allowing any prefix length from /1 to /32, (2) Route aggregation (supernetting) — multiple networks can be summarized as one CIDR block, reducing routing table size. CIDR broke the constraint that Class A must use /8, Class B must use /16, Class C must use /24. CIDR applies to both IPv4 and IPv6. VLSM (variable subnet sizes within a network) is enabled by CIDR.

---

**Q43. Answer: B — 127.0.0.1, D — 255.255.255.255, E — 169.254.100.50**
> Non-assignable special addresses: 127.x.x.x = loopback (reserved for localhost testing), 255.255.255.255 = limited broadcast (not a host address), 169.254.x.x = APIPA link-local (self-assigned, not a manually configured host address), 0.0.0.0 = unspecified. Valid host addresses include private ranges (10.x.x.x, 172.16–31.x.x, 192.168.x.x) and public addresses. The network address and broadcast address of any subnet are also not valid host addresses.

---

**Q44. Answer: B — 254 usable hosts per /24, D — 256 total /24 subnets from /16**
> Subnetting /16 into /24: Host bits borrowed = 24 − 16 = 8 bits. Subnets created = 2⁸ = 256 /24 subnets. Each /24 has 8 host bits: 2⁸ = 256 total addresses, 256 − 2 = 254 usable hosts. The 256 subnets would be 172.16.0.0/24, 172.16.1.0/24, 172.16.2.0/24 ... 172.16.255.0/24. Option C says 256 subnets — that IS correct. Option A says 256 usable hosts — that is WRONG (should be 254). Option D correctly states 256 subnets.

---

**Q45. Answer: B — Equivalent to /26, D — 62 usable hosts**
> 255.255.255.192 in binary: 11111111.11111111.11111111.11000000 = 26 ones = **/26**. Host bits = 32 − 26 = 6 bits. Total addresses = 2⁶ = 64. Usable hosts = 64 − 2 = **62**. Block size = 256 − 192 = 64. Common distractor: 255.255.255.240 = /28 (14 hosts). Know each mask value and its /prefix and host count.

---

**Q46. Answer: B — Router interface on same subnet forwards remote traffic, D — Without gateway can only reach local subnet**
> Default gateway requirements: (1) Must be on the SAME subnet as the host (host can reach it directly at Layer 2), (2) Is the router interface that connects the local subnet to other networks, (3) Without a gateway — the host can ONLY communicate with devices on its local subnet; all traffic to other networks is dropped. The gateway is NOT always the highest IP in the subnet — it can be any valid host address (commonly .1 or .254 by convention, but this is not a rule).

---

**Q47. Answer: B — Classful uses fixed masks, D — Classless allows variable masks**
> Classful addressing (original IPv4 design): The subnet mask is determined solely by the first octet of the address. No flexibility within a class. Classless addressing (CIDR/VLSM): Any prefix length can be used with any address block. Subnets within the same major network can have different sizes (VLSM). This enables efficient address utilization. Modern routers all support classless routing — classful routing protocols (RIPv1, IGRP) are obsolete.

---

**Q48. Answer: B — Borrowing 2 bits creates 4 subnets (/26), D — Each /26 gives 62 usable hosts**
> Subnetting /24 into 4 equal subnets: bits borrowed = log₂(4) = 2 bits. New prefix = /24 + 2 = /26. Block size = 64. Four subnets: .0–.63, .64–.127, .128–.191, .192–.255. Each /26: 2⁶ = 64 total, 64 − 2 = 62 usable hosts. Option E says subnets start at .0, .64, .96, .128 — .96 is WRONG (should be .128). Correct starts: .0, .64, .128, .192.

---

## Scenario-Based — Q49 through Q56

---

**Q49. Answer: C — APIPA address; DHCP server unreachable**
> 169.254.x.x = APIPA = DHCP failure. The computer self-assigned this address because it couldn't reach the DHCP server. APIPA only allows link-local communication — no internet, no cross-subnet services. Troubleshooting: (1) Check physical connection (cable, switch port link light), (2) Verify DHCP server is running and reachable, (3) Run `ipconfig /release` then `ipconfig /renew` on Windows, (4) Check for DHCP scope exhaustion (no available leases). This is a classic and frequently tested scenario.

---

**Q50. Answer: C — /26 for HR (45 hosts)**
> VLSM allocation for HR (45 hosts): /27 = 30 hosts (not enough), /26 = 62 hosts (sufficient, smallest mask that fits 45), /25 = 126 hosts (too large, wastes 81 addresses). The rule: choose the smallest subnet that satisfies the requirement. /26 is the answer. Full VLSM allocation from 192.168.20.0/24: HR /26 (.0–.63), Finance /27 (.64–.95), IT /28 (.96–.111), WAN /30 (.112–.115).

---

**Q51. Answer: D — Inter-VLAN routing not configured**
> Both subnets (10.10.1.0/24 and 10.10.2.0/24) are different networks. Even on the same physical switch, they cannot communicate at Layer 2 — a router or Layer 3 switch must route between them. The most common cause of this scenario in a switched environment is: (1) VLANs are correctly configured but the SVI (Switch Virtual Interface) for one or both VLANs is missing on the Layer 3 switch, or (2) IP routing is not enabled on the Layer 3 switch (`ip routing` command on Cisco). The switch correctly isolates the subnets by VLAN — the fix is configuring inter-VLAN routing.

---

**Q52. Answer: C — PAT**
> One public IP + five simultaneous users = PAT (Port Address Translation). The router maintains a NAT translation table: each internal host's connection gets a unique source port number on the public IP side. When the response arrives, the router uses the port number to determine which internal host should receive it. This is the default behavior of virtually all home and SOHO routers. Static NAT would require 5 public IPs. Dynamic NAT from a pool of 1 IP would only allow 1 user at a time. DHCP assigns private IPs — it doesn't provide internet access by itself.

---

**Q53. Answer: C — /26 for VLAN 10**
> VLAN 10 needs 60 hosts. /26 provides 62 usable hosts (2⁶ − 2 = 62) — smallest mask that fits. /27 = 30 hosts (not enough). /25 = 126 hosts (works but wastes 66 addresses). Following VLSM largest-first: VLAN 10 /26: 192.168.50.0 – .63 (62 hosts), VLAN 20 /27: 192.168.50.64 – .95 (30 hosts), VLAN 30 /28: 192.168.50.96 – .111 (14 hosts). Efficient VLSM allocation leaves 192.168.50.112 – .255 for future use.

---

**Q54. Answer: D — Static NAT**
> The key identifying feature: one fixed internal IP (10.0.0.100) permanently mapped to one fixed public IP (203.0.113.200). Every inbound connection to the public IP is always forwarded to the same private IP. This is static NAT — a permanent one-to-one mapping. PAT would use a single public IP for multiple internal hosts using port numbers. Dynamic NAT uses an IP pool without permanent mappings. This static NAT pattern is commonly used for web servers, mail servers, and VPN concentrators that must be consistently reachable.

---

**Q55. Answer: C — Mismatched subnet masks cause routing/ARP failure**
> With different subnet masks, the two hosts calculate different network addresses for the same IP space. Host A (/24) thinks 10.0.0.200 is on its local network (same /24 subnet) and sends ARP. Host B (/16) thinks it is on a much larger network (10.0.0.0/16) and may ARP differently. The fundamental problem: both hosts must agree on the subnet mask to correctly determine whether a destination is local or remote. The fix: configure both hosts with the same correct mask (/24 = 255.255.255.0). Mismatched masks cause subtle connectivity failures that are hard to diagnose without checking IP configuration on both ends.

---

**Q56. Answer: D — /30**
> WAN links between two routers require exactly 2 usable host addresses (one per router interface). /30 = 4 total addresses − 2 (network + broadcast) = **2 usable hosts**. It is the perfect, most efficient choice for point-to-point router links. /29 = 6 usable hosts (wastes 4). /28 = 14 usable (wastes 12). /31 (RFC 3021) = 2 usable with no network/broadcast (special case, less common on exams). For the N10-009: WAN link = /30 is the expected answer.

---

## Subnetting Math — Q57 through Q60

---

**Q57. Answer: D — Network: 172.16.45.160 | Broadcast: 172.16.45.191 | Hosts: .161–.190 | Count: 30**

**Work:**
- Mask 255.255.255.224 = /27. Block size = 256 − 224 = 32.
- Subnet multiples of 32: 0, 32, 64, 96, 128, **160**, 192...
- Host .178 falls between 160 and 192 → Network = **172.16.45.160**
- Broadcast = 160 + 32 − 1 = **172.16.45.191**
- Host range = **172.16.45.161 – 172.16.45.190**
- Usable hosts = 2⁵ − 2 = 32 − 2 = **30**

---

**Q58. Answer: C — /23 with 510 usable hosts — 32,768 /23 subnets from a /8**

**Work:**
- Need ≥ 500 hosts. Host bits needed: 2ⁿ − 2 ≥ 500 → n = 9 bits (2⁹ = 512, 512 − 2 = 510 ✓).
- n = 8 bits → 254 hosts (not enough). n = 9 bits → 510 hosts ✓.
- Prefix length = 32 − 9 = **/23**.
- Mask = 255.255.254.0. Block size in third octet = 2.
- Number of /23 subnets from /8: bits borrowed = 23 − 8 = 15 bits. 2¹⁵ = **32,768 subnets**.

---

**Q59. Answer: D — Dept A: /25 | Dept B: /26 | Dept C: /27 | Dept D: /28**

**Work — VLSM largest first:**
- Dept A (100 hosts): /25 = 126 hosts ✓. Network: 192.168.100.**0**/25, range: .0–.127.
- Dept B (50 hosts): /26 = 62 hosts ✓. Network: 192.168.100.**128**/26, range: .128–.191.
- Dept C (25 hosts): /27 = 30 hosts ✓. Network: 192.168.100.**192**/27, range: .192–.223.
- Dept D (10 hosts): /28 = 14 hosts ✓. Network: 192.168.100.**224**/28, range: .224–.239.

Remaining: .240–.255 available for future use.

---

**Q60. Answer: D — Same subnet — both hosts are in 192.168.30.128/25**

**Work:**
- Mask 255.255.255.128 = /25. Block size = 128.
- Two subnets from 192.168.30.0/24: **Subnet 1**: .0–.127 (hosts .1–.126) | **Subnet 2**: .128–.255 (hosts .129–.254).
- Host X = 192.168.30.**130** → falls in .128–.255 → Subnet 2 (192.168.30.128/25) ✓
- Host Y = 192.168.30.**200** → falls in .128–.255 → Subnet 2 (192.168.30.128/25) ✓
- **Both hosts are in the SAME subnet (192.168.30.128/25)**. They can communicate directly at Layer 2 without a router.

---

## 📊 Score Tracker

| Section | Total Q's | Your Score | Percentage | Status |
|---------|-----------|------------|------------|--------|
| Single Answer (Q1–Q38) | 38 | /38 | % | ⬜ |
| Multiple Answer (Q39–Q48) | 10 | /10 | % | ⬜ |
| Scenario-Based (Q49–Q56) | 8 | /8 | % | ⬜ |
| Subnetting Math (Q57–Q60) | 4 | /4 | % | ⬜ |
| **TOTAL** | **60** | **/60** | **%** | ⬜ |

### Score Guide

| Score | Percentage | Readiness |
|-------|------------|-----------|
| 54–60 | 90–100% | ✅ Excellent — Chapter 7 mastered |
| 45–53 | 75–89% | 🟡 Good — review wrong answers and re-test |
| 36–44 | 60–74% | 🟠 Fair — practice subnetting daily and re-test |
| Below 36 | < 60% | 🔴 Needs Work — study subnetting cheat sheet and retry |

### Topic Weakness Identifier

| If you missed… | Review this topic |
|----------------|-------------------|
| Q1–Q3 | IPv4 address structure — bits, octets, max value |
| Q4–Q7 | IPv4 address classes A, B, C, D |
| Q8–Q9, Q39 | RFC 1918 private address ranges |
| Q10, Q40, Q49 | APIPA — 169.254.0.0/16, DHCP failure |
| Q11 | Loopback address 127.0.0.1 |
| Q12–Q13 | Special addresses — 0.0.0.0 and 255.255.255.255 |
| Q14–Q15, Q33, Q42 | CIDR notation and prefix-to-mask conversion |
| Q16–Q18, Q22, Q44–Q45, Q48 | Subnet host count and subnet creation math |
| Q19–Q21, Q24, Q57, Q60 | Network/broadcast/host range calculation |
| Q25–Q26, Q58 | Block size and subnet counting |
| Q27, Q56 | /30 for WAN point-to-point links |
| Q28–Q30, Q41, Q52, Q54 | NAT types — Static, Dynamic, PAT |
| Q31–Q32 | Wildcard masks |
| Q34–Q35, Q50, Q59 | VLSM design — largest-first allocation |
| Q36–Q37, Q46, Q51, Q55 | Subnet mask function and default gateway |
| Q38 | Network address identification |
| Q47 | Classful vs classless addressing |

---

> 💡 **Exam Day Tip:** Subnetting questions are time-sensitive. Before the exam starts,
> write your block size table on scratch paper: /25=128, /26=64, /27=32, /28=16,
> /29=8, /30=4. Then for any IP+mask question: (1) find block size, (2) find the
> multiple of block size ≤ host octet = network address, (3) add block size − 1
> for broadcast, (4) host range is network+1 to broadcast−1. With practice,
> each subnetting question should take under 60 seconds.

---

*📁 Part of the Network+ N10-009 Study Series | `Chapter-07-IP-Addressing/practice-questions.md`*
