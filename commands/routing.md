# Mikrotik – RouterOS - CLI - `/routing` - Routing

[Mikrotik RouterOS documentation for Routing](https://help.mikrotik.com/docs/display/ROS/Routing)

- [Home menu level](#home-menu-level)
- [Fast typing shortcut](#fast-typing-shortcut)
- [Sub-menus](#sub-menus)
- [Parameters](#parameters)

## Home menu level

`/routing`

## Fast typing shortcut

`/ro`

## Sub-menus

- [Main](#main): BFD, BGP, Nexthop, OSPF, RIP, RPKI, 
- [IPv4 and IPv6 Fundamentals](#ipv4-and-ipv6-fundamentals): Routing stats
- [Multicast](#multicast): GMP, IGMP-Proxy, PIM-SM
- [Policy Routing](#policy-routing): Routing rule, routing table
- [Routing Debugging Tools](#routing-debugging-tools): fantasy, route
- [Routing Reference](#routing-reference): id
- [Routing Selection and Filters](#routing-selection-and-filters): filter

### Main
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/..`](root-level.md) | `/..` | go up to root |  |
| [`/routing bfd`](https://help.mikrotik.com/docs/display/ROS/BFD) | `/ro bf` |  | Bidirectional Forwarding Detection (BFD) |
| [`/routing bgp`](https://help.mikrotik.com/docs/display/ROS/BGP) | `/ro bg` |  | Border Gateway Protocol (BGP) - inter-domain dynamic routing system | 
| `/routing nexthop` | `/ro  n` |  | Nexthop | 
| [`/routing ospf`](https://help.mikrotik.com/docs/display/ROS/OSPF) | `/ro o` |  | OSPF is Interior Gateway Protocol (IGP) designed to distribute routing information between routers belonging to the same Autonomous System (AS). | 
| [`/routing rip`](https://help.mikrotik.com/docs/display/ROS/RIP) | `/ro ri`|  | RIP version 2 (RFC 2453).  Enables routers in an autonomous system to exchange routing information. Best path | 
| ['/routing rpki`](https://help.mikrotik.com/docs/display/ROS/RPKI) | `/ro rp` |  | Resource Public Key Infrastructure (RPKI) to Router Protocol defined in RFC8210. RTR is a very lightweight low memory footprint protocol, to reliably get prefix validation data from RPKI validators. | 

### IPv4 and IPv6 Fundamentals
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/routing stats`](https://help.mikrotik.com/docs/display/ROS/IP+Routing) | `/ro s` |  | IP Routing stats | 

### Multicast
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/routing gmp`](https://help.mikrotik.com/docs/display/ROS/Group+Management+Protocol) | `/ro g` |  | The Group Management Protocol allows any of the interfaces to become a receiver for the multicast stream | 
| [`/routing igmp-proxy`](https://help.mikrotik.com/docs/display/ROS/IGMP+Proxy) | `/ro ig`  |  | Internet Group Management Protocol (IGMP) proxy can implement multicast routing. It is forwarding IGMP frames and is commonly used when there is no need for a more advanced protocol like PIM. | 
| [`/routing pimsm`](https://help.mikrotik.com/docs/display/ROS/PIM-SM) | `/ro p` |  | Protocol Independent Multicast - Sparse Mode (PIM-SM or PIM) enables RouterOS to support multicast streaming over the network area. | 

### Policy Routing
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/routing rule`](https://help.mikrotik.com/docs/display/ROS/Policy+Routing) | `/ro r` |  | IP Routing rule | 
| [`/routing table`](https://help.mikrotik.com/docs/display/ROS/Policy+Routing) | `/ro t` |  | IP Routing table | 

### Routing Debugging Tools

- [Routing debugging tools](https://help.mikrotik.com/docs/display/ROS/Routing+Debugging+Tools)

| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/routing fantasy`](https://help.mikrotik.com/docs/pages/viewpage.action?pageId=74678282) | `/ro fa`  |  |  Generate large amount of routes for testing purposes | 
| [`/routing route`](https://help.mikrotik.com/docs/pages/viewpage.action?pageId=59965493) | `/ro  ro` |  | A read-only table that lists routes from all the address families as well as all filtered routes with all possible route attributes. | 

### Routing Reference

-[Routing Reference](https://help.mikrotik.com/docs/display/ROS/Routing+Reference)

| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/routing id`](https://help.mikrotik.com/docs/pages/viewpage.action?pageId=59965506) | `/ro id` |  | Global Router ID election configuration. | 

### Routing Selection and Filters

- [Routing Selection and Filters](https://help.mikrotik.com/docs/display/ROS/Route+Selection+and+Filters)

| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/routing filter`](https://help.mikrotik.com/docs/display/ROS/Route+Selection+and+Filters#RouteSelectionandFilters-RouteSelection) |  `/ro fi` |  | Routing filter implements script-like syntax | 

## Parameters

Invoke with : `/routing [parameter]` or `/ro [parameter]`


The following command parameters are accepted:

| **Parameter** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| **discourse** | d |  |  |
| **export** | e | Print or save an export script that can be used to restore configuration |  |  |
| **reinstall-fib** | re |  |  |

## Note
- Not official - May be incomplete.
- Type `/routing` and press `[Tab]` for possible completions. 

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)
