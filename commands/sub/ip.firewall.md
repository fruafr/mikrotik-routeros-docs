# Mikrotik – RouterOS - CLI - `/ip firewall` - Firewall management

Mikrotik RouterOS' documentation for :
    - [Firewall basic concepts](https://help.mikrotik.com/docs/display/ROS/Basic+Concepts).
    - [Firewall and Quality of Service](https://help.mikrotik.com/docs/display/ROS/Firewall+and+Quality+of+Service)

The `/ip firewall` and `/ipv6 firewall` are similar. You need to replace `/ip` by `/ipv6`.

- [Home menu level](#home-menu-level)
- [Fast typing shortcut](#fast-typing-shortcut)
- [Sub-menus](#sub-menus)
- [Parameters](#parameters)

## Home menu level

`/ip firewall`

## Fast typing shortcut

`/ip fi`

## Sub-menus

| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/..`](../ip.md) | `/..` | go up to ip |  |
|[`/ip firewall address-list`](https://help.mikrotik.com/docs/display/ROS/Address-lists) | `/ip fi a`  |    |  Address list |
|`/ip firewall calea` | `/ip fi ca`   |    | [Extra package](https://help.mikrotik.com/docs/display/ROS/Packages). United States Communications Assistance for Law Enforcement Act ([CALEA](https://wiki.mikrotik.com/wiki/CALEA)) compliance. |
|[`/ip firewall connection`](https://help.mikrotik.com/docs/display/ROS/Connection+tracking) | `/ip fi co`   |  Active connections  | Connection tracking  |
|[`/ip firewall filter`](https://help.mikrotik.com/docs/display/ROS/Filter) | `/ip fi f`  |  Firewall filters  |   |
|[`/ip firewall layer7-protocol`](https://help.mikrotik.com/docs/display/ROS/Layer7) | `/ip fi l`  |    | Layer 7 protocol  |
|[`/ip firewall mangle`](https://help.mikrotik.com/docs/display/ROS/Mangle) | `/ip fi m`  | The packet marking management  |   |
|[`/ip firewall nat`](https://help.mikrotik.com/docs/display/ROS/NAT) | `/ip fi n`  |  Network Address Translation  | NAT  |
|[`/ip firewall raw`](https://help.mikrotik.com/docs/display/ROS/RAW) | `/ip fi r`  |    | RAW  |
|[`/ip firewall service-port`](https://help.mikrotik.com/docs/display/ROS/Services) | `/ip fi s`  |  Service port management  |   |

## Parameters

Invoke with : `/ip firewall [parameter]` or `/ip fi [parameter]`

The following command parameters are accepted:

| **Parameter** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| **export** | e |  Print or save an export script that can be used to restore configuration  |   |

- For details on general commands: [General commands](general-commands.md)

## Note
- Not official - May be incomplete.
- Type `/ip firewall` and press `[Tab]` for possible completions. 

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)

