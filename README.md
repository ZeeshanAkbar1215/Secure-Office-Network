#Secure Office Network

#Project Overview

This project demonstrates a secure office network designed and simulated in Cisco Packet Tracer. It separates office departments into VLANs and applies basic network security controls to restrict guest access to internal office networks.

#Network Design

The network includes one router, one Layer 2 switch, and eight PCs distributed across four departments.

Department| VLAN ID| Network| Default Gateway
Administration| 10| 192.168.10.0/24| 192.168.10.1
HR| 20| 192.168.20.0/24| 192.168.20.1
IT| 30| 192.168.30.0/24| 192.168.30.1
Guest| 40| 192.168.40.0/24| 192.168.40.1

#Technologies Used

- Cisco Packet Tracer
- VLAN segmentation
- Router-on-a-Stick inter-VLAN routing
- DHCP for automatic IP address assignment
- Extended Access Control List (ACL) for guest network isolation
- Switch port security and unused-port hardening, where configured

#Security Features

- Departmental network segmentation using VLANs.
- Centralized inter-VLAN routing through router subinterfaces.
- Guest network access restricted to internal Administration, HR, and IT networks using an ACL.
- Unused switch ports shut down, where configured.

#Testing

The following checks were performed during project verification:

- Router subinterfaces were up/up.
- DHCP assigned IP addresses to the eight PCs.
- Guest PC connectivity to its default gateway was successful.
- Guest access to the Administration network was blocked as intended.

#Project File

The Cisco Packet Tracer simulation file (".pkt") and network topology screenshot are intended to be included in this repository.

#Learning Outcomes

This project provided practical experience with VLAN configuration, inter-VLAN routing, DHCP, ACLs, and basic switch security.

Author

Computer Science student | Networking and Cybersecurity learner
