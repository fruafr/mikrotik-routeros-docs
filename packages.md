# Mikrotik - RouterOS - Packages

- [Packages documentation](https://help.mikrotik.com/docs/display/ROS/Packages)
- [Packages download page](https://mikrotik.com/download)

## RouterOS packages 
The `routeros` (system) package is the only package needed for basic operation (e.g. simple home router).
In RouterOS v7, most of the features are combined in the `routeros` (system) package.

## 802.11ax Wifi
On 802.11ax devices, the `wifiwave2` package is required to enable Wifi connections.

## Closed system
Packages are provided only by MikroTik, and no 3rd parties are allowed to make them.

## Additional packages
Specific features (like container, dude) can be enabled by installing the corresponding package.

| **Package** | **Description** | **Architecture availability** |
|---|---|---|
| **calea** | Data gathering tool for compliance with the United States "Communications Assistance for Law Enforcement Act" | *arm, arm64, mipsbe, mmips, tile, ppc, x86, CHR* |
| **container** | Container implementation of Linux containers, allows users to run containerized environments within RouterOS | *arm, arm64, x86, CHR*	| 
| **dude** | Dude tool monitors network environment | *arm, arm64, mmips, tile, x86, CHR* |	
| **gps** | Global Positioning System devices support | *arm, arm64, mipsbe, mmips, tile, ppc, x86, CHR* |
| **iot** | Enables  Bluetooth, MQTT and LoRa functionality | *arm, arm64, mipsbe, mmips, tile, ppc, x86, CHR* |
| **lora** | Lora support | *arm, arm64, mipsbe, mmips, tile, ppc, x86, CHR*
| **lte** | Required package only for SXT LTE (RBSXTLTE3-7), which contains drivers for the built-in LTE interface | *mipsbe* |
| **rose-storage** | Additional enterprise data center functionality in RouterOS, support disk monitoring, improved formatting, RAIDs, rsync, iSCSI ,NVMe over TCP, NFS and improved SMB | *arm, arm64, tile, x86, CHR* |
| **tr069-client** | TR069 Client package | *arm, arm64, mipsbe, mmips, smips, tile, ppc, x86, CHR*
| **ups** | APC ups management interface | *arm, arm64, mipsbe, mmips, tile, ppc, x86, CHR*
| **user-manager** | MikroTik User Manager server for controlling Hotspot and other service users. | *arm, arm64, mipsbe, mmips, tile, ppc, x86, CHR*
| **wifiwave2** | WifiWave2 package for managing compatible 802.11ax and 802.11ac wave 2 wireless interfaces and WifiWave2 CAPsMAN for central WifiWave2 device management. Mandatory for 802.11ax devices. | *arm, arm64, mmips, tile, ppc, x86, CHR*
| **zerotier** | Enables ZeroTier functionality | *arm, arm64*

## Note
- Not official - May be incomplete.

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)
