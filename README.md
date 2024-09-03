# SZABIST Karachi Campus Network Design

## Project Overview

This project involves designing and implementing the networking infrastructure for SZABIST Karachi campus, which includes multiple departments spread across seven different buildings. The goal is to create a robust, secure, and efficient network using Cisco Packet Tracer.

## Network Requirements

### 100 Campus Building
- **Labs:**
  - **CS Lab:** 58 PCs, 2 Printers, 1 FTP Server
  - **AI Lab:** 48 PCs, 1 Printer
  - **Lab-3:** 38 PCs, 2 Printers, 1 FTP Server
  - **Lab-4:** 35 PCs, 2 Printers
  - **Lab-5:** 35 PCs, 2 Printers, 1 FTP Server
  - **Lab-6:** 35 PCs
  - **Smart Lab:** 40 PCs, 1 Printer
  - **Gaming Lab:** 9 PCs, 2 Printers
- **Classrooms:** 20 classrooms, each with 1 PC
- **Departments:**
  - **Faculty:** 25 PCs, 4 Printers
  - **Academic:** 5 PCs, 3 Printers
  - **Administration:** 4 PCs
  - **IT:** 10 PCs, 2 Printers

### 99 Campus Building
- **Classrooms:** 18 classrooms, each with 1 PC
- **Departments:**
  - **Faculty:** 32 PCs, 6 Printers
  - **Academic:** 6 PCs, 2 Printers
  - **IT:** 4 PCs, 1 Printer
  - **Examination:** 12 PCs, 4 Printers
  - **Administration:** 2 PCs
- **Data Center:** 4 Servers (Web, ZABDESK, Email, CMS)
- **Edge Router:** Located in the 99 Campus Building

## Design Specifications

- **IP Addressing:** Use VLSM for efficient IP address allocation. Public IP pool: `11.11.11.0/30`. Private IP pools: `192.168.X.0/24` as needed.
- **VLANs:** Create VLANs for each department and lab for improved network management.
- **Routing:** Implement Inter-VLAN routing. Use single-area OSPF for dynamic routing.
- **DHCP:** Configure DHCP on the Edge Router or designated router for automatic IP allocation.
- **NAT:** Enable NAT on the Edge Router for internet connectivity.
- **ACLs:** Implement ACLs to restrict access to resources (e.g., Faculty printers, ZABDESK).
- **Port Security:** Enable port security for servers and lab devices.
- **Remote Management:** Configure remote management for routers and switches. Password protect all devices.

## Implementation Steps

1. **Design Network Topology:** Create a detailed network diagram including all devices, connections, and IP addresses.
2. **Configure VLANs and Subnets:** Set up VLANs and assign IP addresses using VLSM.
3. **Setup DHCP and NAT:** Configure DHCP and NAT services on the Edge Router.
4. **Implement Security Measures:** Apply ACLs, port security, and remote management settings.
5. **Test Connectivity:** Ensure all devices are reachable and functional, and verify that all security measures are effective.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Cisco Packet Tracer and Cisco Modeling Labs for network simulation tools
- SZABIST Karachi for providing the network requirements

For further details or questions, please contact [Rohail Rathore](mailto:rohailrathore10@hotmail.com).

