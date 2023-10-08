# Mikrotik – RouterOS - CLI - General Commands

[Enriched from Mikrotik RouterOS' documentation for General Commands](https://help.mikrotik.com/docs/display/ROS/Command+Line+Interface)

There are some commands that are common to nearly all menu levels, namely: 
-[add](#add)
-[comment](#comment)
-[disable](#disable)
-[edit](#edit)
-[enable](#enable)
-[export](#export)
-[find](#find)
-[get](#get)
-[move](#move)
-[print](#print)
-[remove](#remove)
-[set](#set)

These commands have similar behavior throughout different menu levels.

## **add**

This command usually has all the same arguments as a [set](#set), except the item number argument. It adds a new item with the values you have specified, usually at the end of the item list, in places where the order of items is relevant. There are some required properties that you have to supply, such as the interface for a new address, while other properties are set to defaults unless you explicitly specify them.

- **Common Parameters**
    - `copy-from` - Copies an existing item. It takes default values of a new item's properties from another item. If you do not want to make an exact copy, you can specify new values for some properties. When copying items that have names, you will usually have to give a new name to a copy
    - `place-before` - places a new item before an existing item with a specified position. Thus, you do not need to use the move command after adding an item to the list
    - `disabled` - controls disabled/enabled state of the newly added item(-s)
    - `comment` - holds the description of a newly created item
- **Return Values**
    - add command returns the internal number of items it has added

## **comment**

This command sets comment for items.

## **disable**

This command disables items. It is the opposite of [enable](#enable)

## **edit** 

This command is associated with the [set](#set) command. It can be used to edit values of properties that contain a large amount of text, such as scripts, but it works with all editable properties. Depending on the capabilities of the terminal, either a full-screen editor or a single line editor is launched to edit the value of the specified property.

## **enable**

This command enables items. It is the opposite of [disable](#disable)

## **export**

This command prints or saves an [export script](export.md) that can be used to restore configuration.
It takes the same arguments as the [export](export.md) command.

## **find** 

The find command finds items by value

It has the same arguments as a [set](#set), plus the flag arguments like disabled or active that take values yes or no depending on the value of the respective flag. To see all flags and their names, look at the top of the print command's output. The find command returns internal numbers of all items that have the same values of arguments as specified.

## **get**

The get command gets the value of an item's property.

## **move** 

Changes the order of items in the list. 

- **Parameters**:
    - **the first argument** specifies the item(-s) being moved.
    - **the second argument** specifies the item before which to place all items being moved (they are placed at the end of the list if the second argument is omitted). |

## **print**

The print command prints the values of items' properties.

Shows all information that's accessible from a particular command level. Thus, /system clock print shows the system date and time, /ip route print shows all routes etc. If there\'s a list of items in the current level and they are not read-only, i.e. you can change/remove them (example of read-only item list is /system history, which shows a history of executed actions), then print command also assigns numbers that are used by all commands that operate with items in this list.

- **Common Parameters**:
    - `append` - 
    - `brief` - forces the print command to use tabular output form
    - `count-only` - shows the number of items
    - `detail` - forces the print command to use property=value output form
    - `file` - prints the contents of the specific sub-menu into a file on the router.
    - `follow` - 
    - `follow-only` - 
    - `follow-strict` - 
    - `from` - show only specified items, in the same order in which they are given.
    - `interval` - updates the output from the print command for every interval of seconds.
    - `oid` - prints the OID value for properties that are accessible from SNMP
    - `proplist` - 
    - `show-ids` - 
    - `where` - show only items that match specified criteria. The syntax of where the property is similar to the find command.
    - `without-paging` - prints the output without stopping after each screenful. |

## **remove** :

The remove command removes specified item(-s) from a list.

## **set**:

The set command changes item properties.

Allows you to change values of general parameters or item parameters. The set command has arguments with names corresponding to values you can change. Use ? or double Tab to see a list of all arguments. If there is a list of items in this command level, then the set has one action argument that accepts the number of items (or list of numbers) you wish to set up. This command does not return anything.|

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)
