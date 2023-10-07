# Mikrotik - RouterOS - / - Root level CLI commands

## Home menu level
/
## Fast typing shortcut
/

## Sub-menus

| **Command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [/..](root-level.md) | /.. | go up to root |  |
| [/](root-level.md)  | / |  |  | Return to root |
| [/caps-man](capsman.md) | /ca | | Controlled Access Point system Manager (CAPsMAN) |
| [/certificate](certificate.md) | /ce | Certificate management |  |
| [/console](console.md) | /cons |  | Console |
| [/disk](disk.md) | /di |  | Disk |
| [/environment](environment.md) | /en | list of all variables |  |
| [/file](file.md) | /fil | local router file storage. | Files & File Transfer Protocol (FTP) |
| [/interface](interface.md) | /in |  | Interfaces |
| [/ip](ip.md) | /ip | IP options | IPv4 services |
| [/ipv6](ipv6.md) | /ipv |  | IPv6 services |
| [/log](log.md) | /l | System logs |
| [/mpls](mpls.md) | /m |  | Multi Protocol Label Switching (MPLS) |
| [/partitions](partitions.md) | /part |  | Partitions |
| [/port](port.md) | /po | Serial ports |  |
| [/ppp](ppp.md) | /pp | Point to Point Protocol |  |
| /queue | /que | Bandwidth management | |
| /radius | /rad | Radius client settings |  |
| /routing | /ro |  |  | 
| [/snmp](snmp.md) | /sn | SNMP settings |  | 
| /special-login | /sp | Special login users |  |
| /system | /sy |  | System operations |  | 
| /task | /ta | commands related to background task handling |  |
| /terminal | /te | commands related to terminal handling |  |
| /tool | /too | Diagnostics tools |  |
| /user | /us | User management |  |

## Sub-Commands and Parameters

The following command parameters are accepted:

| **Command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| /beep | /be |  |  |
| /blink | /bl |  |  |  
| /convert | /conv |  convert binary data encoding |  |
| /delay | /de | does nothing for a while |  |
| /do | /d | executes command |  |
| /error | /er |make error value |  |
| /execute | /exe | run script as separate console job |  |
| [/export](export.md) | /exp | Print or save an export script that can be used to restore configuration | Export configuration |
| /find | /fin | Find items by value |  |
| /for | /for | executes command for a range of integer values  |  |
| /foreach | /fore | executes command for every element in a list |  |
| /global | /g | set value global variable |  |
| /if | /if | executes command if condition is true |  |
| [/import](import.md) | /imp |  | Import configuration |  |
| /len | /le  | return number of elements in value |  |
| /local | /loc | set value of local variable |  |
| /nothing | /n | do nothing and return nothing |  |
| /parse | /pars | build command from text |  |
| /password | /pa  | Change password |  |
| /pick | /pic | return range of string characters or array values  |  |
| /ping | /pin | Send ICMP Echo packets |  |
| /put | /pu | prints argument on the screen |  |
| /quit | /qui | Quit console |  |
| /redo | /red  | Redo previously undone action |  |
| /resolve | /res | perform a dns lookup of domain name |  |
| /retry | /retr | repeatedly executes command until it succeeds |  |
| /return | /retu | return value from function |  |
| /rndnum | /rndn  | return random number in given interval |  |
| /rndstr | /rnds | return random string |  |
| /set | /set | Change item properties |  |
| /time | /time | returns time taken by command to execute |  |
| /timestamp | /times  | returns time since the epoch |  |
| /toarray | /toa | convert argument to array value |  |
| /tobool | /tob | convert argument to truth value |  |
| /toid | /toid | convert argument to internal number value |  |
| /toip | /toip | convert argument to IP address value |  |
| /toip6 | /toip6 | convert argument to IPv6 address value |  |
| /tonum | /ton | convert argument to integer number value |  |
| /tostr | /tos | convert argument to string value |  |
| /totime | /tot | convert argument to time interval value |  |
| /typeof | /ty | return type of value |  |
| /undo | /un | Undo previous action |  |
| /while | /w | executes command while condition is true |  |

For details on general commands: [General commands](https://help.mikrotik.com/docs/display/ROS/Console)

## Note
- Not official - May be incomplete.
- Type / and use tab twice for possible completions. 
