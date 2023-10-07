# mikrotik-routeros-docs
Mikrotik RouterOS documentation

Contains documentation about Mikrotik RouterOS. Not endorsed by Mikrotik.

## Introduction
[SIA Mikrotīkls](https://mikrotik.com/aboutus) is a Latvian company developing routers, switches and ISP systems, etc under the brand Mikrotik.

[RouterOS](https://mikrotik.com/software) is the operating system of RouterBoard products. It is [based on Linux kernel](https://help.mikrotik.com/docs/display/ROS/Getting+started). It powers MikroTik hardware devices, but is also available for virtual machines.

Yet, the Mikrotik RouterOS software on top of the kernel is proprietary requiring a [license key](https://help.mikrotik.com/docs/display/ROS/RouterOS+license+keys) (a free demo license key is available). 

## A side note on SwOS

Some routers are sold with a dual boot between RouterOS and SwOS. [SwOS](https://help.mikrotik.com/docs/display/SWOS/SwOS) "*is an operating system designed specifically for administration of MikroTik switch products. SwOS is configurable from your web browser. It gives you all the basic functionality for a managed switch, plus more: allows to manage port-to-port forwarding, broadcast storm control, apply MAC filter, configure VLANs, mirror traffic, apply bandwidth limitation and even adjust some MAC and IP header fields"*.

## Manuals

### Official
- [Current Mikrotik RouterOS Documentation](https://help.mikrotik.com/docs/)

### Mikrotik User Meetings (MUM)
- [Mikrotik User Meetings Website](https://mum.mikrotik.com/)
- [MUM Presentation archive](https://mum.mikrotik.com/archive)
- [Most underused MikroTik hardware and software features](mum/presentation_5143_1523360368.pdf) : Helps you choose the suitable MikroTik hardware and software features

## List of commands

A list of commands has been compiled from RouterOS 7 CLI (one level deep from root) and online documentation:

- [General console usage](/commands/general-console.md)
- [General commands](/commands/general-commands.md)
- [Root Level commands](/commands/root-level.md)
- [Search a specific command in Mikrotik documentation with Google Search - type your command before site](https://www.google.com/search?q=site%3Ahelp.mikrotik.com)

The actual capabilities depend on your specific hardware model and license limitations.

## RouterOS Source Code 
- [GPL sources from Mikrotik. Based on RouterOS 6.41 RC38 published by a third party](https://github.com/robimarko/routeros-GPL)
- RouterOS Linux kernel 3.3.5 patch published by third parties:
        - [github.com/wxarcher](https://github.com/wsxarcher/routeros-linux-patch/tree/master)
        - [github.com/Ciusss89](https://github.com/Ciusss89/routeros-linux-patch)
- [RouterOS License terms, including a method to obtain the source code by email, subject to open source obligations](https://mikrotik.com/downloadterms.html)

## Old documentation
- [Old reference manual PDF (RouterOS 3.0) - Pre-2011](manual/ros_3_0_reference_manual.pdf)

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of SIA Mikrotīkls, Latvia
