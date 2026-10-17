
# Day 02 - Switching Basics

## Objective
Understand how a switch learns MAC addresses
and forwards Ethernet frames.

## 1. MAC Address Learning
A switch learns the source MAC address from an
incoming Ethernet frame and associates it with
the incoming port in the relevant VLAN.

## 2. MAC Address Table
Command:
show mac address-table

This displays learned MAC addresses, VLANs,
and their associated switch ports.

## 3. Unknown Unicast
If the destination MAC is unknown, the switch
floods the frame out eligible ports in the same
VLAN, except the incoming port.

## 4. Practical Troubleshooting
- Check interface status.
- Generate traffic from the connected device.
- Verify the MAC address table.
- Check VLAN membership and connectivity.

## Key Takeaways
- Source MAC is used for learning.
- Destination MAC is used for forwarding.
- Unknown unicast flooding is VLAN-scoped.

## Status
Theory: Completed
Packet Tracer lab: Pending
