📌 Project Overview

This project focuses on designing and configuring a scalable multi-area network infrastructure in Cisco Packet Tracer. The network integrates:

OSPF routing areas
EIGRP routing domain
RIP routing domain
Route redistribution between protocols
DHCP services
NAT configuration
ACL-based traffic filtering
SMTP/DNS mail services
End-to-end connectivity testing

The project demonstrates practical implementation of enterprise networking concepts and routing interoperability.

1. Technologies & Protocols Used
Cisco Packet Tracer
OSPF
EIGRP
RIP
DHCP
NAT
ACLs
SMTP
DNS
VLSM Subnetting
🌐 Network Features
✅ Dynamic Routing

2. Implemented and verified:

OSPF routing
EIGRP routing
RIP routing

with proper route propagation between areas.

3. Route Redistribution

Configured redistribution between:

OSPF → EIGRP → RIP

allowing communication between different routing domains.

3. DHCP Configuration

DHCP pools were configured for multiple networks using dedicated servers for automatic IP assignment and gateway configuration.

4. NAT Implementation

NAT mapping and translation were configured to simulate internal-to-external communication.

5. ACL Security

Access Control Lists were applied to:

Block HTTP access for selected hosts/networks
Allow permitted devices to access services

demonstrating selective traffic filtering.

6. Email & DNS Services

SMTP and DNS services were configured and verified through successful email transmission between hosts.

7. Connectivity Verification

Connectivity tests included:

Ping verification
DHCP validation
Gateway reachability
Cross-network communication

across OSPF, EIGRP, and RIP domains.

8. Challenges Faced
IP overlap issues during subnetting
Complex redistribution configuration
ACL rules blocking unintended hosts
NAT implementation limitations across all hosts

9. Files Included
23i-2089_A.pdf     → Final project report
23i-2089_A.pkt     → Cisco Packet Tracer topology

10. How to Run
Open the .pkt file in Cisco Packet Tracer
Start simulation or realtime mode
Verify:
Routing tables
DHCP assignments
ACL behavior
NAT translations
Email communication
Use ping/web browser/mail tools for testing

12. Project Modules
VLSM & IP Addressing
OSPF Area Configuration
EIGRP Routing
RIP Routing
Redistribution
DHCP
NAT
ACL Security
SMTP/DNS Services
Connectivity Verification


