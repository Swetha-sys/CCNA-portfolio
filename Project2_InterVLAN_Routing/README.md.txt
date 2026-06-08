# CCNA Project 2 - Inter-VLAN Routing

## Objective

Enable communication between different VLANs using Router-on-a-Stick.

## Devices Used

- 1 Router 2811
- 1 Switch 2960
- 6 PCs

## VLANs

- VLAN 10 - ADMIN
- VLAN 20 - HR
- VLAN 30 - GUEST

## Configuration

Configured trunking between switch and router.

Configured router subinterfaces:

- Fa0/0.10
- Fa0/0.20
- Fa0/0.30

Configured default gateways on all PCs.

## Verification

Successfully pinged:

192.168.10.10 → 192.168.20.10

## Concepts Learned

- VLAN
- Trunking
- 802.1Q
- Router-on-a-Stick
- Inter-VLAN Routing