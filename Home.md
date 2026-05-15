# Network Fundamentals & Automation Engineering

## From Automation Practitioner to Architecture Visionary

Welcome! This wiki documents my journey as a **Network Automation Engineer** (7+ years at Nokia & Ericsson) transitioning into **architectural depth**, **AI-driven automation**, and **technical interview mastery**. This is not just networking 101—it's about understanding _why_ we automate, _how_ modern AI augments network operations, and _what_ technical leaders need to know.

---

## 🎯 Mission Statement

As an experienced automation engineer, I have:

- ✅ Built and deployed automated workflows in telecom infrastructure (Nokia, Ericsson)
- ✅ Mastered Robot Framework and automation testing frameworks
- ✅ Scaled operations through Python, APIs, and custom scripts

**Now I'm leveling up to:**

- 📚 Master underlying network architecture and protocols (not just APIs that hide them)
- 🤖 Leverage AI/LLMs to augment network automation and troubleshooting
- 🏗️ Design next-generation automation solutions with AI/ML

---

## 📊 Audience & Repository Map

| Role                         | Primary Focus                         | Recommended Path                                                                                        |
| ---------------------------- | ------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **You (Current)**            | Deepen fundamentals + AI/modern tools | Start: [Core Fundamentals](#1-core-fundamentals) → [AI Integration](#4-ai-in-network-operations)        |
| **New Automation Engineers** | Learn automation through this repo    | Start: [Protocols](#2-routing--protocols) → [Automation](#3-network-automation--infrastructure-as-code) |
| **Interview Prep**           | System design, architecture, depth    | [Interview Master](#6-interview-prep--technical-depth) section                                          |

---

## 🏗️ Core Learning Structure

### 1. **Core Fundamentals** (Bridging the Gaps)

_Why you need this: Telecom companies' automation often abstracts these layers. Time to own the theory._

#### 1.1 OSI Model Deep Dive

- Why 7 layers exist and how they interact
- Real telecom equipment perspective (network nodes, RAN, core)
- Packet structure at each layer
- **Practical**: tcpdump and Wireshark analysis of real traffic
- **Interview Q**: "Explain TCP vs UDP trade-offs at Layer 4"
- [Learn more →](./Fundamentals/OSI-Model)

#### 1.2 Networking Fundamentals

- IP addressing (IPv4, IPv6, CIDR, subnetting)
- MAC addresses and ARP protocol
- Link layer concepts (Ethernet, Frame Relay, optical)
- How does your automation tool track these?
- **Practical**: use Wireshark to inspect ARP, DHCP, and VLAN traffic in a lab
- **Interview Q**: "How do you design subnetting for a segmented automation environment?"
- [Learn more →](./Fundamentals/IP-Addressing)

#### 1.3 Telecom-Specific Protocols

- Understanding telecom network architecture (RAN, Core, EPC/5GC)
- 3GPP standards overview
- Difference between IT networking and telecom
- **Mind Map**: 5G network slicing architecture
- **Interview Q**: "What are the key differences between telecom core and traditional enterprise networks?"
- [Learn more →](./Fundamentals/Telecom-Protocols)

---

### 2. **Routing & Protocols** (From User to Global Scale)

_Why this matters: Most Telecom automation touches routing, BGP, OSPF at some layer._

#### 2.1 BGP (Border Gateway Protocol)

- BGP fundamentals: AS numbers, prefixes, path selection
- BGP states, timers, and convergence
- Attributes and route filtering (what you automate!)
- Troubleshooting BGP issues through automation
- **Real-world**: How ISPs use BGP for traffic engineering
- **Interview Q**: "Design an automated BGP monitoring solution"
- [Learn more →](./Protocols/BGP)

#### 2.2 OSPF & Interior Gateway Protocols

- Link-state routing: OSPF, IS-IS
- Comparison: OSPF vs BGP vs eigrp
- Metric calculation and convergence
- SPF (Shortest Path First) algorithm
- **Automation angle**: Automating OSPF neighbor management
- **Interview Q**: "How would you automate OSPF neighbor and area validation across multiple routers?"
- [Learn more →](./Protocols/OSPF-ISIS)

#### 2.3 Segment Routing (SR)

- Modern routing: Segment Routing vs traditional MPLS
- Why SR matters for network automation
- SR deployment use cases (Telecom, Cloud)
- **Interview Q**: "What are the automation benefits of segment routing compared to classic MPLS?"
- [Learn more →](./Protocols/Segment-Routing)

#### 2.4 MPLS & Traffic Engineering

- MPLS fundamentals and label switching
- TE-MPLS and fast reroute (FRR)
- How automation monitors MPLS tunnels
- **Interview Q**: "How would you build automated monitoring for MPLS TE and FRR?"
- [Learn more →](./Protocols/MPLS-TE)

---

### 3. **Network Automation & Infrastructure-as-Code** (Expertise to Enterprise)

_Scaling from individual scripts to enterprise automation + AI._

#### 3.1 Automation Frameworks Review

- Robot Framework deep dive
- Comparison: Robot vs Ansible vs Terraform vs Python
- When to use each framework
- Best practices from Nokia/Ericsson implementations
- **Interview Q**: "Which automation framework would you choose for a multi-vendor network and why?"
- [Learn more →](./Automation/Robot-Framework)

#### 3.2 Modern Automation Stack

- **YANG/NETCONF/RESTCONF**: Model-driven networking
- Ansible for network automation at scale
- Terraform for infrastructure provisioning
- Python scripting vs. frameworks (when frameworks fail)
- **Interview Q**: "Design a multi-vendor automation solution"
- [Learn more →](./Automation/Modern-Stack)

#### 3.3 API-First Networking

- Understanding APIs as the backbone of automation
- gNMI (gRPC Network Management Interface)
- Telemetry and streaming data (not just polling)
- How to build resilient API calls
- **Interview Q**: "How do you ensure resilience for network automation APIs?"
- [Learn more →](./Automation/APIs-Telemetry)

#### 3.4 CI/CD for Network Operations

- GitOps, Github Actions and network infrastructure
- Testing network configurations
- Network validation and compliance automation
- Rollback strategies for network changes
- **Interview Q**: "What CI/CD approach would you use for automated network changes?"
- [Learn more →](./Automation/CICD-Networks)

---

### 4. **AI in Network Operations** (The Future)

_Competitive advantage: Blending automation experience + AI/ML expertise._

#### 4.1 LLMs for Network Automation

- Using ChatGPT/Claude for network design and troubleshooting
- Prompt engineering for network queries
- Generating automation code using AI
- Limitation awareness: What AI gets wrong in networking
- **Practical**: Building ChatGPT plugins for network automation
- **Interview Q**: "How would you use LLMs safely in network automation?"
- [Learn more →](./AI-Networks/LLMs-Automation)

#### 4.2 Anomaly Detection & AIOps

- Using ML for detecting network anomalies
- Building ML models on network telemetry
- Predictive maintenance through AI
- Real case studies: Telecom operators using AIOps
- **Interview Q**: "How would you create an AIOps workflow for telecom network alerts?"
- [Learn more →](./AI-Networks/AIOps)

#### 4.3 Network Intent & Autonomous Systems

- Network Intent Protocol (NIP) concepts
- Using AI for autonomous network healing
- Self-healing network automation
- What's hype vs. reality
- **Interview Q**: "What are the key challenges in building autonomous network systems?"
- [Learn more →](./AI-Networks/Autonomous-Networks)

#### 4.4 AI-Driven Root Cause Analysis

- Combining automation data + AI for RCA
- Building knowledge graphs from network data
- AI for log analysis and correlation
- **Tool Comparison**: Network RCA tools + AI integration
- **Interview Q**: "How would AI improve root cause analysis in a network operations center?"
- [Learn more →](./AI-Networks/AI-RCA)

---

### 5. **Data Center & Cloud Networking** (Modern Infrastructure)

_Understanding where your automation runs today + tomorrow._

#### 5.1 Data Center Architecture

- 3-tier vs. spine-leaf topology
- Why spine-leaf dominates modern data centers
- Underlay and overlay networks
- Equal-Cost Multi-Path (ECMP) routing
- **Interview Q**: "How do you design a spine-leaf fabric for scalable automation?"
- [Learn more →](./DataCenter/Architecture)

#### 5.2 Virtualization & SDN

- Virtual switching and bridging
- OpenFlow and SDN concepts
- Network Functions Virtualization (NFV)
- Kubernetes networking and service discovery
- **Interview Q**: "What is the role of SDN in modern automated data centers?"
- [Learn more →](./DataCenter/SDN-NFV)

#### 5.3 Cloud Networking Models

- AWS, Azure, GCP networking paradigms
- Hybrid cloud networking
- Site-to-site VPN and inter-cloud connectivity
- Automating cloud networking
- **Interview Q**: "How do you automate hybrid cloud network connectivity securely?"
- [Learn more →](./DataCenter/Cloud-Networking)

#### 5.4 Container Networking

- Container networking basics (Docker, Kubernetes)
- CNI (Container Network Interface) plugins
- Service mesh fundamentals (Istio, Linkerd)
- **Interview Q**: "Design a microservices network"
- [Learn more →](./DataCenter/Container-Networking)

---

### 6. **Interview Prep & Technical Depth** (Landing Your Next Role)

_From automation engineer to architecture visionary._

#### 6.1 System Design for Networks

- Designing scalable automation systems
- Building resilient network monitoring
- Designing for failure scenarios
- High-level architecture discussions
- **Example Questions**:
  - "Design a global BGP monitoring system"
  - "Build an automated network compliance engine"
  - "Design an AIOps platform for large enterprises"
- [Learn more →](./Interview-Prep/System-Design)

#### 6.2 Technical Leadership Topics

- Scalability and performance in automation
- Debugging complex distributed network issues
- Trade-offs: Centralized vs. distributed automation
- Cost optimization through automation
- **Interview Q**: "What leadership considerations matter most when scaling network automation?"
- [Learn more →](./Interview-Prep/Leadership-Topics)

#### 6.3 Telecom-Specific Architecture

- Deep understanding of 5G/4G architecture
- How Telecom equipment fits in networks
- RAN architecture (gNB, DU, CU)
- Core network (AMF, SMF, UPF)
- **Interview Q**: "Explain the architecture of 5G network slicing"
- [Learn more →](./Interview-Prep/Telecom-Architecture)

#### 6.4 Interview Question Repository

- Top 50 networking questions (with answers)
- Top 30 automation interview questions
- Behavioral questions specific to automation roles
- FAANG vs. startup vs. telecom interviews
- [Learn more →](./Interview-Prep/Question-Bank)

---

### 7. **Advanced & Emerging Topics** (Stay Ahead)

_What's next in networking and automation._

#### 7.1 Network Telemetry & Observability

- Streaming telemetry (gNMI, SNMP, syslog)
- Metrics, logs, traces (The three pillars)
- Time-series databases (InfluxDB, Prometheus)
- Visualization (Grafana, Kibana)
- **Interview Q**: "Design a network observability platform"
- [Learn more →](./Advanced/Telemetry)

#### 7.2 Security Automation

- Automating firewall rule management
- Network segmentation automation
- Compliance automation (frameworks: CIS, PCI-DSS)
- Zero-trust architecture principles
- **Interview Q**: "How would you automate security policy enforcement across a hybrid network?"
- [Learn more →](./Advanced/Security-Automation)

#### 7.3 Edge Computing & 5G

- Edge nodes and distributed architecture
- 5G network slicing automation
- RAN intelligent controller (RIC)
- Automating edge network deployments
- **Interview Q**: "How do you automate edge network deployments in 5G environments?"
- [Learn more →](./Advanced/Edge-5G)

#### 7.4 Network AI/ML Opportunities

- Where AI adds real value in networking
- Building your own ML models
- Avoiding common pitfalls
- Startup ideas in network AI
- **Interview Q**: "What AI/ML opportunity would you propose for network operations?"
- [Learn more →](./Advanced/ML-Opportunities)

---

## 🗺️ Quick Navigation by Use Case

### **I want to deepen fundamentals** (New architecture role)

→ Start: [Core Fundamentals](#1-core-fundamentals) → [Routing & Protocols](#2-routing--protocols) → [System Design](#61-system-design-for-networks)

### **I want to leverage AI in automation** (Modern tooling)

→ Start: [AI in Network Operations](#4-ai-in-network-operations) → [Modern Stack](#32-modern-automation-stack) → [Real case studies](#32-modern-automation-stack)

### **I'm preparing for FAANG/startup interviews**

→ Start: [System Design](#61-system-design-for-networks) → [Interview Questions](#64-interview-question-repository)

### **I need to transition from telecom to cloud/data center**

→ Start: [Data Center Architecture](#51-data-center-architecture) → [Cloud Networking](#53-cloud-networking-models) → [Container Networking](#54-container-networking)

### **I want to stay cutting-edge in networking**

→ Start: [Emerging Topics](#7-advanced--emerging-topics) → [AI/ML Opportunities](#74-network-aiml-opportunities)

---

## 📊 Progress Tracking

| Module                 | Status         | Last Updated | Priority  |
| ---------------------- | -------------- | ------------ | --------- |
| Core Fundamentals      | 📝 In Progress | -            | 🔴 High   |
| Routing & Protocols    | 📝 In Progress | -            | 🔴 High   |
| Network Automation     | 📝 In Progress | -            | 🔴 High   |
| AI in Networks         | 📋 Planning    | -            | 🟡 Medium |
| Data Center Networking | 📋 Planning    | -            | 🟡 Medium |
| Interview Prep         | 📋 Planning    | -            | 🟡 Medium |
| Emerging Topics        | 📋 Backlog     | -            | 🟢 Low    |

---

## 💡 Unique Value Proposition

Unlike generic networking resources, this wiki:

- ✅ **Bridges theory and practice** from 7+ years of telecom automation
- ✅ **Includes AI/LLM perspectives** (not just traditional networking)
- ✅ **Tailored for interviews** with system design focus
- ✅ **Addresses telecom-specific knowledge** (5G, 3GPP, AMF)
- ✅ **Balances depth and breadth** for principal engineer aspirations

---

## 📝 Contribution & Maintenance

Last Updated: **May 15, 2026**

This wiki is a **living document** evolving with:

- New AI/ML techniques in networking
- Emerging network technologies
- Interview questions and learnings
- Real-world project documentation
- Tool updates and comparisons

**Your feedback improves this wiki!** If you find gaps, have questions, or want to contribute, consider opening an issue or PR.

---

**Ready to level up? Start with [Core Fundamentals](#1-core-fundamentals) or jump to your area of interest! 🚀**
