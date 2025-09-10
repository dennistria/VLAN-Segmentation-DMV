# VLAN-Segmentation-DMV

**Course:** CYB 210 – Network Defense  
**Tools:** Cisco Packet Tracer, VLANs, DHCP, NAT, RIP v2  

## Overview
Redesigned a DMV network to segment guest and video traffic while ensuring DHCP and NAT worked correctly.

## My Role
- Configured VLANs 50/70/80/150  
- Corrected DHCP pool exhaustion errors  
- Assigned static IPs to webcams  
- Verified routing and translations with CLI commands  

## Outcome
- Guest traffic isolated from DMV data  
- DHCP/APIPA errors eliminated  
- Video VLAN secured and fully functional  

## Files in this Repository
- **[VLAN-Segmentation-DMV.pkt](./VLAN-Segmentation-DMV.pkt)** → Cisco Packet Tracer project file  
- **[Project-Writeup.pdf](./Project-Writeup.pdf)** → Paper explaining requirements, design, and outcome  
- **[screenshots/](./screenshots/)** → VLAN table, DHCP bindings, ping test results  

## Proof (Screenshots)
![VLAN Configuration](./screenshots/Vlan-conf.png)  
*VLANs configured and verified with `show vlan brief`.*

![DHCP Configuration](./screenshots/Dhcp-conf.png)  
*DHCP scope active and bindings confirmed with `show ip dhcp binding`.*

## Reflection
This project showed me the importance of proper VLAN segmentation for both security and performance.
