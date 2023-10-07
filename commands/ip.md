# Mikrotik – RouterOS - CLI - `/ip` - IPv4 services

IP options

- [Home menu level](#home-menu-level)
- [Fast typing shortcut](#fast-typing-shortcut)
- [Sub-menus](#sub-menus)
- [Parameters](#parameters)

## Home menu level

`/ip` 

## Fast typing shortcut

`/ip`

## Sub-menus

- [Main](#main)
- [Authentication, Authorization, Accounting](#authentication-authorization-accounting): hotspot (captive portal)
- [Diagnostics, monitoring and troubleshooting](#diagnostics-monitoring-and-troubleshooting): traffic-flow (statistics)
- [Extended Features](#extended-features): Back to home (VPN access), SMB
- [Firewall and Quality of Service](#firewall-and-quality-of-service): firewall, kid-control, packing, UPnP
- [IPv4 and IPv6 Fundamentals](#ipv4-and-ipv6-fundamentals): address, pool, route, settings
- [Management tools](#management-tools): SSH server
- [Network Management](#network-management): ARP, DDNS, DHCP, DNS, HTTP Proxy
- [Routing](#routing): VRF
- [System Information and Utilities](#system-information-and-utilities): Neighbors (MNDP, CDP, LLDP), TFTP server, services
- [Virtual Private Networks](#virtual-private-networks): IPSEC
- [Other](#other): Socks Proxy

### Main
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/..`](root-level.md) | `/..` | go up to root |  |

### Authentication, Authorization, Accounting
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip hotspot`](https://help.mikrotik.com/docs/pages/viewpage.action?pageId=56459266) | `/ip h` | HotSpot servers management | Captive portal |

### Diagnostics, monitoring and troubleshooting
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip traffic-flow`](https://help.mikrotik.com/docs/display/ROS/Traffic+Flow) | `/ip tr` |  | Statistical information about packets that pass through the router |     

### Extended features
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip cloud`](https://help.mikrotik.com/docs/display/ROS/Back+To+Home) | `/ip c` |  | Back to home - VPN |
| [`/ip smb`](https://help.mikrotik.com/docs/display/ROS/SMB) | `/ip sm` |  | SMB (shares) - RouterOS only supports SMB v1.0 and v2.002|

### Firewall and Quality of Service
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip firewall`](https://help.mikrotik.com/docs/display/ROS/Basic+Concepts) | `/ip fi` | Firewall management |  |
| [`/ip kid-control`](https://help.mikrotik.com/docs/display/ROS/Kid+Control) | `/ip k` | Kid control settings |  |
| [`/ip packing`](https://help.mikrotik.com/docs/display/ROS/IP+packing) | `/ip pa` | Packet packing settings |  |
| [`/ip upnp`](https://help.mikrotik.com/docs/display/ROS/UPnP) | `/ip u` | Universal Plug and Play |  |

### IPv4 and IPv6 Fundamentals
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip address`](https://help.mikrotik.com/docs/display/ROS/IP+Addressing) | `/ip ad` | Address management | IP Addressing |         
| [`/ip pool`](https://help.mikrotik.com/docs/display/ROS/IP+Pools) | `/ip po` | IP address pool | IP Pools |
| [`/ip route`](https://help.mikrotik.com/docs/display/ROS/IP+Routing) | `/ip r` | Route management | IP Routing |
| [`/ip settings`](https://help.mikrotik.com/docs/display/ROS/IP+Settings) | `/ip set` |  | IP Settings |

### Management tools
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip ssh`](https://help.mikrotik.com/docs/display/ROS/SSH) | `/ip s` | SSH settings | SSH server |

### Network Management
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip arp`](https://help.mikrotik.com/docs/display/ROS/ARP) | `/ip ar` | ARP entries management |  |
| [`/ip cloud`](https://help.mikrotik.com/docs/display/ROS/Cloud) | `/ip c` |  | Mikrotik Dynamic DNS (DDNS) |
| [`/ip dhcp-client`](https://help.mikrotik.com/docs/display/ROS/DHCP#DHCP-DHCPClient) | `/ip dhcp-c` | DHCP client settings |  |
| [`/ip dhcp-relay`](https://help.mikrotik.com/docs/display/ROS/DHCP#DHCP-DHCPRelay) | `/ip dhcp-r` | DHCP relay settings |  |    
| [`/ip dhcp-server`](https://help.mikrotik.com/docs/display/ROS/DHCP#DHCP-DHCPServer) | `/ip dh` | DHCP server settings |  |
| [`/ip dns`](https://help.mikrotik.com/docs/display/ROS/DNS) | `/ip dn` | DNS settings |  |
| [`/ip proxy`](https://help.mikrotik.com/docs/display/ROS/Proxy) | `/ip p` |  | HTTP Proxy (for FTP and HTTP protocols) |

### Routing
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip vrf`](https://help.mikrotik.com/docs/pages/viewpage.action?pageId=328206) | `/ip v` |  | multiple Virtual Routing and Forwarding instances on a single router |

### System Information and Utilities
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip neighbor`](https://help.mikrotik.com/docs/display/ROS/Neighbor+discovery) | `/ip n` |  | Neighbors (MNDP, CDP, LLDP) |
| [`/ip tftp`](https://help.mikrotik.com/docs/display/ROS/TFTP) | `/ip tf` | TFTP server |  |
| [`/ip service`](https://help.mikrotik.com/docs/display/ROS/Services) | `/ip ser` | IP services |  |

### Virtual Private Networks
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip ipsec`](https://help.mikrotik.com/docs/display/ROS/IPsec) | `/ip i` | IP security |  |

### Other
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ip socks`](https://help.mikrotik.com/docs/display/ROS/First+Time+Configuration) | `/ip so` | SOCKS version 4 proxy  |  |


## Parameters

Invoke with : `/ip [parameter]`

The following command parameters are accepted:

| **Parameter** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| **export** | e | Print or save an export script that can be used to restore configuration | |    

## Note
- Not official - May be incomplete.
- Type `/ip` and use `[Tab]` twice for possible completions. 

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of SIA Mikrotīkls, Latvia
