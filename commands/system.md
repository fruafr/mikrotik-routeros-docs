# Mikrotik – RouterOS - CLI - `/system` - System operations

- Mikrotik RouterOS documentation for :
    - [Diagnostics, Monitoring and Troubleshooting](https://help.mikrotik.com/docs/display/ROS/Diagnostics%2C+monitoring+and+troubleshooting)
    - [Hardware](https://help.mikrotik.com/docs/display/ROS/Hardware)
    - [Management Tools](https://help.mikrotik.com/docs/display/ROS/Management+tools)
    - [System Information and Utilities](https://help.mikrotik.com/docs/display/ROS/System+Information+and+Utilities)

- [Home menu level](#home-menu-level)
- [Fast typing shortcut](#fast-typing-shortcut)
- [Sub-menus](#sub-menus)
- [Parameters](#parameters): Check installation, reset configuration, reboot/shutdown, serial console/ssh/telnet, create support file

## Home menu level

`/system`

## Fast typing shortcut

`/sy`

## Sub-menus

- [Main](#main)
- [Bridging and Switching](#bridging-and-switching): SwOS management (dual boot)
- [Diagnostics, Monitoring and Troubleshooting](#diagnostics-monitoring-and-troubleshooting): Router health, logging configuration, system resources, watchdog
- [Extended Features](#extended-features): UPS
- [Getting Started](#getting-started): Backup, default configuration, command history, license, packages, upgrade
- [Hardware](#hardware): LEDs, Routerboard information
- [Management Tools](#management-tools): Serial console,
- [Mobile Networking](#mobile-networking): GPS
- [Scripting](#scripting): Scripting management
- [System Information and Utilities](#system-information-and-utilities): Clock, device mode, router identity, login note, NTP, PTP, scheduler

### Main
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/..`](root-level.md) | `/..` | go up to root |  |

### Bridging and Switching
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system swos`](https://help.mikrotik.com/docs/display/ROS/CRS3xx%2C+CRS5xx%2C+CCR2116%2C+CCR2216+switch+chip+features) | `/sys swos` |  | load, save and reset SwOS configuration, as well as upgrade SwOS and set an IP address for the CRS3xx series switches from RouterOS |

### Diagnostics, monitoring and troubleshooting
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system health`](https://help.mikrotik.com/docs/display/ROS/Health) | `/sys he` | Router health | Display different information about hardware status, like temperature, voltage, current, fan-speed, etc. |
| [`/system logging`](https://help.mikrotik.com/docs/display/ROS/Log) | `/sys l` | Global logging configuration |  |
| [`/system resource`](https://help.mikrotik.com/docs/display/ROS/Resource) | `/sys re`  | System resources | Overall resource usage and router statistics like uptime, memory usage, disk usage, version, etc.  |
| [`/system watchdog`](https://help.mikrotik.com/docs/display/ROS/Watchdog) | `/sys w` | Watchdog | Configuring system to reboot, when a specific IP address does not respond, or when it detects, that the software has locked up |

### Extended features
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system ups`](https://help.mikrotik.com/docs/display/ROS/UPS) | `/sys ups` | | UPS monitor feature works with APC UPS units that support “smart” signalling over serial RS232 or USB connection. *Requires ups.npk package install* |

### Getting Started
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system backup`](https://help.mikrotik.com/docs/display/ROS/Backup) | `/sys b` | Makes a full system backup | RouterOS Backup |
| [`/system default-configuration`](https://help.mikrotik.com/docs/display/ROS/Default+configurations) | `/sys def` |  | Default configurations |
| [`/system history`](https://help.mikrotik.com/docs/display/ROS/Configuration+Management) | `/sys hi` | Command history |  |
| [`/system license`](https://help.mikrotik.com/docs/display/ROS/RouterOS+license+keys) | `/sys li` | Licensing information | RouterOS license keys |
| [`/system package`](https://help.mikrotik.com/docs/display/ROS/Packages) | `/sys p` | Software packages |  |
| [`/system upgrade`](https://help.mikrotik.com/docs/display/ROS/Upgrading+and+installation) | `/sys u` | Router upgrading |  |

### Hardware
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system leds`](https://help.mikrotik.com/docs/display/ROS/LEDs) | `/sys le` |  | Configuring each LED's activity the way that the user wishes |
| [`/system routerboard`](https://help.mikrotik.com/docs/display/ROS/RouterBOARD) | `/sys ro`  | Routerboard options | Basic information about your device |

### Management tools
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system console`](https://help.mikrotik.com/docs/display/ROS/Clock) | `/sys c` | Connection over serial port | Serial console |

### Mobile Networking
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system gps`](https://help.mikrotik.com/docs/display/ROS/GPS) | `/sys gps` |  | Global Positioning System (GPS) is used for determining precise location of a GPS receiver. |

### Scripting
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system script`](https://help.mikrotik.com/docs/display/ROS/Scripting) | `/sys script`  | Scripting management |  |

### System Information and Utilities
| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/system clock`](https://help.mikrotik.com/docs/display/ROS/Clock) | `/sys cl` | Print/change system date and time |  |
| [`/system device-mode`](https://help.mikrotik.com/docs/display/ROS/Device-mode) | `/sys dev` | Device mode | sets specific limitations on a device, or limits access to specific configuration options |
| [`/system identity`](https://help.mikrotik.com/docs/display/ROS/Identity) | `/sys i` | System identity |  unique identifying name for when the system identifies itself to other routers in the network. |
| [`/system note`](https://help.mikrotik.com/docs/display/ROS/Note) | `/sys no`  | Login note | assign arbitrary text notes or messages that will be displayed on each login right after the banner |
| [`/system ntp`](https://help.mikrotik.com/docs/display/ROS/NTP) | `/sys nt` |  | NTP client. Optional: NTP server (requires the ntp package installed and enabled) |
| [`/system ptp`](https://help.mikrotik.com/docs/display/ROS/Precision+Time+Protocol) | `/sys pt` | | Precision Time Protocol |]
| [`/system scheduler`](https://help.mikrotik.com/docs/display/ROS/Scheduler) | `/sys sch` | Schedule scripts to be run at times | can trigger script execution at a particular time moment, after a specified time interval, or both. |

## Parameters

Invoke with : `/system [parameter]` or `/sy [parameter]`

The following command parameters are accepted:

| **Parameter** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [**check-installation**](https://help.mikrotik.com/docs/display/ROS/Packages) | ch | Check installed packages |  |
| **export** | e | Print or save an export script that can be used to restore configuration | |    
| [**reboot**](https://help.mikrotik.com/docs/display/ROS/Upgrading+and+installation) | reb | Restart the router |  |
| [**reset-configuration**](https://help.mikrotik.com/docs/display/ROS/Configuration+Management) | rese |  | Command clears all configuration of the router and sets it to the factory defaults including the login name and password ('admin' with an empty password or, for some models, check user and wireless passwords on the sticker). For more details on the default configuration see the list. After the configuration reset command is executed router will reboot and load the default configuration. It is possible to override the default reset behavior |
| [**serial-terminal**](https://help.mikrotik.com/docs/display/ROS/Serial+Console) | se | Serial Terminal |  |
| **shutdown** | sh | Shut the router down |  |
| **ssh** | ssh | SSH client for interactive session |  |
| **ssh-exec** | ssh- | SSH client for non-interactive command execution |  |
| **sup-output** | s | Create support output file |  |
| **telnet** | t | Run Telnet |  |
| 

## Note
- Not official - May be incomplete.
- Type `/system` and use `[Tab]` twice for possible completions. 

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of SIA Mikrotīkls, Latvia
