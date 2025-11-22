# Lab Topology

Purpose: Private host-only SOC lab for learning SIEM, logging, and detection.

## Network
- Subnet: 192.168.56.0/24
- Host-only gateway (host adapter): 192.168.56.1
- DHCP: disabled (using static IPs)

## Virtual Machines and IPs
- WIN-Endpoint: 192.168.56.10
- Ubuntu-Server: 192.168.56.11
- SIEM (Wazuh or SecurityOnion): 192.168.56.12
- Kali: 192.168.56.13

## Notes
- All VMs connected via VirtualBox Host-only Adapter.
- No internet required over host-only. Use NAT on a second adapter later if needed for updates.

## To Do
- Add simple diagram (screenshot from draw.io or hand sketch).
- Confirm ping between VMs once created.

## Screenshots
- VirtualBox Network Adapter (Host-only)
  "C:\Users\danie\OneDrive\Documents\GitHub\blue-lab\screenshots\2025-11-21_22h30_03.png"- Ubuntu Server static IP + ping tests
  
- Windows VM static IP + ping tests
  "C:\Users\danie\OneDrive\Documents\GitHub\blue-lab\screenshots\2025-11-21_22h30_23.png"- Kali VM static IP + ping tests