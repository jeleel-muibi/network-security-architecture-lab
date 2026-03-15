This repository explores secure network architecture concepts that later informed the HybridOps platform.

Platform overview → https://hybridops.tech/why  
Documentation → https://docs.hybridops.tech

---

# Secure Network Access Architecture Lab

Enterprise network security lab exploring segmented network design, access control, routing resilience and secure connectivity patterns.

The project models a multi-department organisational network using Cisco Packet Tracer to demonstrate how VLAN segmentation, routing policies and firewall controls can be combined to provide secure network access across distributed environments.

---

## Architecture Overview

The simulated network includes:

• Departmental network segmentation using VLANs  
• Distribution layer routing and gateway redundancy  
• Secure external connectivity with firewall policies  
• Wireless infrastructure integration  
• Voice network segmentation for IP telephony

---

## Network Segmentation

Departmental isolation is implemented through VLAN-based segmentation.

Configured VLANs include:

• VLAN 10 — Production  
• VLAN 20 — Administration  
• VLAN 30 — Finance  
• VLAN 40 — Wireless LAN  
• VLAN 50 — Voice services

Segmentation ensures that traffic between departments can be controlled and inspected through routing and firewall policies.

---

## Switching Architecture

The switching layer implements several enterprise switching patterns:

• Access and trunk port configuration  
• VLAN segmentation across access switches  
• EtherChannel link aggregation for redundancy and bandwidth  
• Spanning Tree protections for loop prevention

These mechanisms provide both scalability and resilience in the switching fabric.

---

## Routing Architecture

Inter-VLAN routing and gateway redundancy are implemented at the distribution layer.

Key capabilities include:

• Layer 3 routing between departmental VLANs  
• OSPF dynamic routing configuration  
• HSRP gateway redundancy for high availability

This design ensures network continuity even if a routing node becomes unavailable.

---

## DHCP and Address Management

Dynamic IP allocation is provided through VLAN-specific DHCP pools.

Each pool includes:

• Network address allocation  
• Default gateway configuration  
• Reserved address exclusions

This allows automated endpoint provisioning across segmented networks.

---

## Firewall and Traffic Control

Network access is controlled through firewall and routing policies.

Security mechanisms include:

• Network Address Translation (NAT) for external connectivity  
• Access Control Lists (ACLs) for traffic filtering  
• Controlled inter-VLAN communication policies

These controls demonstrate how segmented networks enforce security boundaries between departments.

---

## Voice Network

A dedicated Voice VLAN supports IP telephony services.

Features include:

• Voice traffic segmentation  
• DHCP configuration for IP phones  
• Telephony service configuration and extension assignment

Separating voice traffic improves both performance and security.

---

## Lab Environment

The architecture is implemented using:

• Cisco Packet Tracer simulation  
• Multi-layer switching topology  
• Segmented departmental networks  
• Simulated WAN edge connectivity

---

## Project Context

This project explores foundational concepts in secure enterprise network architecture including segmentation, routing resilience and access control.

Many of the design principles explored here later informed networking and security patterns used within the HybridOps platform.
