# ospf-three-router-network
Three-router network implementation using OSPF in Cisco Packet Tracer, demonstrating dynamic routing, network redundancy, route convergence, and troubleshooting.
 Pkt link: https://drive.google.com/file/d/1YGwtl5Y56yGNwnt0ofV9VDSPeL71UbBY/view?usp=drive_link

## Project Overview

This project involves designing and configuring a three-router network using **Open Shortest Path First (OSPF)** in Cisco Packet Tracer.

The network uses a triangular topology connecting three LANs through three routers. OSPF was configured to enable dynamic routing, allowing routers to automatically exchange routing information and learn about remote networks without manually configuring static routes.

The project also demonstrates network redundancy by simulating a router-to-router link failure and observing how OSPF selects an alternative path to maintain connectivity.

## What I Implemented

- Designed a three-router triangular network topology.
- Configured IPv4 addressing on router interfaces.
- Configured DHCP to automatically assign IP addresses to PCs.
- Configured OSPFv2 using a single area (Area 0).
- Assigned unique router IDs to all three routers.
- Advertised LAN and inter-router networks using OSPF network statements.
- Established and verified OSPF neighbor relationships.
- Examined routing tables to identify dynamically learned routes.
- Tested communication between devices across different LANs.
- Simulated a link failure using the `shutdown` command.
- Verified OSPF route reconvergence and alternative path selection.
- Restored the failed link and verified connectivity.

## Technologies and Tools

- Cisco Packet Tracer
- Cisco Routers
- Cisco 2960 Switches
- OSPFv2
- IPv4 Addressing and Subnetting
- DHCP
- Dynamic Routing

## Key Concepts Practised

- Link-state routing
- OSPF router IDs and areas
- OSPF neighbor relationships
- Wildcard masks
- Routing table analysis
- Dynamic route learning
- Network redundancy
- OSPF convergence and reconvergence
- Network troubleshooting

## Key Takeaway

This project helped me understand how dynamic routing works in a multi-router environment. I also learned that establishing connectivity between routers is different from enabling communication between the networks behind them.

The link-failure exercise demonstrated how OSPF can maintain network connectivity by selecting an alternative path when a direct link becomes unavailable.

## Project Series

**10 Weeks of Networking: From NetAcad Student to Network Builder**

- Week 1: Small Business Network
- Week 2: VLSM Growing Company Network
- Week 3: OSPF Configuration and Network Redundancy
