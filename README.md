# 📡 Complete CCNA Packet Tracer Lab – From Basic to Advanced Configurations

This Packet Tracer project includes a comprehensive set of configurations that walk through nearly the entire CCNA 200-301 syllabus. It's structured in parts to show the progression from initial setup to advanced network services, routing protocols, Layer 2 and Layer 3 technologies, IPv6, and wireless implementation.


## 🔧 Configuration Breakdown

### ✅ Part 1: Initial Setup
- Hostname configuration for all devices
- `enable secret` using: yusiffuad
  - Type 9 hashing on routers and core/distribution switches
  - Type 5 on access switches
- Local user account: `cisco` with secret `ccna`
- Console login secured with local authentication
- Exec timeout of 30 minutes
- Logging synchronous enabled on console lines

### 🔁 Part 2: VLANs & Layer-2 EtherChannel
- VLAN creation and assignment across switches
- Layer 2 EtherChannel for link aggregation between switches

### 🌐 Part 3: IP Addressing, Layer-3 EtherChannel, and HSRP
- IP address configuration for all interfaces
- Layer-3 EtherChannel on distribution/core links
- Hot Standby Router Protocol (HSRP) for gateway redundancy

### 🌲 Part 4: Spanning Tree Protocol (RSTP)
- Rapid PVST+ configured
- STP root and standby bridges aligned with HSRP priorities
- PortFast and BPDU Guard enabled on host-facing ports

### 🛣️ Part 5: Static and Dynamic Routing
- Static routes, RIP, EIGRP, and OSPF routing configurations between routers

### ⚙️ Part 6: Network Services
- **DHCP** for dynamic IP allocation
- **DNS** for name resolution
- **NTP** for time synchronization
- **SNMP**, **Syslog**, and **FTP** setup
- **SSH** for secure device access
- **NAT** (static and dynamic) for internal-to-external communication

### 🔐 Part 7: Network Security
- ACLs for traffic filtering
- Layer-2 security features: port security, BPDU Guard

### 🌍 Part 8: IPv6 Configuration
- IPv6 addressing and routing

### 📶 Part 9: Wireless Configuration
- Wireless LAN Controller (WLC1) GUI access via https://10.0.0.7
  - Username: `yusiffuad`
  - Password: `yus1ff`
- Wireless configuration for access points and client devices

---

## 📂 Files
- `.pkt` file: Open with Cisco Packet Tracer (v8.2 or higher recommended)

## 🎯 Purpose
To help CCNA students and networking enthusiasts:
- Practice and understand core concepts hands-on
- Visualize real-world Cisco network setups
- Prepare for practical exam scenarios

---

## ✅ Author
**Yusif Fuad Kamara**  
Built as part of CCNA self-study and practical demonstration of skills.

Feel free to fork, use, or share. Credit is appreciated. 🙏

