# EIGRP--routing-lab

## Overview 
Cisco EIGRP routing lab demonstrating neighbor adjacency, route propagation, and verification commands using Packet Tracer.

## Lab Objectives 
-Configure router hostnames 
-Configure interface IP addresses 
-Configure EIGRP routing 
-Verify neighbor adjacency 
-Verify routing tables 
## Key Commands Used 
### Basic Router Setup
hostname R1
interface g0/0
ip address 10.1.1.1 255.255.255.0
no shutdown 
### EIGRP Configuration 
router eigrp 100
network 10.1.1.0
no auto-summary
### Verification
show ip eigrp neighbors 
show ip route 
show ip protocols 
## What I Learned 
How EIGRP establishes neighbor adjacency between routers 
How routes are exchanged using the EIGRP routing protocols 
How to verify routing using commands like show ip route and show ip eigrp neighbors.
How dynamic routing updates tables automatically
## Topology 
<img width="631" height="334" alt="image" src="https://github.com/user-attachments/assets/eb6dc967-4d5d-45b9-b605-6639df8505a9" />
