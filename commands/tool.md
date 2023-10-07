# Mikrotik – RouterOS - CLI - `/tool` - Diagnostics tools

- Mikrotik RouterOS documentation for :
    - [Diagnostics, Monitoring and Troubleshooting](https://help.mikrotik.com/docs/display/ROS/Diagnostics%2C+monitoring+and+troubleshooting)
    - [Hardware](https://help.mikrotik.com/docs/display/ROS/Hardware)
    - [Management Tools](https://help.mikrotik.com/docs/display/ROS/Management+tools)
    - [System Information and Utilities](https://help.mikrotik.com/docs/display/ROS/System+Information+and+Utilities)

- [Home menu level](#home-menu-level)
- [Fast typing shortcut](#fast-typing-shortcut)
- [Sub-menus](#sub-menus)
- [Parameters](#parameters): Bandwidth/speed test, Dynamic DNS update, File fetching, Scan IP/MAC/telnet, profile CPU process, get SNMP values, Monitor traffic, pin, traceroute, Wake on LAN

## Home menu level

`/tool`

## Fast typing shortcut

`/too`

## Sub-menus

- [Main](#main)
- [Diagnostics, Monitoring and Troubleshooting](#diagnostics-monitoring-and-troubleshooting): Bandwidth server, graphing, network monitoring, packet sniffer, traffic generator, traffic monitor
- [Management tools](#management-tools): MAC server (Telnet, WinBox, Ping Server), Router Management Overlay Network (RoMON)
- [Mobile Networking](#mobile-networking): SMS  
- [System Information and Utilities](#system-information-and-utilities): E-mail


### Main
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/..`](root-level.md) | `/..` | go up to root | |

### Diagnostics, monitoring and troubleshooting
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/tool bandwidth-server`](https://help.mikrotik.com/docs/display/ROS/Bandwidth+Test) | `/too bandwidth-s` | Bandwidth tester service | |
| [`/tool graphing`](https://help.mikrotik.com/docs/display/ROS/Graphing) | `/too g`| System resource and traffic graphing | |
| [`/tool netwatch`](https://help.mikrotik.com/docs/display/ROS/Netwatch) | `/too n` | Network watching tool | Netwatch monitors the state of hosts on the network |
| [`/tool sniffer`](https://help.mikrotik.com/docs/display/ROS/Packet+Sniffer) | `/too sni` | Packet sniffering | Tool that can capture and analyze packets that are going to, leaving, or going through the router |
| [`/tool traffic-generator`](https://help.mikrotik.com/docs/display/ROS/Traffic+Generator) | `/too traffic-g`  |  | Allows evaluating the performance of DUT (Device Under Test) or SUT (System Under Test) |
| `/tool traffic-monitor` | `/too tr` | The traffic monitor tool | |

### Management tools
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/tool mac-server`](https://help.mikrotik.com/docs/display/ROS/MAC+server) | `/too mac-se` | MAC Telnet Server | MAC server section allows you to configure MAC Telnet Server, MAC WinBox Server and MAC Ping Server on RouterOS device |
| [`/tool romon`](https://help.mikrotik.com/docs/display/ROS/RoMON) | `/too r` |  | Router Management Overlay Network (RoMON) - establish an independent MAC layer peer discovery and data forwarding network |

### Mobile Networking
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/tool sms`](https://help.mikrotik.com/docs/display/ROS/SMS) | `/too sm` |  | Connect the GSM modem to the RouterOS device and use it to send and receive SMS messages |

### System Information and Utilities
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/tool e-mail`](https://help.mikrotik.com/docs/display/ROS/E-mail) | `/too e-` |  | allows sending e-mails from the router|

## Parameters

Invoke with : `/tool [parameter]` or `/to [parameter]`

The following command parameters are accepted:

| **Parameter** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [**bandwidth-test**](https://help.mikrotik.com/docs/display/ROS/Bandwidth+Test) | bandwidth-t | Run bandwidth test to remote router |  |
| [**dns-update**](https://help.mikrotik.com/docs/display/ROS/Dynamic+DNS) | d | Dynamic DNS update |  |
| **export** | ex | Print or save an export script that can be used to restore configuration |  |
| [**fetch**](https://help.mikrotik.com/docs/display/ROS/Fetch) | fe |  | Fetch is one of the console tools in Mikrotik RouterOS. It is used to copy files to/from a network device via HTTP, FTP or SFTP (Support for SFTP added on v6.45), it can also be used to send POST/GET requests and send any kind of data to a remote server. The HTTPS protocol is supported; by default, no certificate checks are made, but setting check-certificate to yes enables trust chain validation from the local certificate store. |
| **flood-ping** | fl | Send a lot of ICMP Echo packets and wait for response |  |
| [**ip-scan**](https://help.mikrotik.com/docs/display/ROS/IP+Scan) | i |  | scan networks based on some network prefix or by setting an interface to listen to. |
| [**mac-scan**](https://help.mikrotik.com/docs/display/ROS/MAC+server) | m | Scan for MAC addresses | Discovers all devices, which support MAC telnet protocol on the given network |
| [**mac-telnet**](https://help.mikrotik.com/docs/display/ROS/MAC+server) | mac-t  | MAC Telnet Client | provide access to a router that has no IP address set |
| [**ping**](https://help.mikrotik.com/docs/display/ROS/Ping) | ping | Send ICMP Echo packets |  |
| **ping-speed** | ping- | The ICMP bandwidth test |  |
| [**profile**](https://help.mikrotik.com/docs/display/ROS/Profiler) | p |  | Shows CPU usage for each process running in RouterOS |
| [**snmp-get**](https://help.mikrotik.com/docs/display/ROS/PoE-Out) | snmp-g |  | Get a specific SNMP OID value /tool snmp-get address=10.155.149.252 oid=1.3.6.1.4.1.14988.1.1.15.1.1.5.3 |
| [**snmp-walk**](https://help.mikrotik.com/docs/display/ROS/PoE-Out) | snmp-w |  | Request SNMP value. /tool snmp-walk address=10.155.149.252 oid=1.3.6.1.4.1.14988.1.1.15.1.1.5 |
| [**speed-test**](https://help.mikrotik.com/docs/display/ROS/Speed+Test) | s |  | Measure ping, jitter, TCP and UDP throughput from one MikroTik device, to another |
| [**torch**](https://help.mikrotik.com/docs/display/ROS/Torch) | to | Realtime traffic monitor | Can be used to monitor the traffic flow through an interface. *Traffic appears in torch is before it has been filtered by a Firewall* |
| [**traceroute**](https://help.mikrotik.com/docs/display/ROS/Traceroute) | trac | Trace route to host | Displays the list of the routers that packet travels through to get to a remote host |
| [**wol**](https://help.mikrotik.com/docs/display/ROS/Wake+on+LAN) | w |  | Wake On Lan. Send a specific frame (Magic Packet) to any MAC address of your choosing. If the target device supports Wake on LAN, it should wake up from sleep or shutdown state |

## Note
- Not official - May be incomplete.
- Type `/tool` and use `[Tab]` twice for possible completions. 

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of SIA Mikrotīkls, Latvia
