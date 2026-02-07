# Smart Office VLAN Network

## 📌 Overview
This project implements a VLAN-based office network using Cisco Packet Tracer with inter-VLAN routing, wireless access, and internal web hosting.

## Network Design
- VLAN 10: HR (192.168.10.0/24)
- VLAN 20: IT (192.168.20.0/24)
- VLAN 30: Sales (192.168.30.0/24)
- Router-on-a-Stick Inter-VLAN Routing
- WRT300N Wireless Access Point
- Internal Web Server

## Tools
- Cisco Packet Tracer
- CLI Configuration
- HTML/CSS

## Topology
Refer - topology.png

## 📁 Project Structure

```
Smart-Office-VLAN-Network/
├── packet_tracer/
│   └── smart_office.pkt
├── screenshots/
│   ├── topology.png
│   ├── ping_test.png
│   └── website.png
├── config/
│   ├── router.txt
│   └── switch.txt
├── website/
│   └── index.html
└── README.md
```


## How to Run
1. Open smart_office.pkt in Cisco Packet Tracer
2. Power on all devices
3. Test connectivity using ping
4. Open http://192.168.30.2 in browser

## ✅ Results
- Successful inter-VLAN communication
- Wireless client access
- Internal website hosted

## Author
Manya
