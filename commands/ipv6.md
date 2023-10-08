# Mikrotik – RouterOS - CLI - `/ipv6` - IPv6 services

IP options

- [Home menu level](#home-menu-level)
- [Fast typing shortcut](#fast-typing-shortcut)
- [Sub-menus](#sub-menus)
- [Parameters](#parameters)

## Home menu level

`/ipv6`

## Fast typing shortcut

`/ipv`

## Sub-menus

- [Main](#main)
- [Firewall and Quality of Service](#firewall-and-quality-of-service): firewall
- [IPv4 and IPv6 Fundamentals](#ipv4-and-ipv6-fundamentals): address, IPv6 neighbor discovery, pool, route, settings
- [Network Management](#network-management): DHCP


### Main
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/..`](root-level.md) | `/..` | go up to root |  |

### Firewall and Quality of Service
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ipv6 firewall`](sub/ip.firewall.md) | `/ipv f`  |  | IPv6 Firewall Management |

### IPv4 and IPv6 Fundamentals
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ipv6 address`](https://help.mikrotik.com/docs/display/ROS/IP+Addressing) | `/ipv a` |  | IPv6 Addressing |
| [`/ipv6 nd`](https://help.mikrotik.com/docs/display/ROS/IPv6+Neighbor+Discovery) | `/ipv nd` | Neighbor Discovery |  |
| [`/ipv6 neighbor`](https://help.mikrotik.com/docs/display/ROS/Neighbor+discovery) | `/ipv ne` | neighbors | Neighbors Discovery |
| [`/ipv6 route`](https://help.mikrotik.com/docs/display/ROS/IP+Routing) | `/ipv ro` |  | IPv6 Routing |
| [`/ipv6 pool`](https://help.mikrotik.com/docs/display/ROS/IP+Pools) | `/ipv po` | IPv6 address pools |  |
| [`/ipv6 settings`](https://help.mikrotik.com/docs/display/ROS/IP+Settings) | `/ipv se` |  | IPv6 Settings |

### Network Management
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/ipv6 dhcp-client`](https://help.mikrotik.com/docs/display/ROS/DHCP#DHCP-DHCPv6Client) | `/ipv dhcp-c` | DHCPv6 client settings |  |
| [`/ipv6 dhcp-relay`](https://help.mikrotik.com/docs/display/ROS/DHCP) | `/ipv dhcp-r` | DHCPv6 relay settings |  |
| [`/ipv6 dhcp-server`](https://help.mikrotik.com/docs/display/ROS/DHCP#DHCP-DHCPv6Server) | `/ipv d` | DHCPv6 server settings |  |

## Parameters

Invoke with : `/ipv6 [parameter]` or `/ipv [parameter]`

The following command parameters are accepted:

| **Parameter** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| **export** | e | Print or save an export script that can be used to restore configuration | |    

## Note
- Not official - May be incomplete.
- Type `/ipv6` and press `[Tab]` for possible completions. 

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)

