# Cisco CME VoIP Environment Project

This project demonstrates the implementation and configuration of a basic Cisco IP Telephony environment using Cisco Packet Tracer as part of an Ausbildung portfolio.

## 🛠️ Network Topology & Components
* **Router**: Cisco 2811 (Acting as Cisco CME and DHCP Server)
* **Switch**: Cisco 2960-24TT (Configured with Voice VLAN)
* **Endpoints**: 2x Cisco IP Phones (7960)

## ⚙️ Key Configurations
1. **Voice VLAN (VLAN 10)**: Created and assigned to switch ports (FastEthernet 0/1 - 0/3) to segregate voice traffic.
2. **DHCP Server**: Configured a DHCP pool (`192.168.10.0/24`) with **Option 150** pointing to the TFTP server (`192.168.10.1`).
3. **Cisco CallManager Express (CME)**: 
   - Enabled telephony service with `max-ephones 2` and `max-dn 2`.
   - Configured Directory Numbers (ephone-dn) for extensions.

## 📸 Documentation & Screenshots

* **Network Topology Overview:**
  ![Network Topology](01-Network-Topology.png)

* **Router DHCP & Core Setup:**
  ![Router Configuration](02-Router-DHCP-Configuration.png)

* **Switch Port Activation & VLAN Configuration:**
  ![Switch Configuration](03-Switch-Ports-Activation.png)

## 🚀 Author
Developed by **Karim Bourchkak** as part of professional training (*Ausbildung*).
