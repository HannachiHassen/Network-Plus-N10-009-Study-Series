# 📝 Practice Questions — Chapter 6
### *Network Topologies, Architectures & Types | Network+ N10-009 Study Series*

![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B%20N10--009-FF0000?style=for-the-badge&logo=comptia&logoColor=white)
![Chapter](https://img.shields.io/badge/Chapter-06%20Topologies%2C%20Architectures%20%26%20Types-8B1A9D?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-55-28A745?style=for-the-badge)
![Difficulty](https://img.shields.io/badge/Difficulty-Mixed-FF6B35?style=for-the-badge)

> 📌 55 practice questions covering physical and logical topologies (star, bus, ring, mesh,
> hybrid), network types (LAN, WAN, MAN, PAN, CAN, SAN, WLAN), three-tier architecture
> (core, distribution, access), spine-leaf architecture, Software-Defined Networking (SDN),
> SOHO network design, high availability and redundancy concepts, and network segmentation.
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

**Q1.** Which network topology connects all devices to a single central device (such as a switch), making it the most common physical topology in modern LANs?

- A) Bus
- B) Ring
- C) **Star**
- D) Mesh

---

**Q2.** In which physical topology does every device connect to every other device directly, providing maximum redundancy but at significant cabling cost?

- A) Star
- B) Ring
- C) Bus
- D) **Full mesh**

---

**Q3.** A company's network uses a topology where each device connects to at least two other devices, providing redundancy without requiring every device to connect to every other. Which topology is this?

- A) Full mesh
- B) Star
- C) **Partial mesh**
- D) Bus

---

**Q4.** Which legacy topology connected all devices to a single shared cable segment, where a break in the cable would bring down the entire network?

- A) Star
- B) Ring
- C) **Bus**
- D) Mesh

---

**Q5.** Which network topology passes data in a unidirectional or bidirectional circle, where each device connects to exactly two neighbors? A single break in a unidirectional ring can bring down the network.

- A) Bus
- B) Star
- C) **Ring**
- D) Full mesh

---

**Q6.** A topology that combines two or more different topology types into a single network is called:

- A) Full mesh
- B) Point-to-point
- C) **Hybrid**
- D) Extended star

---

**Q7.** What is the difference between a physical topology and a logical topology?

- A) Physical topology describes IP addressing; logical topology describes cabling
- B) **Physical topology describes how devices are physically cabled and connected; logical topology describes how data flows through the network regardless of physical layout**
- C) Physical topology is used only in WAN environments; logical topology is used in LANs
- D) They are the same concept described from different vendor perspectives

---

**Q8.** A network that spans a single building, campus, or small geographic area — typically owned and managed by a single organization — is classified as which network type?

- A) WAN
- B) MAN
- C) **LAN**
- D) CAN

---

**Q9.** Which network type typically spans a city or metropolitan area and is often provided by a telecommunications carrier or ISP to connect multiple LANs within the same geographic region?

- A) LAN
- B) **MAN**
- C) WAN
- D) PAN

---

**Q10.** Which network type spans large geographic distances — across countries or continents — and is typically composed of multiple interconnected LANs connected via leased lines, MPLS, or the internet?

- A) MAN
- B) LAN
- C) CAN
- D) **WAN**

---

**Q11.** A network that covers a small personal area — typically within 10 meters of a person — and uses technologies like Bluetooth, NFC, or USB is classified as:

- A) LAN
- B) WLAN
- C) **PAN**
- D) MAN

---

**Q12.** Which network type connects buildings and facilities across a college campus or business campus, spanning more than a single building but less than a metropolitan area?

- A) LAN
- B) MAN
- C) WAN
- D) **CAN**

---

**Q13.** In the three-tier hierarchical network architecture, which layer is responsible for high-speed backbone connectivity and connects the entire network together — handling inter-VLAN routing and connecting to the WAN?

- A) Access layer
- B) Distribution layer
- C) **Core layer**
- D) Aggregation layer

---

**Q14.** In the three-tier hierarchical architecture, which layer connects end-user devices (workstations, printers, IP phones) to the network and handles port security, DHCP snooping, and PoE?

- A) Core layer
- B) Distribution layer
- C) **Access layer**
- D) Aggregation layer

---

**Q15.** In the three-tier hierarchical architecture, which layer sits between the core and access layers, handles policy enforcement, inter-VLAN routing, and aggregates traffic from access switches before sending it to the core?

- A) Access layer
- B) **Distribution layer**
- C) Core layer
- D) Collapsed core layer

---

**Q16.** A small company with fewer than 100 employees deploys a single layer of switches directly connected to the core router, eliminating the separate distribution layer. This simplified design is called:

- A) Three-tier architecture
- B) **Collapsed core (two-tier) architecture**
- C) Spine-leaf architecture
- D) Full mesh topology

---

**Q17.** Which modern data center network architecture uses a two-tier design with high-speed spine switches interconnecting all leaf switches — ensuring every leaf switch is exactly two hops from any other leaf switch?

- A) Three-tier hierarchical
- B) Collapsed core
- C) **Spine-leaf architecture**
- D) Bus topology

---

**Q18.** Which of the following is a key advantage of spine-leaf architecture over traditional three-tier architecture in data centers?

- A) Spine-leaf uses fewer cables and is cheaper to deploy
- B) Spine-leaf relies on Spanning Tree Protocol to prevent loops
- C) Spine-leaf requires all servers to connect directly to spine switches
- D) **Spine-leaf provides predictable, consistent latency because all traffic travels the same number of hops (two hops maximum between any two endpoints)**

---

**Q19.** In a spine-leaf architecture, which rule governs the connection between spine and leaf switches?

- A) Each leaf switch connects only to one spine switch for redundancy
- B) Spine switches connect to all other spine switches
- C) **Each leaf switch connects to every spine switch, and spine switches do not connect to each other — traffic always goes leaf → spine → leaf**
- D) Leaf switches connect only to servers, never to other leaf switches

---

**Q20.** Which technology separates the control plane (network intelligence/routing decisions) from the data plane (packet forwarding), allowing network behavior to be programmatically controlled from a centralized software controller?

- A) VLAN
- B) STP
- C) **SDN (Software-Defined Networking)**
- D) OSPF

---

**Q21.** In SDN architecture, which component is responsible for making routing and forwarding decisions for the entire network and communicating those decisions to network devices?

- A) Data plane
- B) Southbound API
- C) **SDN controller (control plane)**
- D) Northbound API

---

**Q22.** In SDN, which API allows the SDN controller to communicate downward to network devices (switches and routers) to program their forwarding tables?

- A) Northbound API
- B) East-West API
- C) **Southbound API**
- D) Hypervisor API

---

**Q23.** A home or small office network that includes a router, wireless access point, and a small switch — all managed by one person without enterprise-grade equipment — is classified as which type of deployment?

- A) Enterprise LAN
- B) Data center network
- C) **SOHO (Small Office/Home Office)**
- D) Campus area network

---

**Q24.** Which redundancy concept involves deploying two or more network devices that can take over each other's function automatically if one fails, ensuring continuous network operation?

- A) Load balancing
- B) QoS prioritization
- C) **High availability (HA) with failover**
- D) Traffic shaping

---

**Q25.** A network design uses two uplink connections from an access switch to the distribution layer — one active and one in standby, ready to take over if the primary link fails. Which protocol manages this link redundancy at Layer 2?

- A) OSPF
- B) BGP
- C) VRRP
- D) **STP (Spanning Tree Protocol)**

---

**Q26.** Which first-hop redundancy protocol (FHRP) is a Cisco-proprietary protocol that allows two or more routers to share a virtual IP address, providing default gateway redundancy for hosts?

- A) VRRP
- B) GLBP
- C) **HSRP (Hot Standby Router Protocol)**
- D) LACP

---

**Q27.** Which first-hop redundancy protocol is an open-standard equivalent of HSRP, defined in RFC 5798, that allows multiple routers to share a virtual IP and MAC address for gateway redundancy?

- A) HSRP
- B) GLBP
- C) **VRRP (Virtual Router Redundancy Protocol)**
- D) STP

---

**Q28.** Which technique bonds multiple physical links between two switches into a single logical link to increase bandwidth and provide redundancy — defined by IEEE 802.3ad?

- A) STP
- B) **LACP (Link Aggregation Control Protocol) / 802.3ad**
- C) VRRP
- D) HSRP

---

**Q29.** A network administrator wants to divide a single physical switch into multiple isolated logical networks so that devices in different departments cannot communicate without going through a router. Which technology achieves this?

- A) NAT
- B) STP
- C) **VLAN (Virtual Local Area Network)**
- D) OSPF

---

**Q30.** Which IEEE standard defines VLAN tagging on Ethernet frames — adding a 4-byte tag to the frame header to identify which VLAN the frame belongs to?

- A) 802.11
- B) 802.1X
- C) 802.3ad
- D) **802.1Q**

---

**Q31.** A trunk link between two switches carries traffic for multiple VLANs simultaneously. What happens to frames that do not have an 802.1Q VLAN tag on a trunk link?

- A) They are dropped by the switch
- B) They are treated as broadcast traffic and sent to all VLANs
- C) **They are assigned to the native VLAN (VLAN 1 by default)**
- D) They trigger a STP topology change

---

**Q32.** Which network design concept involves dividing the network into separate zones (e.g., internal, DMZ, guest) to limit the impact of a security breach and restrict lateral movement by attackers?

- A) Redundancy
- B) **Network segmentation**
- C) Load balancing
- D) High availability

---

**Q33.** In a demilitarized zone (DMZ) network design, what is the PURPOSE of placing public-facing servers (web, email, DNS) in the DMZ rather than on the internal network?

- A) It gives public servers faster internet access
- B) **It creates a buffer zone where public-facing servers are isolated from the internal network — if a DMZ server is compromised, the attacker cannot directly access internal systems**
- C) It eliminates the need for a firewall on the internal network
- D) It allows the DMZ servers to bypass NAT for public access

---

**Q34.** Which of the following BEST describes an out-of-band management network?

- A) A network used to carry production traffic between data centers
- B) **A separate, dedicated network used exclusively for managing network devices — allowing administrators to access and manage devices even when the production network is down**
- C) A wireless network segment used for guest access
- D) A VLAN dedicated to VoIP traffic

---

**Q35.** What is the key difference between a point-to-point topology and a point-to-multipoint topology?

- A) Point-to-point uses fiber; point-to-multipoint uses copper
- B) **Point-to-point connects exactly two devices directly; point-to-multipoint connects one central device to multiple remote devices — like a hub-and-spoke WAN design**
- C) Point-to-point is a physical topology; point-to-multipoint is a logical topology
- D) Point-to-point is used only in wireless networks; point-to-multipoint is used in wired networks

---

## 🟡 Multiple Choice — Multiple Answer (Select ALL that apply)

*These questions may have 2 or more correct answers.*

---

**Q36.** Which of the following are TRUE about a full mesh topology? *(Select TWO)*

- A) **Every device connects directly to every other device, providing maximum redundancy**
- B) Full mesh is the most cost-effective topology for large networks
- C) **Full mesh requires n(n-1)/2 connections for n devices, making it expensive to scale**
- D) Full mesh uses a central hub device to connect all nodes
- E) Full mesh is the standard topology used in enterprise access layers

---

**Q37.** Which of the following are characteristics of the three-tier hierarchical network model? *(Select THREE)*

- A) **Core layer provides high-speed backbone connectivity and should not perform packet filtering or manipulation**
- B) Access layer connects to the WAN and internet links
- C) **Distribution layer enforces policies, handles inter-VLAN routing, and aggregates access layer traffic**
- D) **Access layer provides end-user device connectivity and handles port security and PoE**
- E) The three-tier model eliminates the need for redundant links between layers

---

**Q38.** Which of the following are TRUE about spine-leaf architecture? *(Select THREE)*

- A) Spine switches connect to other spine switches for redundancy
- B) **Every leaf switch connects to every spine switch**
- C) **Spine-leaf provides consistent, predictable latency — all traffic travels a maximum of two hops**
- D) Spine-leaf uses Spanning Tree Protocol to manage redundant paths
- E) **Spine-leaf scales horizontally by adding more leaf switches without redesigning the spine**

---

**Q39.** Which of the following are TRUE about VLANs? *(Select TWO)*

- A) VLANs can only be created on routers, not switches
- B) **VLANs logically segment a single physical switch into multiple isolated broadcast domains**
- C) Devices in different VLANs can communicate without a Layer 3 device
- D) **Traffic between VLANs requires a router or Layer 3 switch for inter-VLAN routing**
- E) VLANs require dedicated physical cables for each segment

---

**Q40.** Which of the following are first-hop redundancy protocols (FHRPs) that provide default gateway failover? *(Select TWO)*

- A) STP
- B) LACP
- C) **HSRP (Cisco proprietary)**
- D) **VRRP (open standard, RFC 5798)**
- E) OSPF

---

**Q41.** Which of the following are TRUE about SDN (Software-Defined Networking)? *(Select THREE)*

- A) SDN combines the control plane and data plane on each individual network device
- B) **SDN separates the control plane from the data plane, centralizing routing decisions in a software controller**
- C) **SDN controllers communicate with network devices using southbound APIs (e.g., OpenFlow)**
- D) **SDN enables programmatic network configuration and automation through northbound APIs**
- E) SDN requires all network devices to be replaced with proprietary SDN hardware

---

**Q42.** Which of the following network types are correctly matched to their geographic scope? *(Select THREE)*

- A) **PAN — personal area (Bluetooth, NFC, ~10 meters)**
- B) MAN — wide national coverage across multiple cities
- C) **LAN — single building or campus, organization-owned**
- D) **WAN — large geographic area, multiple cities/countries, uses leased lines or internet**
- E) CAN — a single floor of a building only

---

**Q43.** Which of the following are TRUE about network segmentation? *(Select TWO)*

- A) Network segmentation combines all devices into one flat broadcast domain for simplicity
- B) **Network segmentation limits the blast radius of a security incident by isolating compromised segments from the rest of the network**
- C) Network segmentation eliminates the need for firewalls
- D) **Network segmentation improves security and performance by reducing broadcast domain size and enforcing access control between segments**
- E) Network segmentation requires a physical firewall appliance between every segment

---

**Q44.** Which of the following are TRUE about LACP (Link Aggregation Control Protocol)? *(Select TWO)*

- A) LACP is a Cisco-proprietary protocol and cannot be used with non-Cisco equipment
- B) **LACP is defined by IEEE 802.3ad and is an open standard for bonding multiple physical links into one logical link**
- C) LACP doubles bandwidth by sending the same data on all links simultaneously
- D) **LACP increases bandwidth and provides redundancy — if one physical link fails, traffic continues over the remaining links**
- E) LACP operates at Layer 3 and uses IP addresses to balance traffic

---

**Q45.** Which of the following are TRUE about SOHO networks? *(Select TWO)*

- A) SOHO networks require enterprise-grade equipment with redundant power supplies
- B) **SOHO networks typically use an all-in-one device (combined router, switch, wireless AP, and firewall) provided by the ISP or purchased commercially**
- C) SOHO networks must use the three-tier hierarchical architecture
- D) **SOHO networks connect to the internet via DSL, cable, or fiber broadband and use NAT to share one public IP among multiple internal devices**
- E) SOHO networks require a dedicated network administrator on-site

---

## 🟠 Scenario-Based Questions

*Read each scenario carefully and select the BEST answer.*

---

**Q46.** A network engineer is designing a campus network for a university with 10 buildings, each housing hundreds of workstations. The design must support high availability, efficient traffic management between buildings, and policy enforcement. Which architecture BEST fits this requirement?

- A) Flat single-tier design with one large core switch per building
- B) Point-to-multipoint WAN topology connecting all buildings to a central site
- C) Spine-leaf architecture with 40G uplinks between buildings
- D) **Three-tier hierarchical architecture — access switches in each building, distribution switches aggregating building traffic, and a high-speed core connecting all buildings**

---

**Q47.** A data center team is designing a new network for a cloud service provider. They need predictable latency, the ability to scale horizontally by adding servers, and no dependence on Spanning Tree Protocol. Which architecture BEST meets these requirements?

- A) Three-tier hierarchical with 10G uplinks
- B) Collapsed core with redundant switches
- C) Ring topology with SONET/SDH protection
- D) **Spine-leaf architecture using ECMP (Equal-Cost Multi-Path) routing — providing predictable two-hop latency, horizontal scalability, and loop-free operation without STP**

---

**Q48.** An organization has one internal corporate network and wants to allow external customers to access a web server and email server from the internet — but does NOT want those servers to have direct access to the internal corporate systems. What is the BEST network design to achieve this?

- A) Place all servers on the internal network and use firewall ACLs to restrict access
- B) Place the servers on a separate physical network with no connection to the internal network
- C) **Create a DMZ between two firewalls — public-facing servers live in the DMZ, the outer firewall restricts inbound internet traffic to only necessary ports, and the inner firewall restricts DMZ-to-internal traffic**
- D) Use NAT to hide the internal servers' IP addresses from the internet

---

**Q49.** A manufacturing facility wants to isolate its industrial control systems (ICS) and SCADA devices from its corporate IT network to prevent cyber attacks from reaching critical infrastructure. Both networks must share the same physical switches. Which technology achieves this logical separation?

- A) STP — create a separate spanning tree instance for each network
- B) NAT — translate the ICS IP addresses to different ranges
- C) **VLANs — place ICS/SCADA devices in a dedicated VLAN and corporate devices in another, with strict ACLs controlling inter-VLAN traffic**
- D) LACP — bond the uplinks to increase bandwidth between the networks

---

**Q50.** A network administrator is configuring redundant default gateways for the finance department. The department has two routers (Router A and Router B) both connected to the same LAN segment. If Router A fails, hosts should automatically use Router B without any manual reconfiguration on the workstations. Which technology provides this capability?

- A) LACP — bond the two router interfaces into one logical link
- B) STP — elect a root bridge between the two routers
- C) OSPF — redistribute default routes to host workstations
- D) **HSRP or VRRP — both routers share a virtual IP address; hosts use the virtual IP as their gateway; if Router A fails, Router B automatically takes over the virtual IP**

---

**Q51.** A company's branch office connects to headquarters via a single MPLS WAN link. The network team wants to add a secondary internet VPN link so that if the MPLS link fails, branch traffic automatically reroutes over the VPN. They also want traffic engineering to send latency-sensitive video traffic over MPLS and bulk data over the cheaper VPN. Which technology BEST meets both requirements?

- A) HSRP — configure failover between the MPLS and VPN interfaces
- B) STP — enable redundant paths between the branch and headquarters
- C) VRRP — share a virtual IP between the MPLS and VPN endpoints
- D) **SD-WAN — provides automated failover between links and application-aware traffic steering based on link quality and policy**

---

**Q52.** A network architect is reviewing a proposed office network design. The design shows a flat network where all 500 workstations, 20 servers, a wireless guest network, and IP phones are all in the same /16 subnet with no segmentation. The architect flags this as a serious problem. Which TWO issues does this flat design create?

- A) It requires more switches than a segmented design
- B) **A single large broadcast domain means every broadcast frame is received by all 500 devices, wasting bandwidth and CPU resources (broadcast storm risk)**
- C) A flat design prevents switches from building MAC address tables
- D) **A security breach on one device could allow lateral movement to any other device on the network — there is no segmentation to limit blast radius**
- E) A flat network prevents VoIP phones from making calls

---

## 🟢 Fill in the Blank

*Complete each statement with the correct term.*

---

**Q53.** The ______________ layer of the three-tier hierarchical model provides high-speed backbone connectivity and should perform minimal packet processing. The ______________ layer connects end-user devices, handles port security and PoE, and is where access control policies are first applied as devices join the network.

---

**Q54.** In spine-leaf architecture, every ______________ switch connects to every ______________ switch. Traffic between any two endpoints travels a maximum of ______________ hops. This design provides predictable latency and horizontal scalability without relying on ______________ to manage redundant paths.

---

**Q55.** ______________ separates the control plane (routing decisions) from the data plane (packet forwarding), placing network intelligence in a centralized software controller. The controller communicates downward to network devices using ______________ APIs, and exposes network services upward to applications and orchestration systems using ______________ APIs.

---

---
---

# ✅ Answer Key & Explanations

> ⚠️ **Attempt all 55 questions before reading the answers!**

---

## Single Answer — Q1 through Q35

---

**Q1. Answer: C — Star**
> The star topology connects all devices to a central device (switch or hub). It is the dominant physical topology in modern Ethernet LANs because: (1) a single device failure affects only that device, not the whole network, (2) it is easy to add/remove devices, (3) troubleshooting is straightforward. The weakness is that the central device is a single point of failure — mitigated by using redundant switches. Hubs created shared collision domains; modern switches eliminate this problem.

---

**Q2. Answer: D — Full mesh**
> Full mesh topology connects every node directly to every other node. For n devices: n(n-1)/2 connections are required. Example: 10 devices = 45 connections. Full mesh provides maximum redundancy — there is always an alternative path if any single link fails. It is used in WAN designs and high-availability network cores where redundancy justifies the cost. Impractical for large networks due to exponential cable/port growth.

---

**Q3. Answer: C — Partial mesh**
> Partial mesh connects some — but not all — devices to multiple other devices. Critical nodes get multiple connections; less critical ones may have only one. This provides a balance between the cost of full mesh and the single point of failure risk of a star or bus. Partial mesh is common in WAN and enterprise backbone designs where key sites have redundant links and smaller branch offices have single uplinks.

---

**Q4. Answer: C — Bus**
> The bus topology connects all devices to a single shared cable (backbone) with terminators at each end. All devices share the same collision domain. A break anywhere in the cable brings down the entire segment. Used in early Ethernet (10Base2 coaxial Thinnet). It is obsolete in modern networks. The failure mode and shared medium are the most tested characteristics of bus topology.

---

**Q5. Answer: C — Ring**
> Ring topology connects each device to exactly two neighbors, forming a closed loop. Data travels in one direction (unidirectional ring) or both directions (bidirectional ring / dual ring). Token Ring (IEEE 802.5) and FDDI used ring topology. A break in a unidirectional ring disrupts the entire network. SONET/SDH uses a dual-ring (self-healing) design where traffic can reroute in the opposite direction if one path fails.

---

**Q6. Answer: C — Hybrid**
> A hybrid topology combines two or more topology types. Modern enterprise networks are almost always hybrid — for example, a star-bus (multiple star topologies connected via a bus backbone) or a star-ring (multiple star topologies connected in a ring). The internet itself is a hybrid of multiple topology types. Most real-world networks are hybrid designs.

---

**Q7. Answer: B — Physical = how cabled; logical = how data flows**
> Physical topology describes the actual physical layout of cables, devices, and connections — what you can see and touch. Logical topology describes how data flows through the network — which may differ from the physical layout. Example: Ethernet with a hub is physically a star (all cables go to the hub) but logically a bus (all devices share the same collision domain). Token Ring is physically a star (MAU/hub) but logically a ring (data passes through each device in sequence).

---

**Q8. Answer: C — LAN**
> A LAN (Local Area Network) covers a limited geographic area — a room, building, or small campus — and is typically owned and operated by a single organization. LANs use Ethernet (IEEE 802.3) or Wi-Fi (IEEE 802.11). Characteristics: high bandwidth, low latency, private ownership. WANs span large distances. MANs span a city. CANs span a campus.

---

**Q9. Answer: B — MAN**
> A MAN (Metropolitan Area Network) spans a city or metropolitan area — larger than a LAN but smaller than a WAN. It is typically provided by a carrier/ISP and connects multiple LANs within the same city. Technologies: Metro Ethernet, SONET rings, dark fiber. Example: connecting a company's downtown office to its warehouse 15 km away using a carrier-provided Metro Ethernet connection.

---

**Q10. Answer: D — WAN**
> A WAN (Wide Area Network) spans large geographic areas — cities, countries, or continents. The internet is the largest WAN. Enterprise WANs connect branch offices using: MPLS, leased lines, SD-WAN over broadband, or VPN tunnels over the internet. WANs are characterized by: higher latency than LANs, lower bandwidth (relative), and connections provided by telecommunications carriers.

---

**Q11. Answer: C — PAN**
> A PAN (Personal Area Network) covers a very small area — typically within 10 meters of a person. Technologies: Bluetooth (up to 10m), NFC (centimeters), infrared (IR), USB. Examples: connecting a smartphone to wireless earbuds, a laptop to a Bluetooth keyboard, or a smartphone to a smartwatch. PANs are the smallest network type in the geographic hierarchy.

---

**Q12. Answer: D — CAN**
> A CAN (Campus Area Network) connects multiple buildings within a campus environment — larger than a single-building LAN but smaller than a city-wide MAN. Examples: a university campus connecting multiple academic buildings, dormitories, and administrative offices; a corporate campus connecting headquarters, engineering, and manufacturing buildings. CANs typically use high-speed fiber backbones between buildings.

---

**Q13. Answer: C — Core layer**
> The core layer is the high-speed backbone of the network — it must forward traffic as fast as possible with minimal latency. Best practices: (1) the core should NOT perform packet filtering, ACL processing, or complex policy enforcement (these slow down forwarding), (2) the core should be fully redundant (dual core switches, redundant links), (3) the core connects distribution layers together and provides WAN/internet uplinks.

---

**Q14. Answer: C — Access layer**
> The access layer is where end-user devices connect to the network. Functions: (1) port security (restricting unauthorized device connections), (2) DHCP snooping (preventing rogue DHCP servers), (3) Dynamic ARP Inspection (DAI), (4) PoE (Power over Ethernet for IP phones and APs), (5) 802.1X authentication (requiring devices to authenticate before getting network access), (6) VLAN assignment (placing ports in appropriate VLANs).

---

**Q15. Answer: B — Distribution layer**
> The distribution layer aggregates traffic from multiple access switches before sending it to the core. Functions: (1) inter-VLAN routing (routing between VLANs defined at the access layer), (2) policy enforcement (ACLs, QoS marking), (3) route summarization (aggregating routes before advertising to the core), (4) redundant uplinks to the core using STP/RSTP or Layer 3 equal-cost paths. It acts as the policy boundary between the access layer and the high-speed core.

---

**Q16. Answer: B — Collapsed core (two-tier) architecture**
> When an organization is small enough that a separate distribution layer is unnecessary, the core and distribution functions are collapsed into a single layer — called a collapsed core or two-tier architecture. Access switches connect directly to the collapsed core switches. This reduces cost and complexity for small to medium organizations while maintaining the key hierarchy between access and core functions.

---

**Q17. Answer: C — Spine-leaf architecture**
> Spine-leaf is the standard modern data center network architecture. It consists of: (1) Spine switches — high-speed, high-port-count switches that form the backbone; leaf switches connect to all spines but spines never connect to each other, (2) Leaf switches — top-of-rack switches that connect to servers and to all spine switches. Every endpoint is exactly two hops from any other endpoint (leaf → spine → leaf).

---

**Q18. Answer: D — Predictable, consistent latency — two hops maximum**
> In traditional three-tier architecture, traffic can take different numbers of hops depending on source/destination location — causing variable latency. In spine-leaf, EVERY traffic flow between endpoints takes exactly the same number of hops (two: leaf → spine → leaf), resulting in consistent, predictable latency. This is critical for distributed applications and storage systems that require low and consistent response times.

---

**Q19. Answer: C — Each leaf connects to every spine; spines do not interconnect**
> The spine-leaf connection rule: (1) Every leaf switch connects to every spine switch — providing multiple equal-cost paths, (2) Spine switches NEVER connect to other spine switches — all traffic must go through a leaf, (3) Leaf switches NEVER connect to other leaf switches (with some exceptions for multi-chassis LAG). This design enables ECMP (Equal-Cost Multi-Path) routing across all spine uplinks simultaneously, maximizing bandwidth utilization.

---

**Q20. Answer: C — SDN (Software-Defined Networking)**
> SDN decouples the control plane (the intelligence that decides WHERE to forward traffic) from the data plane (the hardware that actually forwards packets based on forwarding tables). Traditional networks combine both on every device. SDN centralizes control in a software controller, making the network programmable, automatable, and manageable as code. OpenFlow is the most common southbound protocol between SDN controllers and network devices.

---

**Q21. Answer: C — SDN controller (control plane)**
> The SDN controller is the "brain" of the SDN network. It: (1) maintains a global view of the network topology, (2) makes routing and forwarding decisions for the entire network, (3) programs those decisions into network devices via southbound APIs (OpenFlow, NETCONF, RESTCONF), (4) exposes network services to applications via northbound APIs (REST, YANG models). Examples: OpenDaylight, ONOS, Cisco APIC, VMware NSX.

---

**Q22. Answer: C — Southbound API**
> In SDN architecture: Northbound APIs face upward toward applications/orchestration systems (REST APIs, YANG models) — these let applications request network services. Southbound APIs face downward toward network hardware devices — these let the SDN controller program forwarding tables and policies into switches/routers. OpenFlow is the most widely known southbound API. NETCONF/RESTCONF are also southbound APIs used in network programmability.

---

**Q23. Answer: C — SOHO**
> SOHO (Small Office/Home Office) networks are small-scale deployments — typically a combined router/switch/AP device, a cable or DSL modem, and a handful of devices. They use NAT (Network Address Translation) to share one public IP address among multiple internal devices. Management is handled by the user — no dedicated IT staff. ISPs often provide all-in-one gateway devices for SOHO customers.

---

**Q24. Answer: C — High availability (HA) with failover**
> High availability (HA) is the design principle of eliminating single points of failure so that network services remain available even when individual components fail. Failover is the automatic process of switching to a redundant device or path when the primary fails. HA is achieved through: redundant hardware (dual power supplies, RAID storage), redundant links (STP, LACP), redundant devices (HSRP, VRRP), and redundant sites (geo-redundancy).

---

**Q25. Answer: D — STP (Spanning Tree Protocol)**
> STP (IEEE 802.1D) and RSTP (Rapid STP, 802.1w) manage redundant Layer 2 links by blocking redundant paths to prevent loops, then unblocking them if the primary path fails. In the scenario described, STP would keep the standby uplink in blocking state and transition it to forwarding when the primary link fails. Note: Modern designs often use Layer 3 equal-cost paths and ECMP instead of STP to eliminate the blocking overhead.

---

**Q26. Answer: C — HSRP**
> HSRP (Hot Standby Router Protocol) is Cisco-proprietary (RFC 2281). Multiple routers share a virtual IP and virtual MAC address. One router is Active (forwarding traffic), another is Standby (monitoring). If the Active router fails, the Standby takes over the virtual IP automatically within seconds. Hosts always use the virtual IP as their default gateway — they never need reconfiguration. VRRP is the open-standard equivalent. GLBP adds load balancing across routers.

---

**Q27. Answer: C — VRRP**
> VRRP (Virtual Router Redundancy Protocol) is defined by RFC 5798 and is vendor-neutral. It works identically in concept to HSRP — routers share a virtual IP, one is Master, others are Backup. The key exam distinction: HSRP = Cisco proprietary; VRRP = open standard (works on any vendor's equipment). GLBP (also Cisco) adds active/active load balancing on top of failover capability.

---

**Q28. Answer: B — LACP / 802.3ad**
> LACP (Link Aggregation Control Protocol), defined in IEEE 802.3ad (now part of IEEE 802.1AX), combines multiple physical Ethernet links into a single logical channel called a LAG (Link Aggregation Group) or EtherChannel (Cisco term). Benefits: (1) increased bandwidth (sum of all member links), (2) redundancy (traffic continues over remaining links if one fails), (3) load balancing (traffic distributed across member links based on hash). It operates at Layer 2.

---

**Q29. Answer: C — VLAN**
> VLANs (Virtual LANs) logically divide a single physical switch into multiple isolated Layer 2 broadcast domains. Devices in different VLANs cannot communicate without a Layer 3 device (router or L3 switch). VLANs are defined by IEEE 802.1Q and identified by VLAN IDs (1–4094). Common uses: separating departments, isolating guest wireless, creating voice VLANs for IP phones, and isolating server clusters.

---

**Q30. Answer: D — 802.1Q**
> IEEE 802.1Q is the VLAN tagging standard for Ethernet. It inserts a 4-byte tag into the Ethernet frame header between the source MAC address and the EtherType field. The tag contains: TPID (0x8100 identifies it as an 802.1Q frame), Priority Code Point (PCP — used for QoS), Drop Eligible Indicator (DEI), and VLAN ID (12 bits, supporting VLANs 1–4094). 802.11 is wireless. 802.1X is port-based access control. 802.3ad is link aggregation.

---

**Q31. Answer: C — Assigned to the native VLAN (VLAN 1 by default)**
> On an 802.1Q trunk link, the native VLAN is the one VLAN whose traffic is sent untagged. If a frame arrives without a VLAN tag, the switch assigns it to the native VLAN. This is a security concern because VLAN hopping attacks can exploit the native VLAN — best practice is to change the native VLAN from VLAN 1 to an unused VLAN and ensure all legitimate traffic is tagged.

---

**Q32. Answer: B — Network segmentation**
> Network segmentation divides the network into separate logical or physical zones, each with controlled inter-zone communication. Benefits: (1) security — a breach in one segment cannot automatically spread to others (reduces blast radius), (2) performance — smaller broadcast domains reduce broadcast traffic, (3) compliance — sensitive data (PII, PCI) can be isolated in dedicated segments with strict access controls. Tools: VLANs, firewalls, ACLs, software-defined perimeter.

---

**Q33. Answer: B — Buffer zone isolating public servers from internal network**
> A DMZ (Demilitarized Zone) is a network segment between the internet and the internal network, protected by firewalls on both sides. Public-facing servers (web, email, DNS) are placed in the DMZ so that: (1) internet users can access them (outer firewall allows specific ports), (2) if a DMZ server is compromised, the attacker cannot directly reach internal systems (inner firewall blocks DMZ-to-internal traffic). The DMZ provides a controlled exposure zone.

---

**Q34. Answer: B — Separate network for device management**
> An out-of-band (OOB) management network is a separate, dedicated network used exclusively for accessing and managing network devices via console ports, dedicated management interfaces (IPMI, iLO, iDRAC), or management VLANs. The key advantage: administrators can access and troubleshoot devices even when the production network is completely down. In-band management uses the same production network for both data and management traffic — if the network is down, management access is also lost.

---

**Q35. Answer: B — Point-to-point = two devices; point-to-multipoint = one-to-many hub-and-spoke**
> Point-to-point connects exactly two endpoints with a dedicated link (e.g., a leased line between two routers). Point-to-multipoint (hub-and-spoke) connects one central site to multiple remote sites — like a corporate HQ connecting to many branch offices over WAN. Hub-and-spoke WAN designs are cost-effective (fewer circuits than full mesh) but create a dependency on the central hub site — if the hub fails, all branch-to-branch communication fails.

---

## Multiple Answer — Q36 through Q45

---

**Q36. Answer: A — Every device connects to every other, C — n(n-1)/2 connections**
> Full mesh: n nodes require n(n-1)/2 links. Example: 4 nodes = 6 links, 10 nodes = 45 links. This exponential growth makes full mesh impractical for large networks. It provides maximum redundancy because multiple alternative paths exist between every pair of nodes. Full mesh is NOT cost-effective for large networks — it is used only where redundancy requirements justify the cost (WAN between critical sites, network backbone between core switches).

---

**Q37. Answer: A — Core provides high-speed backbone, C — Distribution enforces policy/inter-VLAN routing, D — Access provides end-user connectivity**
> Three-tier hierarchy: Core = speed and backbone connectivity (no filtering), Distribution = policy/routing/aggregation boundary, Access = end-user connectivity + security enforcement. The access layer connects to end users; it does NOT connect to the WAN (that's the core/distribution). Redundant links between layers are essential for high availability — the three-tier model actively encourages redundant uplinks.

---

**Q38. Answer: B — Every leaf connects to every spine, C — Two-hop maximum latency, E — Scales horizontally by adding leaf switches**
> Spine-leaf rules: (1) Every leaf → every spine (full mesh between tiers), (2) Spines never connect to each other, (3) Leafs never connect to each other, (4) Traffic = always leaf → spine → leaf (2 hops max), (5) Scale out by adding leaf switches (connect new leaf to all spines). Spine-leaf does NOT use STP — it uses Layer 3 routing (OSPF, BGP, ECMP) to manage equal-cost paths between leaf and spine, eliminating the blocked ports that STP requires.

---

**Q39. Answer: B — VLANs logically segment into isolated broadcast domains, D — Inter-VLAN traffic requires Layer 3**
> VLANs create separate Layer 2 broadcast domains on a single physical switch. Devices in the same VLAN communicate at Layer 2 (no router needed). Devices in different VLANs CANNOT communicate without a Layer 3 device (router or L3 switch performing inter-VLAN routing). VLANs are configured on switches, not routers. No additional physical cables are needed — VLANs are logical. VLAN IDs are carried on trunk links using 802.1Q tags.

---

**Q40. Answer: C — HSRP, D — VRRP**
> FHRPs (First-Hop Redundancy Protocols): HSRP (Cisco proprietary, RFC 2281) — Active/Standby model, virtual IP + virtual MAC, Cisco only. VRRP (IEEE standard, RFC 5798) — Master/Backup model, virtual IP, vendor-neutral. GLBP (Cisco proprietary) — Active/Active load balancing. STP prevents Layer 2 loops — not a gateway redundancy protocol. LACP bonds physical links — not gateway redundancy. OSPF is a routing protocol.

---

**Q41. Answer: B — Separates control from data plane, C — Southbound APIs to devices, D — Northbound APIs to applications**
> SDN architecture: Control plane = centralized in SDN controller (separated from hardware). Data plane = distributed in network hardware (switches/routers that forward packets based on flow tables programmed by the controller). Southbound APIs (OpenFlow, NETCONF, RESTCONF, gRPC) = controller → network devices. Northbound APIs (REST, YANG) = applications → controller. SDN does NOT require proprietary hardware — it can run on commodity switches using standard southbound protocols.

---

**Q42. Answer: A — PAN (~10m), C — LAN (building/campus), D — WAN (large geographic, leased lines/internet)**
> Network type geographic scope: PAN (~10m, personal devices), LAN (room/building/campus, single org), CAN (campus, multiple buildings), MAN (city/metro area, carrier-provided), WAN (national/international, carrier-provided). MAN does NOT cover multiple cities — that would be WAN. CAN does NOT mean a single floor — it covers an entire campus of multiple buildings. Getting the geographic scope right is critical on the exam.

---

**Q43. Answer: B — Limits blast radius of security incidents, D — Improves security and performance**
> Network segmentation benefits: (1) Security — limits lateral movement; a breach in one segment cannot automatically spread network-wide. This is the "blast radius" concept — segmentation contains the damage, (2) Performance — smaller broadcast domains mean fewer devices receiving each broadcast, reducing unnecessary CPU load on end devices, (3) Compliance — required by PCI-DSS, HIPAA, and other regulations to isolate sensitive data. Segmentation requires firewalls or ACLs between segments, not necessarily physical appliances between every segment — VLANs with L3 ACLs can achieve logical segmentation.

---

**Q44. Answer: B — LACP is IEEE 802.3ad open standard, D — Increases bandwidth and redundancy**
> LACP (IEEE 802.3ad): Open standard (works across vendors). Bonds multiple physical links into one logical channel. Benefits: (1) Bandwidth = sum of all member link speeds (e.g., 4 × 10G = 40G logical link), (2) Redundancy = if one physical link fails, traffic redistributes across remaining links automatically, (3) Load balancing = traffic distributed using hash (src/dst MAC, IP, port). LACP operates at Layer 2. It does NOT double bandwidth by sending the same data twice — each frame uses one physical link.

---

**Q45. Answer: B — All-in-one combined device, D — Connects via DSL/cable/fiber with NAT**
> SOHO networks: Typically use an all-in-one gateway device (combined modem/router/switch/AP/firewall). Connect to the internet via broadband (DSL, cable/DOCSIS, fiber/GPON). Use NAT (specifically PAT — Port Address Translation) to share one public IP among multiple internal devices. No dedicated IT staff — managed by the user. No enterprise redundancy requirements. No three-tier architecture — a flat design with one consumer-grade device is standard.

---

## Scenario-Based — Q46 through Q52

---

**Q46. Answer: D — Three-tier hierarchical architecture**
> Requirements: 10 buildings, high availability, policy enforcement, efficient inter-building traffic. Analysis: Three-tier hierarchical is the ideal campus network architecture. Access switches in each building connect end users. Distribution switches per building (or building cluster) aggregate access traffic and enforce policies (ACLs, QoS). Core switches provide high-speed interconnection between all buildings. This scales to any campus size and provides clear operational boundaries. Spine-leaf is for data centers, not campus LANs. Flat or point-to-multipoint designs don't provide the policy enforcement and hierarchy needed.

---

**Q47. Answer: D — Spine-leaf with ECMP**
> Requirements: predictable latency, horizontal scalability, no STP. Analysis: Spine-leaf specifically addresses all three: (1) Predictable latency — all traffic = 2 hops (leaf → spine → leaf), (2) Horizontal scale — add leaf switches without redesigning the spine, (3) No STP — spine-leaf uses Layer 3 routing (OSPF, BGP) with ECMP, not STP. ECMP (Equal-Cost Multi-Path) distributes traffic across all spine paths simultaneously. Three-tier depends on STP for redundancy management at Layer 2. Collapsed core doesn't scale to cloud provider requirements.

---

**Q48. Answer: C — DMZ between two firewalls**
> Requirements: public server access + internal network isolation. The dual-firewall DMZ design: (1) Outer firewall (internet-facing) — permits only necessary ports inbound (HTTP/80, HTTPS/443, SMTP/25) to DMZ servers; blocks everything else, (2) DMZ — contains public-facing servers (web, email, DNS), (3) Inner firewall (internal-facing) — blocks all DMZ-initiated connections to internal network; permits only specific required responses. If a DMZ server is compromised, the attacker faces the inner firewall before reaching internal systems. This is the gold standard DMZ design.

---

**Q49. Answer: C — VLANs with strict inter-VLAN ACLs**
> Requirements: isolate ICS/SCADA from corporate IT on shared physical switches. VLANs create the logical separation without requiring separate physical infrastructure. Place ICS/SCADA devices in a dedicated VLAN (e.g., VLAN 100) and corporate devices in another (e.g., VLAN 200). Inter-VLAN ACLs on the Layer 3 switch or firewall control what traffic, if any, can pass between the two VLANs (ideally: NO traffic from corporate to ICS, specific monitoring-only traffic from ICS to corporate). This is a common exam scenario — VLANs for logical segmentation on shared physical infrastructure.

---

**Q50. Answer: D — HSRP or VRRP**
> Requirements: automatic default gateway failover for hosts when Router A fails, no host reconfiguration. HSRP/VRRP solution: Both routers share a virtual IP (e.g., 10.0.0.254). Hosts configure 10.0.0.254 as their default gateway — they never know which physical router is active. Router A is Active (or Master). Router B is Standby (or Backup), monitoring Router A via hello messages. When Router A fails, Router B takes over the virtual IP within 3–10 seconds (configurable). LACP bonds links — doesn't provide gateway redundancy. STP manages loop prevention. OSPF redistributes routes — hosts don't run OSPF.

---

**Q51. Answer: D — SD-WAN**
> Requirements: (1) automatic failover between MPLS and VPN, (2) application-aware traffic steering (video over MPLS, bulk over VPN). SD-WAN addresses both requirements exactly: (1) Link monitoring detects MPLS degradation/failure and automatically fails over to the VPN link, (2) Application-aware policies steer latency-sensitive traffic (video, VoIP) over the premium MPLS path and bulk transfers over cheaper internet VPN. HSRP/VRRP provide gateway failover but not multi-link application-aware routing. STP is Layer 2 loop prevention.

---

**Q52. Answer: B — Large single broadcast domain wastes bandwidth, D — No segmentation enables lateral movement**
> Flat network problems: (1) Single /16 broadcast domain = up to 65,534 devices receiving every ARP, DHCP, and broadcast frame — wasting bandwidth on every device's NIC and CPU. With 500 devices, a broadcast storm could bring down the entire network. (2) No segmentation = zero defense-in-depth. A single compromised workstation can directly communicate with every server, phone, and other workstation. Ransomware or an attacker can propagate laterally without any network barriers. The solution: VLANs to create separate broadcast domains + firewalls/ACLs for inter-segment control.

---

## Fill in the Blank — Q53 through Q55

---

**Q53. Answer: Core / Access**
> The **core** layer provides high-speed backbone connectivity and should forward traffic as fast as possible with minimal processing overhead — no ACLs, no complex policy enforcement. The **access** layer is where end-user devices (workstations, IP phones, printers, APs) connect to the network. It handles port security (limiting which MAC addresses can connect), 802.1X authentication, DHCP snooping, Dynamic ARP Inspection, PoE delivery, and VLAN assignment.

---

**Q54. Answer: Leaf / Spine / Two (2) / Spanning Tree Protocol (STP)**
> In spine-leaf: every **leaf** switch connects to every **spine** switch (full mesh between tiers). Traffic between any two endpoints takes a maximum of **two** hops (leaf → spine → leaf). This design eliminates the need for **Spanning Tree Protocol (STP)** because there are no Layer 2 loops — spine-leaf uses Layer 3 routing (OSPF, BGP, ECMP) to leverage all paths simultaneously, unlike STP which blocks redundant paths.

---

**Q55. Answer: SDN (Software-Defined Networking) / Southbound / Northbound**
> **SDN** separates the control plane from the data plane. The centralized SDN controller communicates downward to network hardware using **southbound** APIs (OpenFlow, NETCONF, RESTCONF, gRPC) — programming forwarding tables and policies into switches and routers. The controller exposes network services upward to applications, orchestration platforms, and management systems using **northbound** APIs (REST APIs, YANG data models) — enabling network programmability and automation.

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
| 50–55 | 90–100% | ✅ Excellent — Chapter 6 mastered |
| 41–49 | 75–89% | 🟡 Good — review wrong answers and re-test |
| 33–40 | 60–74% | 🟠 Fair — revisit Chapter 6 notes and diagrams |
| Below 33 | < 60% | 🔴 Needs Work — re-read the chapter and retry |

### Topic Weakness Identifier

| If you missed… | Review this topic |
|----------------|-------------------|
| Q1–Q6, Q36 | Physical topologies — star, bus, ring, mesh, hybrid |
| Q7 | Physical vs logical topology distinction |
| Q8–Q12, Q42 | Network types — LAN, WAN, MAN, PAN, CAN |
| Q13–Q16, Q37, Q46, Q53 | Three-tier hierarchical architecture |
| Q17–Q19, Q38, Q47, Q54 | Spine-leaf architecture and ECMP |
| Q20–Q22, Q41, Q55 | SDN — control/data plane, southbound/northbound APIs |
| Q23, Q45 | SOHO network design |
| Q24–Q27, Q40, Q50 | High availability — HSRP, VRRP, FHRPs |
| Q28, Q44 | LACP / link aggregation (802.3ad) |
| Q29–Q31, Q39, Q49 | VLANs and 802.1Q trunking |
| Q32–Q33, Q43, Q48, Q52 | Network segmentation and DMZ design |
| Q34 | Out-of-band management |
| Q35 | Point-to-point vs point-to-multipoint |
| Q25, Q38 | STP vs spine-leaf loop prevention |
| Q51 | SD-WAN for WAN redundancy and traffic steering |

---

> 💡 **Exam Day Tip:** Three-tier vs spine-leaf questions are almost always scenario-based.
> The key triggers: if the scenario mentions a **campus, university, or multi-building
> enterprise** → three-tier hierarchical. If it mentions a **data center, cloud provider,
> or east-west traffic** → spine-leaf. For redundancy questions: if hosts need automatic
> gateway failover → HSRP or VRRP. If switches need loop-free redundant uplinks → STP
> or Layer 3 ECMP. Know these triggers cold and the scenario questions become straightforward.

---

*📁 Part of the Network+ N10-009 Study Series | `Chapter-06-Topologies-Architectures/practice-questions.md`*
