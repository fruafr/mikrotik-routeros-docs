# Mikrotik – RouterOS - CLI - `/interface` - Interfaces

- [Home menu level](#home-menu-level)
- [Fast typing shortcut](#fast-typing-shortcut)
- [Sub-menus](#sub-menus)
- [Parameters](#parameters)

## Home menu level

`/interface`

## Fast typing shortcut

`/in`

## Sub-menus

- [Main](#main) : list, detect-internet
- [Authentication, Authorization, Accounting](#authentication-authorization-accounting): dot1x
- [Bridging and Switching](#bridging-and-switching): bridge, macsec, vlan, vxlan
- [Extended features](#extended-features): veth (container)
- [High Availability Solutions](#high-availability-solutions): bonding, vrrp
- [Mobile Networking](#mobile-networking): lte, ppp
- [Multiple Protocol Label Switching (MPLS)](#multiple-protocol-label-switching-mpls): vpls
- [Virtual Private Networks](#virtual-private-networks): 6to4, EOIP, GRE, IPIP, L2TP, OpenVPN, PPoE, PPTP, SSTP, Wireguard
- [Wired Connections](#wired-connections): Ethernet, pwr-line
- [Wireless](#wireless): Wireless, Mesh (HWMP+)

### Main
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/..`](root-level.md) | `/..` | go up to root |  |
| [`/interface list`](https://help.mikrotik.com/docs/display/ROS/Interface+Lists) | `/in li` |  |  |
| [`/interface detect-internet`](https://help.mikrotik.com/docs/display/ROS/Detect+Internet) | `/in de` |  | Diagnostic tool that categorizes monitored interfaces |

### Authentication, Authorization, Accounting
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface dot1x`](https://help.mikrotik.com/docs/display/ROS/Dot1X) | `/in d` |  | IEEE 802.1X standard - Port-based network access control using EAP |

### Bridging and Switching
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface bridge`](sub/interface.bridge.md) | `/in b` | Bridge interfaces |  |
| [`/interface macsec`](https://help.mikrotik.com/docs/display/ROS/MACsec) | `/in ma` |  | MACsec (Media Access Control Security) protocol |
| [`/interface vlan`](sub/interface.vlan.md) | `/in vl` | Virtual LAN interfaces |  |
| [`/interface vxlan`](https://help.mikrotik.com/docs/display/ROS/VXLAN) | `/in v` |  | Virtual eXtensible Local Area Network (VXLAN) |

### Extended features
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface veth`](https://help.mikrotik.com/docs/display/ROS/Container) | `/in veth` |  | Virtual Ethernet interface in containers |

### High Availability Solutions
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface bonding`](https://help.mikrotik.com/docs/display/ROS/Bonding) | `/in bo` | Interface bonding |  |
| [`/interface vrrp`](https://help.mikrotik.com/docs/display/ROS/VRRP) | `/in vr` |  | Virtual Router Redundancy Protocol (VRRP) |

### Mobile Networking
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface lte`](https://help.mikrotik.com/docs/display/ROS/LTE) | `/in lte` |  | LTE |
| [`/interface ppp-client`](https://help.mikrotik.com/docs/display/ROS/PPP) | `/in ppp-c` | PPP client | Point-to-Point Protocol (PPP) Client |
| [`/interface ppp-server`](https://help.mikrotik.com/docs/display/ROS/PPP) | `/in ppp-s` | PPP server | Point-to-Point Protocol (PPP) Server |

### Multiple Protocol Label Switching (MPLS)
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface vpls`](https://help.mikrotik.com/docs/display/ROS/VPLS) | `/in vp` |  | Virtual Private Lan Service (VPLS) interface can be considered a tunnel interface just like the EoIP interface |

### Virtual Private Networks
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface 6to4`](https://help.mikrotik.com/docs/display/ROS/6to4) | `/in 6` |  | 6to4 |
| [`/interface eoip`](https://help.mikrotik.com/docs/display/ROS/EoIP) | `/in eoip` | Ethernet over IP tunnel interface |  |
| [`/interface eoipv6`](https://help.mikrotik.com/docs/display/ROS/EoIP) | `/in eoipv` |  | Ethernet over IP tunnel interface IPv6 |
| [`/interface gre`](https://help.mikrotik.com/docs/display/ROS/GRE) | `/in gre` |  | GRE |
| [`/interface gre6`](https://help.mikrotik.com/docs/display/ROS/EoIP) | `/in g` |  |  |
| [`/interface ipip`](https://help.mikrotik.com/docs/display/ROS/IPIP) | `/in ipip` | IP over IP tunnel interfaces |  |
| [``/interface ipipv6`](https://help.mikrotik.com/docs/display/ROS/IPIP) | `/in ipipv` |  | IP over IP tunnel interfaces IPv6 |
| [`/interface l2tp-client`](https://help.mikrotik.com/docs/display/ROS/L2TP) | `/in l2tp-c` | Layer Two Tunneling Protocol's client |  |
| [`/interface l2tp-ether`](https://help.mikrotik.com/docs/display/ROS/L2TP) | `/in l2tp-e` | Layer Two Tunneling Protocol version 3 (L2TPv3) ethernet pseudowires |  |
| [`/interface l2tp-server`](https://help.mikrotik.com/docs/display/ROS/L2TP) | `/in l` | Layer Two Tunneling Protocol's server |  |
| [`/interface ovpn-client`](sub/interface.ovpn-client.md) | `/in ovpn-c` |  | OpenVPN Client |
| [`/interface ovpn-server`](sub/interface.ovpn-server.md) | `/in ovpn-s` |  | OpenVPN Server |
| [`/interface pppoe-client`](https://help.mikrotik.com/docs/display/ROS/PPPoE) | `/in pppoe-c` | PPPoE client interfaces |  |
| [`/interface pppoe-server`](https://help.mikrotik.com/docs/display/ROS/PPPoE) | `/in pppoe-s` | PPPoE server |  |
| [`/interface pptp-client`](https://help.mikrotik.com/docs/display/ROS/PPTP) | `/in pptp-c` | PPTP client |  |
| [`/interface pptp-server`](https://help.mikrotik.com/docs/display/ROS/PPTP) | `/in pptp-server` | PPTP server |  |
| [`/interface sstp-client`](https://help.mikrotik.com/docs/display/ROS/SSTP) | `/in sstp-client` |  | SSTP client |
| [`/interface sstp-server`](https://help.mikrotik.com/docs/display/ROS/SSTP) | `/in sstp-server` |  | SSTP server |
| [`/interface wireguard`](sub/interface.wireguard.md) | `/in wireg` |  | Wireguard VPN |

### Wired Connections
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface ethernet`](sub/interface.ethernet.md) | `/in et` | Ethernet interfaces |  |
| [`/interface pwr-line`](https://help.mikrotik.com/docs/display/ROS/PWR+Line) | `/in pwr`| | PWR-Line |

### Wireless
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/interface wireless`](sub/interface.wireless.md) | `/in wirel` | Wireless interface |  |
| [`/interface mesh`](https://help.mikrotik.com/docs/pages/viewpage.action?pageId=8978441) | `/in me` |  | HWMP+ is a **MikroTik specific** layer-2 routing protocol for wireless mesh networks. It is based on Hybrid Wireless Mesh Protocol (HWMP) from IEEE 802.11s draft standard |

## Parameters

Invoke with : `/interface [parameter]` or `/in [parameter]`

The following command parameters are accepted:

| **Parameter** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| **blink** | bl |  |  | 
| **comment** | c | Set comment for items |  | 
| **disable** | di | Disable interface |  |
| **edit** | ed |  |  |
| **enable** | en | Enable interface |  |
| **export** | ex | Print or save an export script that can be used to restore configuration |  |
| **find** | f |  |  |
| **get** | g | Gets value of item's property | | 
| [**monitor-traffic**](https://help.mikrotik.com/docs/display/ROS/Interface+stats+and+monitor-traffic) | m | Monitor traffic |  |
| **print** | p | Print interface summary |  |
| **reset** | reset |  |
| **reset-counters**| reset- |  |
| **set** | se | Change item properties |  |

- For details on general commands: [General commands](general-commands.md)

## Note
- Not official - May be incomplete.
- Type `/interface` and press `[Tab]` for possible completions. 

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)

