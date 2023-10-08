# Mikrotik – RouterOS - CLI - `/export` - Export configuration

Print or save an export script that can be used to restore configuration

[Mikrotik RouterOS' documentation for Configuration Management](https://help.mikrotik.com/docs/display/ROS/Configuration+Management)

- [Home menu level](#home-menu-level)
- [Fast typing shortcut](#fast-typing-shortcut)
- [Sub-menus](#sub-menus)
- [Parameters](#parameters)

## Home menu level

`/export`

## Fast typing shortcut

`/exp`

## Sub-menus

| **Sub-command** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| [`/..`](root-level.md) | `/..` | go up to root |  |

## Parameters

Invoke with : `/export [parameter]` or `/exp [parameter]`

The following command parameters are accepted:

| **Parameter** | **Shortcut** | **Official Description** | **Note** |
|---|---|---|---|
| **compact** | c | Output only modified configuration, the default behavior |  |          
| **file**  | f | Export configuration to a specified file. When the file is not specified export output will be printed to the terminal |  | 
| **hide-sensitive**  | h | Hide sensitive information, like passwords, keys, etc. | (yes\|no; Default: yes). RouterOS version 6 only |
| **show-sensitive** | s | Show sensitive information, like passwords, keys, etc. | (yes\|no; Default: no). RouterOS version 7 only |
| **terse** | t | With this parameter, the export command will output only configuration parameters, without defaults. |  |
| **verbose** | v | With this parameter, the export command will output whole configuration parameters and items including defaults. |  |

## Note
- Not official - May be incomplete.
- Type `/export` and press `[Tab]` for possible completions. 

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)

