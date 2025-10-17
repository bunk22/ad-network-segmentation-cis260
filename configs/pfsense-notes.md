# pfSense Notes (sanitized)

Interfaces:
- WAN: NAT (VirtualBox)
- LAN (or VLAN 10): 10.10.10.1/24, DHCP 10.10.10.100-200
- (Optional) VLAN 20: 10.10.20.1/24, DHCP 10.10.20.100-200

Firewall examples:
- VLAN10 → allow DNS to DC, allow SMB to 10.10.10.10, allow Internet
- VLAN20 → block RFC1918, allow Internet only
