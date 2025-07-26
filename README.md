# Enterprise OSPF Network Simulation

## 🧾 Project Overview

This project simulates a scalable, enterprise-grade network topology designed and tested in Cisco Packet Tracer. 
It focuses on implementing a robust OSPF-based routing architecture across multiple departments and routing domains. 
The core design incorporates modular area segmentation, IP planning with /29 subnets, and the redistribution of other 
routing protocols like RIP into OSPF. This setup demonstrates practical networking concepts applied in real-world enterprise 
scenarios.

---

## 🛠️ Technologies & Concepts Used

- **OSPF (Open Shortest Path First)**
  - Multi-area configuration
  - ABR (Area Border Router) and ASBR (Autonomous System Boundary Router)
  - Inter-area and intra-area routing
  - Type 1, 2, 3, and 5 LSAs
  - Point-to-point vs broadcast network types

- **Stub and Totally Stubby Areas**
  - Reduced LSDB size
  - Default route injection
  - Prevented LSA flooding in constrained subnets

- **Routing Protocol Redistribution**
  - Static routes redistributed into OSPF
  - RIP routes redistributed into OSPF via ASBR
  - Subnet keyword usage for route accuracy

- **IP Addressing & Subnetting**
  - Use of /29 subnets for point-to-point links
  - Structured allocation to avoid overlap and simplify routing logic

- **Troubleshooting & Verification**
  - OSPF neighbor relationships
  - Route visibility and next-hop verification
  - Impact of interface network types on LSA propagation

---

## 🧠 Learning Outcomes

- Practical deployment of hierarchical OSPF design
- Implementation of stub area optimizations
- Troubleshooting OSPF database and routing table discrepancies
- Integration of multiple dynamic routing protocols in a hybrid setup

---

<img width="1820" height="991" alt="image" src="https://github.com/user-attachments/assets/276132e2-13b1-4914-ab51-bbf51e55f8fa" />

