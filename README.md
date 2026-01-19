# Basic LAN with Static IPs

This is my first networking labs using Cisco Packet Tracer.

## Objective
To build a simple local area network where two PCs can communicate through a switch.

## Topology 
- 1 Cisco 2960 IOS15 switch
- 2 PCs

## IP Addressing 
|Device| IP Address|
|------|-----------|
|PC0 | 192.168.1.10|
|PC1 | 192.168.1.11|

## Steps
1. Added one switch and two PCs in Cisco Packet Tracer
2. Connected devices using copper straight-through cables
3. Assigned static IP addresses
4. Tested connectivity using ping

## Verification 
- Successful ping between PC0 and PC1

## What I Learned
- How devices communicate within the same subnet using IP addresses
- How switches forward traffic between devices on a local network
- Why correct IP addressing is essential for devices to reach each other
- How to use ping as a basic troubleshooting tool to verify connectivity

## Why This Is Important 
This lab shows the fundamental building block of networking. 
If devices cannot communicate on a local network, higher-level services such
as internet access, applications and security controls will not function as intended.

Therefore, understanding how to assign IP addresses and verify connectivity is essential 
for diagnosing network issues. 
