🌐 Ministry LAN Network Design & Implementation
📌 Overview

This project presents a complete LAN network design and implementation for a ministry environment consisting of multiple departments and buildings.

The network is designed using:

 - Subnetting (IP addressing scheme)
 - Hierarchical Network Model (Core, Distribution, Access)
 - VLAN segmentation
 - DHCP, EtherChannel, and security technologies

The goal is to ensure a network that is secure, scalable, reliable, and high-performance.

🎯 Objectives
 - Design an efficient subnetted IP addressing scheme
 - Implement LAN technologies to solve network issues
 - Ensure inter-department communication
 - Apply network security mechanisms
 - Build a scalable and fault-tolerant network

🧮 Task 1: Subnetted IP Addressing Scheme

📊 Borrow Bits Calculation
  - Required subnets: 7
  - Formula:
       2^n - 2 ≥ required subnets
 - Result:
   - Borrow bits = 4
   - Subnets = 16
   - Usable subnets = 14
     
🌐 Subnet Mask
  - Binary: 11111111.11111111.11110000.00000000
  - Decimal: 255.255.240.0 (/20)
    
🖥️ Host Calculation
 - Total hosts per subnet: 4096
 - Usable hosts: 4094
   
🔢 Subnet Increment
  - Block size = 16

🖧 Task 2: LAN Technologies & Infrastructure
🔧 Hardware Used
 - Core Layer: Cisco Catalyst 3560 Multilayer Switch
 - Distribution Layer: Cisco Catalyst 3560
 - Access Layer: Cisco Catalyst 2960
 - Wireless: Cisco Access Points
 - Servers:
   - DHCP Server
   - Public Record Server
   - Financial Server
     
⚙️ Key LAN Technologies

🔹 VLAN
 - Separates departments into secure networks
 - Reduces congestion
 - Improves security
   
🔹 DHCP
 - Automatic IP assignment
 - Prevents IP conflicts
 - Simplifies management
   
🔹 EtherChannel
 - Combines multiple links
 - Increases bandwidth
 - Provides redundancy
   
🔗 Task 3: Hierarchical Network Design

🧱 3-Tier Architecture

🔹 Core Layer
 - Network backbone
 - High-speed routing
 - Connects all buildings
   
🔹 Distribution Layer
 - VLAN routing
 - Traffic control between departments
   
🔹 Access Layer
 - Connects end devices (PCs, printers, APs)
 - Applies security policies

✅ Benefits
 - Reduced congestion
 - Improved security
 - Fault isolation
 - Easy troubleshooting
 - Scalability
   
📈 Task 4: Scalability Analysis

The network supports future expansion through:
 - Adding new VLANs
 - Expanding departments/buildings
 - Adding more devices via DHCP
 - Increasing wireless coverage
  
⚡ Task 5: LAN Infrastructure Performance

🔁 Fault Tolerance
 - Implemented using EtherChannel
 - Provides backup links
 - Prevents network failure
   
🚀 High-Speed Links
 - Aggregated links increase bandwidth
 - Faster communication between buildings

🔐 Task 6: LAN Security Technologies

🛡️ 1. VLAN Segmentation
 - Isolates departments
 - Prevents unauthorized access
   
🔒 2. Port Security (Violation Shutdown)
 - Restricts MAC addresses
 - Shuts down unauthorized ports
   
🔌 3. Switchport Nonegotiate
 - Disables DTP
 - Prevents VLAN hopping attacks
   
📶 4. WPA2 Wireless Security
 - Encrypts Wi-Fi traffic
 - Secures guest and staff connections
   
🧪 Task 7: Suitability of LAN Technologies

✔️ VLAN
 - Improves security & organization
 - Prevents cross-department access
   
✔️ DHCP
 - Automates IP management
 - Reduces configuration errors
   
✔️ EtherChannel
 - Improves speed & reliability
 - Prevents single point of failure
   
✔️ Blackhole VLAN
 - Secures unused ports
 - Prevents unauthorized access
   
✔️ WPA2
 - Protects wireless network
   
✔️ Nonegotiate
 - Secures trunk links
   
✔️ Port Security
 - Blocks unauthorized devices
   
🏆 Conclusion

The proposed LAN design successfully delivers:

 - ✅ High performance
 - 🔒 Strong security
 - 📈 Scalability
 - 🔁 Reliability

By combining VLAN, DHCP, EtherChannel, and security mechanisms, the network ensures efficient communication across all departments while protecting sensitive data.

👩‍💻 Author

Developed by Sofea Aleeya









