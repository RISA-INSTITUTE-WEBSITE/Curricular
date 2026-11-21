# CS202 — Networking

**Institution:** RISA Institution of Applied Sciences  
**Discipline:** Computer Science  
**Module code:** CS202  
**Module title:** Networking  
**Level:** Second-year / 200-level  
**Document:** Proposed module learning outcomes  
**Status:** Draft — pending academic review  
**Version:** 0.1  
**Date:** 21 November 2026

## 1. Module purpose

This module introduces how networked computers exchange information using layered protocols. Students learn to describe network components, configure simple connections and diagnose common connectivity problems through supervised, authorized practical activities.

**Curriculum alignment:** The RISA concept overview explicitly lists TCP/IP, routing, DNS, HTTP and wireless networks. The additional addressing, security, troubleshooting and hands-on laboratory topics are proposed extensions.

## 2. Proposed module learning outcomes

**Upon successful completion of CS202, students should be able to:**

| Code | Learning outcome |
| --- | --- |
| **LO1** | Describe the purpose, types and components of computer networks, distinguishing local and wide-area networks and common topologies. |
| **LO2** | Explain network layering and map major functions and protocols to the TCP/IP model, comparing it with the OSI reference model. |
| **LO3** | Explain how Ethernet and Wi-Fi support local communication, including the roles of switches, access points and basic link-layer addressing. |
| **LO4** | Interpret IPv4 and IPv6 addresses and configure or analyse simple IPv4 subnet and default-gateway settings. |
| **LO5** | Explain the roles of routers, packet forwarding and routing tables in sending traffic between networks. |
| **LO6** | Distinguish TCP and UDP and explain ports, reliable delivery, congestion considerations and common transport-layer use cases at an introductory level. |
| **LO7** | Trace how DNS name resolution and HTTP/HTTPS requests support access to web resources. |
| **LO8** | Describe basic wireless networking principles, including SSIDs, channels, interference and secure connection configuration. |
| **LO9** | Use authorized network utilities or simulations to inspect configurations, test reachability and systematically diagnose simple networking faults. |
| **LO10** | Design, document and validate a small network topology that meets specified connectivity and basic security requirements. |

## 3. Learning outcomes by teaching section

### Section A — Network Fundamentals and Layered Communication

**Mapped outcomes:** LO1, LO2, LO3

**Content focus:**
- Network types, components and topologies
- TCP/IP layers and OSI comparison
- Ethernet, switches, access points, frames and local addressing

### Section B — Internet Protocols and Wireless Networking

**Mapped outcomes:** LO4, LO5, LO6, LO7, LO8

**Content focus:**
- IPv4 subnetting; introductory IPv6 addressing and gateways
- Routing and forwarding
- TCP/UDP, ports and common services
- DNS and HTTP/HTTPS communication flow
- Wireless network operation and protected access

### Section C — Configuration, Troubleshooting and Practical Work

**Mapped outcomes:** LO9, LO10; integrates LO1–LO8

**Content focus:**
- Address assignment and basic network configuration
- Safe use of ping, traceroute/tracert and name lookup tools
- Simulation and documentation of small topologies
- Identifying and correcting typical connectivity faults

## 4. Suggested practical learning and assessment activities

These activities are **proposals**, not a finalized assessment specification.

| Practical activity | Outcomes assessed |
| --- | --- |
| Diagram a small LAN and identify each component's function. | LO1, LO3 |
| Annotate a packet journey using TCP/IP and OSI layer responsibilities. | LO2 |
| Use a simulator to connect devices through a switch and access point. | LO3, LO8 |
| Calculate basic IPv4 subnet ranges and test gateway settings. | LO4 |
| Configure a simple routed two-subnet network in a simulator. | LO5, LO10 |
| Compare UDP and TCP application scenarios using defined requirements. | LO6 |
| Trace DNS lookup and HTTP/HTTPS request steps from a client perspective. | LO7 |
| Diagnose a supplied fault using permitted command-line utilities. | LO9 |
| Deliver a labelled network topology, configuration record and test evidence. | LO9, LO10 |

## 5. Recommended teaching boundaries

- **Safety and authorization:** Practical packet inspection, network scans and configuration changes must be restricted to approved lab systems or simulation environments.
- **Networking scope:** Focus on foundational TCP/IP and small-network operation; leave advanced routing protocols, enterprise architecture and wireless engineering for later modules.
- **Relationship with CS222:** Discuss network protocol behaviour here, while detailed kernel socket and process internals are out of scope.
- **Security:** Teach defensive configuration and safe handling of credentials without requiring penetration testing.

## 6. Curriculum development and approval notes

The curriculum team should determine and approve:

- Choose equipment and an accessible network simulator.
- Set IPv4 subnetting depth and introductory IPv6 expectations.
- Specify permitted network tools, laboratory isolation and access rules.
- Determine credits, prerequisites and practical assessment rubrics.
- Assessment weightings, contact hours, prerequisites and institutional approval status.

**Source and development basis:** Original RISA concept overview: TCP/IP, routing, DNS, HTTP and wireless networks. Expanded foundational content and lab outcomes are proposed, not sourced from the handwritten notes.

---

*RISA Institution of Applied Sciences — Curriculum Development Draft*
