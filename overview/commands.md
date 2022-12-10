# Commands
Here is a list of all the commands that can be used.
**`NOTE:` All commands require `SuperAdmin access`.**
<br>

* `/uperms`
  To open the Administrative GUI
* `/upc AddGroup <User> <Group> [World|Server] [Time]`
  Add a group to a user
* `/upc AddGroupPermission <Group> [-]<Permission> [World|Server] [Time]`
  Add a permission to a group (The `-` makes the permission negative)
* `/upc AddPlayerPermission <User> [-]<Permission> [World|Server] [Time]`
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
- | = Or