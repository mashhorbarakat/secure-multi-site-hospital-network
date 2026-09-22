# Secure Multi-Site Hospital Network

A network security lab built in Cisco Packet Tracer to simulate secure communication between two hospital locations.

**Author:** Mashhor Barakat  
**Project type:** Academic lab / Cybersecurity portfolio  
**Tool:** Cisco Packet Tracer

## Project Overview

This project connects two hospital locations through a simulated ISP network. It demonstrates network segmentation, access restrictions, switch port security, and encrypted site-to-site communication.

The first location contains a Manager PC and a Staff PC. The second location contains two departmental PCs.

## Network Topology

![Hospital Network Topology](Network%20Photo.png)

## Security Features

- **VLAN Segmentation:** Separates the manager, staff, and second department into different network segments.
- **Access Control Lists (ACLs):** Restrict traffic to protect sensitive resources, including the Manager PC.
- **Port Security:** Uses sticky MAC address learning to restrict devices on the protected switch port.
- **Unused Port Shutdown:** Disables unused switch ports.
- **Site-to-Site IPsec VPN:** Protects traffic between the hospital locations across the simulated ISP network.

## Project Files

- [Project Report (PDF)](Mashhor%20Barakat%20Secure%20Multi-Site%20Hospital%20Network.pdf) — Project overview, security features, and documented test results.
- [Cisco Packet Tracer Lab](Cisco%20Packet%20Tracer%20Hospital%20Network.pkt) — Network topology and device configurations.
- [Network Photo](Network%20Photo.png) — Overview of the network layout.

## Testing and Verification

The project documentation covers:

- Connectivity checks using ping.
- Traffic restrictions enforced by ACLs.
- Port security behavior when an unauthorized device is connected.
- VPN verification using IKE/IPsec status and packet counters.

See the PDF report for screenshots and test results.

## How to Explore the Project

1. Read the PDF report for the project scenario and testing details.
2. View the network topology image.
3. Download the `.pkt` file and open it in a compatible version of Cisco Packet Tracer.
4. Inspect the router and switch configurations and repeat the documented tests.

## Areas Practiced

- IP addressing and network segmentation.
- Router and switch configuration.
- Access control and switch port security.
- Site-to-site VPN configuration.
- Network troubleshooting and technical documentation.

## Lab Scope

This is an educational simulation using a fictional hospital scenario. It is not a production hospital deployment.
