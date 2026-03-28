# 📝 Practice Questions — Chapter 3
### *Cloud Concepts & Connectivity Options | Network+ N10-009 Study Series*

![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network%2B%20N10--009-FF0000?style=for-the-badge&logo=comptia&logoColor=white)
![Chapter](https://img.shields.io/badge/Chapter-03%20Cloud%20Concepts%20%26%20Connectivity-0078D4?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-55-28A745?style=for-the-badge)
![Difficulty](https://img.shields.io/badge/Difficulty-Mixed-FF6B35?style=for-the-badge)

> 📌 55 practice questions covering cloud service models (IaaS, PaaS, SaaS, XaaS),
> deployment types (public, private, hybrid, community), cloud connectivity options
> (VPN, Direct Connect, SD-WAN), virtualization, containers, the shared responsibility
> model, and Infrastructure as Code (IaC).
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

**Q1.** A company wants to migrate its email system to the cloud. They do not want to manage any servers, operating systems, or application code — they simply want to log in and use the email application. Which cloud service model BEST fits this requirement?

- A) IaaS
- B) PaaS
- C) **SaaS**
- D) XaaS

---

**Q2.** A software development team needs a cloud environment where they can deploy and run their custom-built applications without managing the underlying servers, operating systems, or runtime environments. Which cloud service model BEST meets this need?

- A) IaaS
- B) **PaaS**
- C) SaaS
- D) DaaS

---

**Q3.** A company requires full control over its virtual machines, storage, and networking in the cloud, including the ability to install and configure any operating system. Which cloud service model provides this level of control?

- A) SaaS
- B) PaaS
- C) **IaaS**
- D) FaaS

---

**Q4.** Which cloud deployment model is owned and operated exclusively for a single organization and can be hosted on-premises or by a third party?

- A) Public cloud
- B) Community cloud
- C) Hybrid cloud
- D) **Private cloud**

---

**Q5.** A healthcare consortium consisting of five hospitals wants to share a cloud environment that meets HIPAA compliance requirements, with costs and governance shared among all member organizations. Which cloud deployment model BEST describes this?

- A) Public cloud
- B) Private cloud
- C) Hybrid cloud
- D) **Community cloud**

---

**Q6.** A company uses both an on-premises private data center and a public cloud provider, with workloads able to move between them based on demand. Which cloud deployment model BEST describes this?

- A) Public cloud
- B) Private cloud
- C) **Hybrid cloud**
- D) Community cloud

---

**Q7.** In the cloud shared responsibility model, which of the following is ALWAYS the responsibility of the cloud customer, regardless of the service model (IaaS, PaaS, or SaaS)?

- A) Patching the hypervisor
- B) Managing physical hardware
- C) Configuring the runtime environment
- D) **Managing user access and data**

---

**Q8.** A company wants to connect its on-premises data center directly to a cloud provider's infrastructure using a dedicated private connection — NOT over the public internet. Which connectivity option BEST describes this?

- A) Site-to-site VPN
- B) **Direct Connect / cloud direct link**
- C) SD-WAN
- D) MPLS

---

**Q9.** Which technology allows multiple isolated virtual machines to run on a single physical server, with each VM having its own OS, storage, and network interface?

- A) Containerization
- B) SD-WAN
- C) **Hypervisor-based virtualization**
- D) Infrastructure as Code

---

**Q10.** Which of the following BEST describes a container compared to a virtual machine?

- A) Containers include a full guest OS, making them more isolated but heavier than VMs
- B) **Containers share the host OS kernel, making them lighter and faster to start than VMs**
- C) Containers require a Type 1 hypervisor to run
- D) Containers provide stronger security isolation than VMs

---

**Q11.** A cloud architect wants to deploy infrastructure using code files that can be version-controlled, reviewed, and repeatedly applied to create identical environments. Which concept describes this approach?

- A) Virtualization
- B) Containerization
- C) **Infrastructure as Code (IaC)**
- D) Platform as a Service

---

**Q12.** Which of the following is a characteristic of public cloud services?

- A) Infrastructure is dedicated to a single organization
- B) The organization bears full responsibility for physical hardware
- C) **Resources are shared among multiple tenants and managed by the cloud provider**
- D) Access is restricted to a specific group of organizations with shared interests

---

**Q13.** A company needs to connect multiple branch offices to cloud resources securely using an overlay network that intelligently routes traffic based on application type, network conditions, and policy. Which technology BEST fits this requirement?

- A) Site-to-site VPN
- B) MPLS
- C) Direct Connect
- D) **SD-WAN**

---

**Q14.** Which of the following BEST describes the difference between a Type 1 and Type 2 hypervisor?

- A) Type 1 runs on top of a host OS; Type 2 runs directly on the hardware
- B) **Type 1 runs directly on the hardware (bare-metal); Type 2 runs on top of a host OS**
- C) Type 1 is used for containers; Type 2 is used for virtual machines
- D) Type 1 supports only Windows VMs; Type 2 supports Linux VMs

---

**Q15.** In the cloud shared responsibility model under IaaS, which of the following is the cloud PROVIDER'S responsibility?

- A) Patching the guest operating system
- B) Configuring application-layer security
- C) Managing user identity and access
- D) **Maintaining physical hardware, data center facilities, and the hypervisor**

---

**Q16.** A developer wants to deploy a serverless function that runs only when triggered by an event and automatically scales without managing any infrastructure. Which cloud service model supports this?

- A) IaaS
- B) SaaS
- C) **FaaS (Function as a Service)**
- D) PaaS

---

**Q17.** Which of the following is an advantage of cloud elasticity?

- A) It guarantees a fixed amount of dedicated resources at all times
- B) **It allows resources to automatically scale up or down based on demand**
- C) It eliminates the need for network connectivity
- D) It provides physical security for on-premises hardware

---

**Q18.** A company uses AWS Direct Connect to connect its on-premises data center to AWS. What is the PRIMARY benefit of this connection over a site-to-site VPN?

- A) Direct Connect is cheaper than VPN in all cases
- B) Direct Connect uses stronger encryption than VPN tunnels
- C) **Direct Connect provides dedicated bandwidth and lower latency without traversing the public internet**
- D) Direct Connect automatically encrypts all data in transit

---

**Q19.** Which of the following cloud concepts ensures that services remain available even if one component fails, by distributing resources across multiple zones or regions?

- A) Elasticity
- B) **High availability and fault tolerance**
- C) Metered billing
- D) Multitenancy

---

**Q20.** A company is using a cloud provider and wants to ensure their virtual machines are not co-located with another organization's VMs on the same physical host. Which feature addresses this concern?

- A) Virtual private cloud (VPC)
- B) Security groups
- C) **Dedicated hosts / bare-metal instances**
- D) Auto-scaling groups

---

**Q21.** Which of the following BEST describes multitenancy in a public cloud environment?

- A) Each customer gets dedicated physical hardware
- B) **Multiple customers share the same underlying physical infrastructure, logically isolated from each other**
- C) The cloud provider and customer share equal responsibility for all resources
- D) Multiple cloud providers share the same data center facilities

---

**Q22.** Which cloud connectivity option uses the public internet but encrypts all traffic between the on-premises network and the cloud provider using IPsec?

- A) Direct Connect
- B) SD-WAN
- C) MPLS
- D) **Site-to-site VPN**

---

**Q23.** A company wants to use cloud resources for overflow capacity during peak periods while keeping sensitive workloads on-premises. Which cloud deployment model does this describe?

- A) Private cloud
- B) Community cloud
- C) Public cloud
- D) **Hybrid cloud (cloud bursting)**

---

**Q24.** Which of the following is a key security concern specific to cloud environments that does NOT typically apply to on-premises infrastructure?

- A) Physical access control
- B) Patch management
- C) **Data sovereignty and residency requirements**
- D) Firewall configuration

---

**Q25.** In cloud computing, which term describes the ability to provision and release resources on demand without human interaction from the service provider?

- A) Multitenancy
- B) Measured service
- C) **On-demand self-service**
- D) Resource pooling

---

**Q26.** A network administrator notices that their organization's cloud costs spike unexpectedly each month. Which cloud billing model would help predict costs by charging a fixed rate for a committed usage period?

- A) Pay-as-you-go
- B) Metered billing
- C) **Reserved instances**
- D) Spot instances

---

**Q27.** Which of the following container orchestration platforms is MOST commonly used to manage, deploy, and scale containerized applications across a cluster of hosts?

- A) Docker
- B) VMware vSphere
- C) **Kubernetes**
- D) Terraform

---

**Q28.** A company wants to move its on-premises application to the cloud with the LEAST amount of modification — simply migrating the existing VMs to cloud infrastructure. Which migration strategy does this describe?

- A) Refactor
- B) Re-platform
- C) **Rehost (lift and shift)**
- D) Rebuild

---

**Q29.** Which of the following is TRUE about a Virtual Private Cloud (VPC)?

- A) A VPC is a physical network segment dedicated to one customer in a public cloud
- B) A VPC requires Direct Connect to function
- C) **A VPC is a logically isolated section of a public cloud where a customer can define their own IP ranges, subnets, and routing**
- D) A VPC is only available in private cloud deployments

---

**Q30.** Which cloud characteristic refers to the provider's ability to assign and reassign physical and virtual resources dynamically to multiple consumers, with the consumer having no control or knowledge of the exact location of those resources?

- A) On-demand self-service
- B) **Resource pooling**
- C) Measured service
- D) Rapid elasticity

---

**Q31.** A company is evaluating cloud providers and wants to understand exactly what uptime the provider guarantees, and what compensation they receive if that threshold is not met. Which document specifies this?

- A) NDA (Non-Disclosure Agreement)
- B) MOU (Memorandum of Understanding)
- C) **SLA (Service Level Agreement)**
- D) AUP (Acceptable Use Policy)

---

**Q32.** Which of the following BEST describes SD-WAN compared to traditional MPLS WAN?

- A) SD-WAN requires a dedicated physical connection from each site to the provider
- B) SD-WAN only works over fiber connections
- C) SD-WAN is more expensive than MPLS and offers less flexibility
- D) **SD-WAN uses software-defined policies to route traffic intelligently over multiple connection types including broadband, LTE, and MPLS**

---

**Q33.** A developer uses Terraform to define and provision cloud infrastructure using configuration files. This approach is an example of which cloud concept?

- A) Platform as a Service
- B) Containerization
- C) **Infrastructure as Code (IaC)**
- D) Virtualization

---

**Q34.** Which of the following cloud deployment models offers the LEAST amount of control to the organization using it?

- A) Private cloud
- B) Hybrid cloud
- C) Community cloud
- D) **Public cloud**

---

**Q35.** A company is migrating to the cloud and their security team is concerned about who is responsible for patching the operating system on cloud VMs. Under IaaS, who is responsible?

- A) The cloud provider — they manage all software
- B) A shared 50/50 responsibility between customer and provider
- C) **The customer — the provider manages hardware and hypervisor; the customer manages the OS and above**
- D) A third-party managed service provider by default

---

## 🟡 Multiple Choice — Multiple Answer (Select ALL that apply)

*These questions may have 2 or more correct answers.*

---

**Q36.** Which of the following are characteristics of cloud computing as defined by NIST? *(Select THREE)*

- A) **On-demand self-service**
- B) Dedicated physical hardware for each customer
- C) **Broad network access**
- D) **Measured service (pay per use)**
- E) Requires on-premises connectivity via MPLS only

---

**Q37.** Which of the following are examples of SaaS applications? *(Select THREE)*

- A) **Microsoft 365 (Office online)**
- B) Amazon EC2 (virtual machines)
- C) **Google Workspace (Gmail, Docs)**
- D) Microsoft Azure App Service (app hosting platform)
- E) **Salesforce CRM**

---

**Q38.** Which of the following are TRUE about containers compared to virtual machines? *(Select TWO)*

- A) Containers include a full guest operating system
- B) **Containers share the host OS kernel and are more lightweight than VMs**
- C) Containers provide stronger hardware-level isolation than VMs
- D) **Containers start faster and use fewer resources than VMs**
- E) Containers require a Type 1 hypervisor to run

---

**Q39.** Which of the following are cloud connectivity options for connecting an on-premises data center to a cloud provider? *(Select THREE)*

- A) **Site-to-site IPsec VPN**
- B) **Dedicated Direct Connect / cloud direct link**
- C) VLAN trunking between on-premises switches
- D) **SD-WAN overlay**
- E) STP (Spanning Tree Protocol)

---

**Q40.** In the shared responsibility model, which of the following are ALWAYS the cloud customer's responsibility regardless of service model? *(Select TWO)*

- A) Physical server maintenance
- B) Hypervisor patching
- C) **Data classification and protection**
- D) Data center physical security
- E) **Identity and access management (IAM)**

---

**Q41.** Which of the following are TRUE about hybrid cloud deployments? *(Select TWO)*

- A) Hybrid cloud means using two different public cloud providers
- B) **Hybrid cloud combines on-premises private infrastructure with one or more public cloud services**
- C) Hybrid cloud eliminates the need for on-premises infrastructure
- D) **Hybrid cloud enables cloud bursting — using the public cloud for overflow capacity during peak demand**
- E) Hybrid cloud is only available to government organizations

---

**Q42.** Which of the following are benefits of Infrastructure as Code (IaC)? *(Select THREE)*

- A) **Consistent, repeatable environment provisioning**
- B) Eliminates the need for cloud providers entirely
- C) **Version control and auditability of infrastructure changes**
- D) **Faster deployment and reduced human error**
- E) Requires physical access to servers to apply changes

---

**Q43.** Which of the following are TRUE about Direct Connect compared to a site-to-site VPN? *(Select TWO)*

- A) Direct Connect is always cheaper than VPN
- B) **Direct Connect provides dedicated, private bandwidth that does not traverse the public internet**
- C) Direct Connect automatically encrypts all traffic end-to-end
- D) **Direct Connect offers more consistent latency and higher throughput than a VPN over the internet**
- E) Direct Connect requires no physical circuit to be provisioned

---

**Q44.** Which of the following are valid cloud service models? *(Select THREE)*

- A) **IaaS — Infrastructure as a Service**
- B) NaaS — Network as a Seat
- C) **PaaS — Platform as a Service**
- D) **SaaS — Software as a Service**
- E) TaaS — Traffic as a Service

---

**Q45.** Which of the following are security considerations unique to or amplified in cloud environments? *(Select THREE)*

- A) **Data sovereignty — data may be stored in jurisdictions with different legal requirements**
- B) Physical hardware theft from the data center
- C) **Misconfigured storage buckets or permissions exposing data publicly**
- D) **Shared tenancy — risk of data leakage between co-located customer workloads**
- E) Power outages affecting on-premises UPS systems

---

## 🟠 Scenario-Based Questions

*Read each scenario carefully and select the BEST answer.*

---

**Q46.** A financial services company must keep all customer data within the borders of their home country due to regulatory requirements. They want to use cloud services but cannot store data on servers in other countries. Which cloud concept does this regulatory requirement represent, and which deployment model BEST satisfies it?

- A) Data encryption — public cloud with encryption at rest
- B) **Data sovereignty — private cloud or a public cloud region in the same country**
- C) Multitenancy — community cloud shared with other financial institutions
- D) Elasticity — hybrid cloud with auto-scaling enabled

---

**Q47.** A startup is building a new web application. The development team wants to focus entirely on writing code and not manage any servers, databases, or middleware. The cloud provider should handle all infrastructure and platform concerns automatically. Which service model BEST meets their needs?

- A) IaaS — the team gets VMs they can configure as needed
- B) **PaaS — the platform handles infrastructure; the team deploys only their application code**
- C) SaaS — the team uses a pre-built application
- D) FaaS — each function runs independently with no persistent runtime

---

**Q48.** A company currently runs all workloads on-premises. During the annual product launch, traffic spikes 10x for three days before returning to normal. Expanding on-premises capacity for this peak would be cost-prohibitive. Which approach BEST solves this?

- A) Purchase additional on-premises servers to handle peak load permanently
- B) Deploy a CDN to absorb the traffic spike
- C) Implement QoS to prioritize launch traffic
- D) **Use hybrid cloud bursting — keeping normal workloads on-premises and spinning up cloud resources during the spike**

---

**Q49.** An enterprise's security team audits their AWS environment and discovers that an S3 storage bucket containing sensitive customer records is publicly accessible on the internet. No one in the company intentionally configured it this way. Under the shared responsibility model, who is responsible for this misconfiguration, and what should be done?

- A) AWS is responsible — they should fix the bucket permissions automatically
- B) **The customer is responsible — data security and access configuration are always the customer's responsibility; they must immediately restrict the bucket's access policy**
- C) AWS and the customer share equal responsibility for storage bucket configuration
- D) A third-party auditor is responsible for finding and fixing cloud misconfigurations

---

**Q50.** A company has five branch offices spread across three continents. They want to connect all branches to cloud resources with intelligent traffic routing — sending latency-sensitive video conferencing traffic over the best available path while routing bulk backups over cheaper links. The solution must work over existing broadband and LTE connections. Which technology BEST fits this requirement?

- A) Dedicated MPLS circuit between all five offices
- B) Site-to-site IPsec VPN with static routing
- C) Direct Connect from each branch to the cloud provider
- D) **SD-WAN with application-aware routing policies**

---

**Q51.** A DevOps team manages cloud infrastructure across development, staging, and production environments. Currently, each environment is configured manually, leading to inconsistencies and environment-specific bugs. The team lead wants all three environments to be identical and reproducible from a single source of truth. Which approach BEST solves this?

- A) Use SaaS applications to standardize the environments
- B) Hire more system administrators to manually maintain consistency
- C) **Implement Infrastructure as Code (IaC) using tools like Terraform or Ansible**
- D) Migrate all environments to a community cloud

---

**Q52.** A company's cloud architect is designing a multi-region deployment. They want to ensure that if an entire cloud region goes down (e.g., a data center fire or natural disaster), the application remains available with no data loss. Which cloud design principle addresses this?

- A) Elasticity — automatically adding more resources in the affected region
- B) Multitenancy — spreading workloads across multiple customer accounts
- C) On-demand self-service — spinning up new VMs manually after the outage is detected
- D) **High availability with geo-redundancy — deploying across multiple regions with automated failover and data replication**

---

## 🟢 Fill in the Blank

*Complete each statement with the correct term.*

---

**Q53.** In cloud computing, ______________ is the service model where the provider manages everything from hardware to the application, and the customer only manages their data and user access. ______________ is the model where the customer manages everything from the OS upward, and the provider manages physical infrastructure and the hypervisor.

---

**Q54.** The cloud deployment model that combines on-premises private infrastructure with public cloud services, allowing workloads to move between them, is called a ______________ cloud. The practice of using the public cloud for overflow capacity during peak demand periods is called ______________.

---

**Q55.** A ______________ is a dedicated private connection between an on-premises data center and a cloud provider that does not traverse the public internet, offering consistent latency and guaranteed bandwidth. By contrast, a ______________ uses the public internet but creates an encrypted tunnel using IPsec to securely connect on-premises networks to cloud resources.

---

---
---

# ✅ Answer Key & Explanations

> ⚠️ **Attempt all 55 questions before reading the answers!**

---

## Single Answer — Q1 through Q35

---

**Q1. Answer: C — SaaS**
> SaaS (Software as a Service) delivers fully managed applications over the internet. The customer uses the software but manages nothing underneath it — no servers, OS, middleware, or code. Examples: Microsoft 365, Gmail, Salesforce, Zoom. IaaS gives VMs. PaaS gives a development platform. XaaS is an umbrella term for all "as a Service" models.

---

**Q2. Answer: B — PaaS**
> PaaS (Platform as a Service) provides a managed development and deployment environment. The customer deploys their own application code; the provider manages the runtime, middleware, OS, servers, and networking. Examples: AWS Elastic Beanstalk, Google App Engine, Azure App Service, Heroku. With IaaS, the team would still need to manage the OS and runtime.

---

**Q3. Answer: C — IaaS**
> IaaS (Infrastructure as a Service) provides virtualized computing resources over the cloud — VMs, storage, and networking. The customer has full control from the OS level upward: they can install any OS, configure networking, and deploy any software. Examples: AWS EC2, Azure Virtual Machines, Google Compute Engine.

---

**Q4. Answer: D — Private cloud**
> A private cloud is dedicated to a single organization. It can be hosted on-premises or by a third party (managed private cloud), but the infrastructure is not shared with other organizations. It offers the most control and security but also the highest cost.

---

**Q5. Answer: D — Community cloud**
> A community cloud is shared among a specific group of organizations with common interests — in this case, hospitals with shared HIPAA compliance requirements. Costs, governance, and infrastructure are shared among the community members. This is different from a public cloud (open to all) and a private cloud (single organization).

---

**Q6. Answer: C — Hybrid cloud**
> A hybrid cloud combines private on-premises infrastructure with public cloud services, with orchestration allowing workloads to move between them. This is the defining characteristic of hybrid cloud — the integration and portability between environments.

---

**Q7. Answer: D — Managing user access and data**
> Regardless of service model (IaaS, PaaS, or SaaS), the customer is ALWAYS responsible for their own data and identity/access management (who can access what). The provider's responsibility boundary shifts based on the model — in SaaS, the provider manages almost everything except data and access. In IaaS, the customer manages more. Data ownership never transfers to the provider.

---

**Q8. Answer: B — Direct Connect / cloud direct link**
> Direct Connect (AWS) or ExpressRoute (Azure) or Cloud Interconnect (Google) are dedicated private connections between on-premises infrastructure and cloud providers. They bypass the public internet entirely, offering lower and more consistent latency, guaranteed bandwidth, and no exposure to internet congestion. A site-to-site VPN also connects on-premises to cloud but travels over the public internet.

---

**Q9. Answer: C — Hypervisor-based virtualization**
> A hypervisor (also called a Virtual Machine Monitor or VMM) allows multiple VMs to run on a single physical host, each with its own complete OS. Type 1 hypervisors run on bare metal (VMware ESXi, Microsoft Hyper-V, Xen). Type 2 run on top of a host OS (VMware Workstation, VirtualBox). Containers share the OS kernel — they are not VMs.

---

**Q10. Answer: B — Containers share the host OS kernel**
> Containers share the underlying host OS kernel and isolate applications at the process level using namespaces and cgroups. This makes them much lighter (MBs vs GBs), faster to start (seconds vs minutes), and more portable than VMs. VMs include a full guest OS. Containers have weaker hardware-level isolation than VMs (they share the kernel), which is a security consideration. Containers do NOT need a hypervisor.

---

**Q11. Answer: C — Infrastructure as Code (IaC)**
> IaC is the practice of managing and provisioning infrastructure through machine-readable configuration files rather than manual processes. Tools include Terraform, Ansible, Puppet, Chef, and AWS CloudFormation. IaC enables version control, repeatability, peer review, and automated deployment of infrastructure — treating infrastructure like software.

---

**Q12. Answer: C — Resources are shared among multiple tenants**
> Public cloud services are multi-tenant — multiple organizations share the same underlying physical infrastructure, logically isolated from each other. The cloud provider owns and manages all hardware. This model offers lower cost, global scale, and no capital expenditure, but the organization has less control over the physical environment.

---

**Q13. Answer: D — SD-WAN**
> SD-WAN (Software-Defined Wide Area Network) uses a software-defined control plane to intelligently route traffic across multiple underlying connection types (broadband, MPLS, LTE, etc.) based on application type, performance metrics, and policy. It is ideal for connecting branch offices to cloud resources because it provides application awareness, cost efficiency, and centralized management.

---

**Q14. Answer: B — Type 1 runs on hardware; Type 2 runs on host OS**
> Type 1 hypervisors (bare-metal) run directly on physical hardware without a host OS — examples: VMware ESXi, Microsoft Hyper-V, KVM, Xen. They are more efficient and used in enterprise/production environments. Type 2 hypervisors (hosted) run as applications on top of a host OS — examples: VMware Workstation, VirtualBox, Parallels. They are used for development and testing.

---

**Q15. Answer: D — Physical hardware, data center, and hypervisor**
> Under IaaS, the cloud provider is responsible for: physical servers, networking, storage hardware, data center facilities (power, cooling, physical security), and the hypervisor layer. The customer is responsible for: the guest OS, application code, runtime, middleware, data, and identity/access management.

---

**Q16. Answer: C — FaaS (Function as a Service)**
> FaaS is a serverless computing model where developers write individual functions that are triggered by events (HTTP request, database change, schedule). The provider manages ALL infrastructure — no servers, containers, or runtimes to configure. Examples: AWS Lambda, Azure Functions, Google Cloud Functions. It is a subset of PaaS but even more abstracted.

---

**Q17. Answer: B — Resources automatically scale up or down**
> Cloud elasticity is the ability to dynamically provision and release resources in response to demand — scaling up when traffic increases and scaling down when it decreases, automatically and rapidly. This is a core cloud characteristic that differs from traditional infrastructure, which requires manual capacity planning. It is NOT a guarantee of fixed resources (that would be reserved instances).

---

**Q18. Answer: C — Dedicated bandwidth and lower latency without traversing the internet**
> AWS Direct Connect (and equivalent services like Azure ExpressRoute) provide a private, dedicated circuit between on-premises and the cloud. Key benefits: predictable latency, consistent bandwidth, no internet congestion, and no exposure to public internet threats. Important caveat: Direct Connect does NOT automatically encrypt traffic — you must implement encryption separately if required (e.g., MACsec or VPN over Direct Connect). Site-to-site VPN is cheaper but travels over the public internet with variable latency.

---

**Q19. Answer: B — High availability and fault tolerance**
> High availability (HA) ensures services remain accessible even if components fail, by distributing resources across multiple Availability Zones, regions, or data centers with automatic failover. Elasticity is about scaling. Measured service is about billing. Multitenancy is about shared infrastructure.

---

**Q20. Answer: C — Dedicated hosts / bare-metal instances**
> In a public cloud, dedicated hosts provide physical servers exclusively for one customer — no other customer's VMs run on the same physical hardware. This addresses compliance requirements, licensing restrictions, and security concerns about co-tenancy. A VPC provides logical network isolation but not physical isolation. Security groups control network traffic.

---

**Q21. Answer: B — Multiple customers share underlying physical infrastructure, logically isolated**
> Multitenancy is a fundamental public cloud characteristic where many customers (tenants) share the same physical hardware, network, and storage infrastructure. Logical isolation (through VMs, VPCs, and access controls) separates each tenant's data and workloads. This enables economies of scale but raises concerns about data isolation and compliance.

---

**Q22. Answer: D — Site-to-site VPN**
> A site-to-site VPN uses the public internet as the transport but creates an encrypted IPsec tunnel between the on-premises gateway and the cloud provider's VPN endpoint. It is cost-effective and quick to deploy but subject to internet latency variability. Direct Connect uses a private dedicated circuit. SD-WAN routes intelligently across multiple links. MPLS is a private WAN technology.

---

**Q23. Answer: D — Hybrid cloud (cloud bursting)**
> Cloud bursting is a hybrid cloud pattern where normal workloads run on-premises (private), but when demand exceeds on-premises capacity, workloads "burst" into the public cloud automatically. This is a classic hybrid cloud use case — sensitive or steady-state workloads stay on-premises while elastic burst capacity comes from the cloud.

---

**Q24. Answer: C — Data sovereignty and residency requirements**
> Data sovereignty refers to the legal concept that data is subject to the laws of the country where it is stored. In cloud environments, data may be stored in data centers across multiple countries, creating compliance challenges that don't exist with on-premises infrastructure where data location is fully controlled. Physical access control, patch management, and firewall configuration apply to both on-premises and cloud.

---

**Q25. Answer: C — On-demand self-service**
> On-demand self-service is one of the five essential NIST cloud characteristics. It means customers can provision compute, storage, and network resources on their own, at any time, without requiring human interaction from the provider. This is what distinguishes cloud from traditional hosting. Measured service is the pay-per-use billing model. Resource pooling is shared infrastructure.

---

**Q26. Answer: C — Reserved instances**
> Reserved instances (or committed use discounts) allow customers to commit to using a specific resource for 1 or 3 years in exchange for a significant discount (up to 70%) over on-demand pricing. This provides predictable costs. Pay-as-you-go and metered billing are variable. Spot instances are deeply discounted but can be terminated by the provider at any time.

---

**Q27. Answer: C — Kubernetes**
> Kubernetes (K8s) is the industry-standard container orchestration platform for deploying, scaling, and managing containerized applications across clusters of hosts. It automates container scheduling, scaling, self-healing, and load balancing. Docker is the container runtime/image format. VMware vSphere is a VM hypervisor platform. Terraform is an IaC tool.

---

**Q28. Answer: C — Rehost (lift and shift)**
> "Lift and shift" (rehost) migrates existing applications to the cloud with no code changes — simply moving VMs from on-premises to cloud IaaS. It is the fastest migration strategy with lowest risk but captures the least cloud-native benefit. Refactor = redesign application to be cloud-native. Re-platform = make minor optimizations without full redesign. Rebuild = rewrite the application from scratch.

---

**Q29. Answer: C — Logically isolated section of public cloud with custom IP, subnets, and routing**
> A VPC (Virtual Private Cloud) is a logically isolated network environment within a public cloud where the customer can define their own IP address ranges, create subnets, configure route tables, and control network gateways. It provides network isolation without dedicated physical hardware. AWS VPC, Azure Virtual Network, and Google VPC are examples.

---

**Q30. Answer: B — Resource pooling**
> Resource pooling is the NIST cloud characteristic where the provider's computing resources are pooled to serve multiple consumers using a multi-tenant model. Resources (storage, processing, memory, network) are dynamically assigned and reassigned based on demand. Consumers generally have no knowledge or control over the exact location of the resources (though they may specify country or region).

---

**Q31. Answer: C — SLA (Service Level Agreement)**
> An SLA defines the committed level of service — typically uptime guarantees (e.g., 99.99%), performance metrics, and remedies (credits, refunds) if the provider fails to meet commitments. Cloud providers publish their SLAs publicly. An NDA protects confidential information. An MOU outlines intent between parties. An AUP defines acceptable use of services.

---

**Q32. Answer: D — SD-WAN uses software-defined policies over multiple connection types**
> SD-WAN provides application-aware, policy-driven routing across multiple WAN connection types (broadband internet, LTE/5G, MPLS) simultaneously. It is more flexible and typically cheaper than pure MPLS. It does not require a dedicated physical circuit from each site. It works over existing internet connections and provides centralized management via a software controller.

---

**Q33. Answer: C — Infrastructure as Code (IaC)**
> Terraform is an IaC tool that uses declarative configuration files (HCL language) to define, provision, and manage cloud infrastructure across multiple providers. The infrastructure definition is stored as code — versionable, testable, and repeatable. This is the defining example of IaC. Kubernetes manages containers. Docker is a container runtime. Ansible is another IaC/configuration management tool.

---

**Q34. Answer: D — Public cloud**
> In a public cloud, the customer has the least control — they cannot control physical hardware location (beyond region selection), cannot inspect the underlying infrastructure, and must accept the provider's shared security model. Private cloud offers maximum control (dedicated infrastructure). Hybrid and community clouds offer intermediate levels.

---

**Q35. Answer: C — The customer manages OS and above; provider manages hardware and hypervisor**
> Under IaaS, the shared responsibility boundary sits at the hypervisor. The cloud provider is responsible for: physical hardware, data center, networking hardware, and the hypervisor. The customer is responsible for: guest OS installation and patching, application code, runtime configuration, middleware, data, and identity management. This is one of the most tested shared responsibility model questions.

---

## Multiple Answer — Q36 through Q45

---

**Q36. Answer: A — On-demand self-service, C — Broad network access, D — Measured service**
> The five NIST essential cloud characteristics are: (1) On-demand self-service, (2) Broad network access, (3) Resource pooling, (4) Rapid elasticity, and (5) Measured service. Dedicated hardware contradicts multitenancy. MPLS-only connectivity contradicts broad network access.

---

**Q37. Answer: A — Microsoft 365, C — Google Workspace, E — Salesforce CRM**
> SaaS applications are fully managed, ready-to-use software: Microsoft 365, Google Workspace (Gmail, Docs, Sheets), Salesforce, Zoom, Dropbox. Amazon EC2 is IaaS (virtual machines). Azure App Service is PaaS (a deployment platform for applications). The key question for SaaS: does the customer manage any infrastructure or code? If no — it's SaaS.

---

**Q38. Answer: B — Share host OS kernel, D — Start faster and use fewer resources**
> Containers share the host OS kernel (using Linux namespaces and cgroups for isolation), making them MB-sized vs GB-sized VMs, and they start in seconds vs minutes. VMs have stronger isolation because they have their own full OS and run on a hypervisor — a compromised container could potentially affect the host kernel, while a compromised VM has a harder path to the host. Containers do NOT require a hypervisor.

---

**Q39. Answer: A — Site-to-site VPN, B — Direct Connect, D — SD-WAN**
> The three primary ways to connect on-premises to cloud: (1) Site-to-site IPsec VPN (encrypted, over internet), (2) Direct Connect/ExpressRoute (dedicated private circuit), (3) SD-WAN (intelligent overlay over multiple link types). VLAN trunking is a local network technology. STP prevents Layer 2 loops and is not a WAN connectivity option.

---

**Q40. Answer: C — Data classification and protection, E — Identity and access management**
> Across ALL cloud service models (IaaS, PaaS, SaaS), customers retain responsibility for their data (classification, encryption, compliance) and IAM (who has access, with what privileges, using what authentication). Physical server maintenance and hypervisor patching are always the provider's responsibility. Data center physical security is always the provider's responsibility.

---

**Q41. Answer: B — Combines on-premises with public cloud, D — Enables cloud bursting**
> Hybrid cloud specifically combines private on-premises (or private cloud) infrastructure with public cloud services. It is NOT about using two public cloud providers (that's multi-cloud). Cloud bursting is a key hybrid cloud pattern. Hybrid cloud does NOT eliminate on-premises infrastructure — having both is what makes it hybrid. It is used across industries, not just government.

---

**Q42. Answer: A — Consistent provisioning, C — Version control and auditability, D — Faster deployment**
> IaC benefits: (1) Consistency — environments are identical every time, (2) Version control — changes are tracked in Git like code, enabling peer review and rollback, (3) Speed — automated provisioning is faster than manual configuration, (4) Reduced human error — no manual typing mistakes. IaC does not eliminate cloud providers — it automates using them. It does not require physical server access.

---

**Q43. Answer: B — Dedicated private bandwidth not on internet, D — More consistent latency and higher throughput**
> Direct Connect provides a private, dedicated circuit (provisioned through a colocation or partner facility) that never touches the public internet. This gives: (1) consistent, predictable latency (no internet congestion), (2) higher throughput with committed bandwidth guarantees, (3) no internet security exposure. It is NOT always cheaper (it has provisioning costs). It does NOT automatically encrypt traffic — encryption must be added separately.

---

**Q44. Answer: A — IaaS, C — PaaS, D — SaaS**
> The three foundational cloud service models are IaaS, PaaS, and SaaS. Other legitimate XaaS models include FaaS, DaaS (Desktop as a Service), and DBaaS (Database as a Service). "NaaS — Network as a Seat" and "TaaS — Traffic as a Service" are fabricated distractors — do not be fooled by plausible-sounding acronyms.

---

**Q45. Answer: A — Data sovereignty, C — Misconfigured storage buckets, D — Shared tenancy risk**
> Cloud-specific security concerns: (1) Data sovereignty — where data is physically stored affects legal jurisdiction, (2) Misconfiguration — the #1 cause of cloud data breaches (publicly accessible S3 buckets, overpermissive IAM roles), (3) Shared tenancy — theoretical risk of data leakage between co-located tenants (side-channel attacks, hypervisor vulnerabilities). Physical theft and UPS failures are on-premises concerns the provider handles in cloud.

---

## Scenario-Based — Q46 through Q52

---

**Q46. Answer: B — Data sovereignty — private cloud or same-country public cloud region**
> Data sovereignty means data must remain within a specific legal jurisdiction. For a financial services company with this requirement, the solution is either a private cloud (full control over data location) or a public cloud provider with a certified region within the same country. Encryption at rest doesn't solve jurisdiction issues. Community cloud shares data among multiple organizations. The key term for the exam is "data sovereignty."

---

**Q47. Answer: B — PaaS**
> The team wants to write code only — they don't want to manage any servers, OS, middleware, databases, or runtime. PaaS provides a managed platform where developers deploy only their application code. IaaS would still require OS and runtime management. SaaS is a pre-built application they'd use, not build. FaaS is more granular (individual event-triggered functions) and doesn't provide a persistent application runtime, so PaaS is the better fit for a full web application.

---

**Q48. Answer: D — Hybrid cloud bursting**
> The problem is peak demand that is impractical to handle with permanent on-premises capacity. Cloud bursting solves this exactly — normal load runs on-premises (cost-effective), and the 10x peak overflow automatically spins up in the public cloud for three days, then scales back down. Purchasing permanent servers is wasteful for 3-day peaks. A CDN helps with content delivery but not application compute. QoS manages traffic priority, not compute capacity.

---

**Q49. Answer: B — Customer is responsible; restrict bucket access immediately**
> Under the shared responsibility model, data security and access configuration in IaaS/SaaS environments are ALWAYS the customer's responsibility. AWS (or any cloud provider) provides the tools (bucket policies, IAM) to secure storage — but configuring those controls is the customer's job. A publicly accessible bucket with sensitive data is a customer misconfiguration. The immediate action is to apply a restrictive bucket policy. This is also a real-world #1 cause of cloud data breaches.

---

**Q50. Answer: D — SD-WAN with application-aware routing**
> The requirements — multiple branches, multiple continents, intelligent routing (video conferencing on best path, backups on cheaper links), existing broadband and LTE connections — perfectly describe SD-WAN. SD-WAN's defining capability is application-aware, policy-driven routing across heterogeneous connection types. MPLS is expensive and doesn't work over existing broadband. Static VPN doesn't adapt to network conditions. Direct Connect from each branch is expensive and doesn't provide intelligent routing.

---

**Q51. Answer: C — Infrastructure as Code using Terraform or Ansible**
> The problem is environment drift — manual configuration leads to inconsistencies. IaC solves this by defining ALL environments in code files stored in version control. Running the same IaC configuration produces identical environments every time. Terraform provisions infrastructure (VMs, networks, storage). Ansible configures software on those resources. SaaS applications don't help with infrastructure consistency. More administrators makes the problem worse. Community cloud doesn't solve environment inconsistency.

---

**Q52. Answer: D — High availability with geo-redundancy**
> Protecting against an entire region failure requires geo-redundancy: deploying the application across multiple geographically separated cloud regions with: (1) data replication between regions in real time (or near-real-time), (2) automated DNS failover to redirect traffic to the surviving region, (3) health checks that trigger failover automatically. Elasticity adds capacity within a region — useless if the region is down. Multitenancy is about sharing, not redundancy. Manual spin-up is too slow.

---

## Fill in the Blank — Q53 through Q55

---

**Q53. Answer: SaaS / IaaS**
> **SaaS** (Software as a Service) is where the provider manages everything from hardware to the application — the customer only manages their data and users. **IaaS** (Infrastructure as a Service) is where the customer manages everything from the OS upward, and the provider manages physical infrastructure and the hypervisor. This is the full spectrum of the shared responsibility model.

---

**Q54. Answer: Hybrid / cloud bursting**
> A **hybrid** cloud combines on-premises private infrastructure with public cloud services, with workloads portable between them. **Cloud bursting** is the specific pattern of using the public cloud for overflow/peak capacity while keeping baseline workloads on-premises — automatically expanding into the cloud when on-premises capacity is exceeded.

---

**Q55. Answer: Direct Connect (or cloud direct link / ExpressRoute) / site-to-site VPN**
> A **Direct Connect** (AWS) or **ExpressRoute** (Azure) is a dedicated private connection to a cloud provider, bypassing the public internet, providing consistent latency and guaranteed bandwidth. A **site-to-site VPN** creates an encrypted IPsec tunnel over the public internet between on-premises and cloud — lower cost and faster to deploy but subject to internet variability.

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
| 50–55 | 90–100% | ✅ Excellent — Chapter 3 mastered |
| 41–49 | 75–89% | 🟡 Good — review wrong answers and re-test |
| 33–40 | 60–74% | 🟠 Fair — revisit Chapter 3 notes and diagrams |
| Below 33 | < 60% | 🔴 Needs Work — re-read the chapter and retry |

### Topic Weakness Identifier

| If you missed… | Review this topic |
|----------------|-------------------|
| Q1–Q3, Q16, Q37, Q44, Q53 | Cloud service models — IaaS, PaaS, SaaS, FaaS |
| Q4–Q6, Q12, Q21, Q23, Q34, Q41, Q54 | Cloud deployment models — public, private, hybrid, community |
| Q7, Q15, Q35, Q40, Q45, Q49 | Shared responsibility model |
| Q8, Q18, Q22, Q39, Q43, Q55 | Cloud connectivity — Direct Connect vs VPN |
| Q9–Q10, Q14, Q38 | Virtualization and containers |
| Q11, Q27, Q33, Q42, Q51 | Infrastructure as Code and Kubernetes |
| Q13, Q32, Q50 | SD-WAN and WAN connectivity |
| Q17, Q19, Q25, Q30, Q36 | NIST cloud characteristics |
| Q24, Q29, Q46 | Data sovereignty and VPC |
| Q26, Q31 | SLAs and cloud billing models |
| Q28 | Cloud migration strategies |
| Q52 | High availability and geo-redundancy |

---

> 💡 **Study Tip:** The shared responsibility model (Q7, Q15, Q35, Q40, Q49) is one of
> the most tested cloud topics on the N10-009. Draw the responsibility matrix for
> IaaS, PaaS, and SaaS and memorize what shifts between provider and customer at
> each layer. Data and IAM are ALWAYS the customer's responsibility.

---

*📁 Part of the Network+ N10-009 Study Series | `Chapter-03-Cloud-Concepts/practice-questions.md`*
