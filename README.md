# OSPF Implementation on Enterprise WAN

## 📌 Project Overview
This project demonstrates the design and simulation of an Enterprise Wide Area Network (WAN) connecting a Head Office to four branch offices. The topology relies on **OSPF (Open Shortest Path First)** for dynamic routing and redundancy, with specific **Static Route** manipulation to control traffic engineering policies.

**Tools Used:** Cisco Packet Tracer 8.2 (or your version)

## 🎯 Key Features
- **Partial Mesh Topology:** Designed for high availability.
- **Dynamic Routing:** OSPF Area 0 configured for automatic failover.
- **Traffic Engineering:** A static route was implemented to force traffic from Head Office to Branch 2 via an indirect path (Head Office -> Branch 1 -> Branch 2), satisfying the project's complex routing requirement.
- **Hardware Upgrade:** Utilized `NM-1SS` modules to expand router serial capabilities.

## 📸 Network Topology
![Network Topology](images/topology.png)
*(Make sure the filename matches your uploaded image exactly)*

## 🚀 How to Run
1. Download the file `Enterprise_WAN_Simulation.pkt` from this repository.
2. Open it in **Cisco Packet Tracer**.
3. You can ping between PC0, PC1, and PC2 to verify full connectivity.
4. Run a `traceroute` from the Head Office Router to `192.168.8.10` to observe the static route path manipulation.

## 📄 Project Report
For a detailed explanation of the configuration, challenges, and testing results, please view the full project report:
[Download Project Report (PDF)](docs/Project_Report.pdf)

---
**Author:** [Your Name]
**Course:** Routing and Switching
