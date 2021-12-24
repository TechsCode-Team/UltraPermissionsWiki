# Welcome!
Welcome to the Wiki page of Ultra Permissions, where you can find all the information and documentation. You can navigate the wiki using the sidebar on the right.
<br>

## Contact
You can communicate with our support team by joining our **[Discord](https://discord.gg/3JuHDm8)**. It is the only way we can give you support once you have verified your purchase.
<br>

## What can you find on the wiki?
- [Commands](/wiki/overview) - The list of commands
- [Installation Guide](/wiki/installation) - A quick guide on how to install Ultra Permissions
- [Features](/wiki/features) - A list with all the features of Ultra Permissions
- [API](/wiki/api) - A guide on how to use our API

# Commands
Here is a list of all the commands that can be used.
**`NOTE:` All commands require `SuperAdmin access`.**
<br>

* `/uperms`
  To open the Administrative GUI
* `/upc AddGroup <User> <Group> [World|Server] [Time]`
  Add a group to a user
* `/upc AddGroupPermission <Group> [-]<Permission> [Server] [Time]`
  Add a permission to a group (The `-` makes the permission negative)
* `/upc AddPlayerPermission <User> [-]<Permission> [Server] [Time]`
  Adds a permission to a player (The `-` makes the permission negative)
* `/upc AddSuperAdmin <User>`
  Gives them SuperAdmin access
* `/upc CopyGroup <Group> <copyGroupName>`
  Copy a group
* `/upc createGroup <groupName> [Server]`
  Creates a group
* `/upc DeleteGroup <Group>`
  Delete a group
* `/upc DeleteUser <User>`
  Delete a user
* `/upc PurgeGroup <Group>`
  Removes all members of the group
* `/upc PurgeGroupPermission <Group>`
  Removes all permissions from the group
* `/upc PurgePlayerGroups <User>`
  Removes all groups from the player
* `/upc PurgePlayerPermission <User>`
  Removes all permissions from the player
* `/upc PurgeSuperAdmins`
  Removes all Superadmins from UltraPermission.
* `/upc RemoveGroup <User> <Group>`
  Removes a group from a player
* `/upc RemoveGroupPermission <Group> <Permission>`
  Removes a permission from a group
* `/upc RemovePlayerPermission <User> <Permission>`
  Removes a permission from a player
* `/upc RemoveSuperAdmin <User>`
  Removes someone as a Superadmin
* `/upc RestrictGroupToWorld <Group> <World>`
  Restrict a group to a single world
* `/upc SetGroups <User> <Groups>`
  Sets the groups of a player
* `/upc SetPlayerPrefix <User> <Prefix>`
  Sets a player's prefix
* `/upc SetPlayerSuffix <User> <Suffix>`
  Sets a player's suffix
* `/upc setGroupPriority`
  Set a groups priority
* `/upc SetGroupPrefix`
  Set a groups prefix
* `/upc SetGroupSuffix`
  Set a groups suffix
* `/upc TransferAccount <All|Groups|Permissions> <Append|Overwrite> <From> <To>`
  Transferes the selected data from user `<From>` to user `<To>`. Append will append the new incoming datas on the existing one datas of the `<To>` user. Overwrite will remove all existing datas and add the new incoming datas.
* `/upc Transfer <File|MySQL> <File|MySQL>`
  Transfers storage to either MySQL or File
  <br>

## Symbols:
- <> = Required
- [] = Optional

# Placeholders
Below is a list of all available placeholders. Keep in mind these placeholders require **[PlaceholderAPI](https://www.spigotmc.org/resources/6245/)** & a plugin that supports the API!
<br>

* `%uperms_has_permission_(permission)%`
  Shows if the player has the specific permission.
* `%uperms_has_group_(group)%`
  Shows if the player is member of the specific group.
* `%uperms_inherits_group%`
  Shows if the player inherits directly from a group or indirectly via other group.
* `%uperms_prefixes%`
  Shows all Prefixes that a Player has seperated by a space.
* `%uperms_prefix%`
  Shows the first prefix that a player has.
* `%uperms_prefix_color%`
  Shows the Prefix Color of the first group.
* `%uperms_rank%`
  Shows the name of the first rank that the player has.
* `%uperms_ranks%`
  Shows the the name of all ranks that the player has.
* `%uperms_rank_timer%`
  Shows the remaining time of the first temporary group. (Days, Hours)
* `%uperms_rank_timer_detailed%`
  Shows the remaining time of the first temporary group. (Days, Hours, Minutes, Seconds)
* `%uperms_rank_timer_(group)%`
  Shows the remaining time of a specific group. (Days, Hours)
* `%uperms_rank_timer_detailed_(group)%`
  Shows the detailed remaining time of a specific group. (Days, Hours, Minutes, Seconds)
* `%uperms_secondaryprefix%`
  Same as *%uperms_prefix%* but with the second group.
* `%uperms_secondarysuffix%`
  Same as *%uperms_suffix%* but with the second group.
* `%uperms_suffixes%`
  Shows all Suffixes that a Player has seperated by a space.
* `%uperms_suffix%`
  Shows the first Suffix that a player has.
* `%uperms_suffix_color%`
  Shows the Prefix Color of the first group.
* `%uperms_<user>_permission_timer_<permission>%`
  Shows the remaining time of the specified permission of a specific user (Days, Hours)
* `%uperms_<user>_permission_timer_detailed_<permission>%`
  Shows the detailed remaining time of the specified permission of a specific user (Days, Hours, Minutes, Seconds)
