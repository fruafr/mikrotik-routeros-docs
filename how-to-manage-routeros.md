# Mikrotik - RouterOS - How to manage RouterOS ?

## First time configuration

First, you need to [sucessfully install RouterOS](https://help.mikrotik.com/docs/display/ROS/First+Time+Configuration):
- When no specific configuration is found, the **IP address 192.168.88.1/24** is set on ether1 or combo1, or sfp1.
- When connecting the first time to the router with the **default username admin** and **no password** (for some models, check user password on the sticker)

## Management methods - How to reach my Mikrotik Router ?

There are several methods to connect to the router :
- [Web interface (WebFig)](#webfig)
    - **Security: insecure connection unless HTTPS is enabled**
- [WinBox configuration utility](#winbox)
- [MikroTik mobile app](#mobile-app)
- [Command Line Interface (CLI)](cli.md) with a [SSH client software](https://help.mikrotik.com/docs/display/ROS/SSH)
    - **Security : It is recommanded to setup SSH keys instead of password authentication**
- [Command Line Interface (CLI)](cli.md) with a [Telnet client software](https://help.mikrotik.com/docs/display/ROS/Command+Line+Interface)
    - **Security : telnet is insecure. SSH should be used instead and Telnet should be turned off** 
- [Command Line Interface (CLI)](cli.md) via [serial cable](https://help.mikrotik.com/docs/display/ROS/Serial+Console) (or even keyboard and monitor if router has VGA card) through a serial port (DB9 or RJ45, depending on the model)
    - **Solution if no IP or MAC connectivity is available**
- [Rest API accessed via HTTP protocol](rest-api.md)
    - **Security: insecure connection unless HTTPS is enabled**
- [Application Programmable Interface (API) for lower level integration with other software or programming languages (e.g. Python)](api.md)
    - **Security: insecure connection unless HTTPS is enabled**

Other connection methods exist and are described in the ["Management Tools"](https://help.mikrotik.com/docs/display/ROS/Management+tools) section of Mikrotik's RouterOS documentation.

## WebFig 

[Per Mikrotik's Webfig documentation](https://help.mikrotik.com/docs/display/ROS/Webfig): 

*"WebFig is a web-based RouterOS utility that allows you to monitor, configure and troubleshoot the router. It is designed as an alternative of WinBox, both have similar layouts and both have access to almost any feature of RouterOS."*

You can access it in your browser with the address of your router: [http://192.168.88.1](http://192.168.88.1)

By default, it is insecure. [HTTPS can be enabled](https://help.mikrotik.com/docs/display/ROS/Webfig).

## Winbox

[Per Mikrotik's Winbox documentation](https://help.mikrotik.com/docs/display/ROS/Winbox): 

*"Winbox is a small utility that allows the administration of MikroTik RouterOS using a fast and simple GUI. It is a native Win32/Win64 binary but can be run on Linux and macOS (OSX) using Wine. All Winbox interface functions are as close as possible mirroring the console functions, that is why there are no Winbox sections in the manual."*

### Download
To download Winbox, [go to Mikrotik's download page](https://mikrotik.com/download)

### Firewall

Winbox runs on port [8291/tcp](https://wiki.mikrotik.com/wiki/Manual:IP/Services).

## Mobile App

[Per Mikrotik's Mobile App documentation](https://help.mikrotik.com/docs/display/ROS/MikroTik+mobile+app):

*"The application is available for both **Android** and **iOS** operating systems. It is good way to configure a new device, as it provides a simple and user-friendly setup screen for the most basic settings of your new router. It also features an advanced menu, for the more experienced user."*

### Downloading app

The MikroTik application is available to download on:
- [**Apple App Store**](https://apps.apple.com/us/app/mikrotik/id1323064830)
- [**Android Google Play**](https://play.google.com/store/apps/details?id=com.mikrotik.android.tikapp&hl=fr&gl=US)
- [**Mikrotik's website**](https://mikrotik.com/mobile_app)

## Note
- Not official - May be incomplete.

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)
