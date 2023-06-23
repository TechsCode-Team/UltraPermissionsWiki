# Commands
Here is the list of all the commands that can be used.

**`NOTE:` All commands require `SuperAdmin access`.**
<br>

## Admin Commands

* `/uperms`
  To open the Administrative GUI
* `/upc AddSuperAdmin <User>`
  Gives the user SuperAdmin access
* `/upc RemoveSuperAdmin <User>`
  Removes someone as a SuperAdmin
* `/upc PurgeSuperAdmins`
  Removes all SuperAdmins from UltraPermission.
<br>

## Group Commands

* `/upc AddGroup <User> <Group> [World|Server] [+|-][Time]`
  Add a a group to a user with optional use of Operators
  (+ = Add, - = Reduce) to add more time or reduce the time.  
* `/upc RemoveGroup <User> <Group>`
  Removes a group from a player
* `/promote <User> <Path>`
  Promotes the user to the next role in the path
* `/demote <User> <Path>`
Demotes the user to the previous role in the path
* `/upc CreateGroup <groupName> [Server]`
  Creates a group
* `/upc DeleteGroup <Group>`
  Delete a group
* `/upc SetGroups <User> <Groups>`
  Sets the groups of a player
* `/upc setGroupPriority <Group> <Priority>`
  Set a groups priority
* `/upc SetGroupPrefix <Group> <Prefix>`
  Set a groups prefix
* `/upc SetGroupSuffix <Group> <Suffix>`
  Set a groups suffix
* `/upc RestrictGroupToWorld <Group> <World>`
  Restrict a group to a single world
* `/upc RemoveGroupPermission <Group> <Permission>`
  Removes a permission from a group
* `/upc CopyGroup <Group> <copyGroupName>`
  Copy a group
* `/upc PurgeGroup <Group>`
  Removes all members of the group
* `/upc PurgeGroupPermission <Group>`
  Removes all permissions from the group
* `/upc PurgePlayerGroups <User>`
  Removes all groups from the player
<br>

## User Commands

* `/upc AddPlayerPermission <User> [-]<Permission> [World|Server] [+|-][Time]`
  Adds a permission to a player (The `-` makes the permission negative) and with
  optional use of Operators (+ = Add, - = Reduce) to add more time or reduce the time. 
* `/upc RemovePlayerPermission <User> <Permission>`
  Removes a permission from a player
* `/upc SetPlayerPrefix <User> <Prefix>`
  Sets a player's prefix
* `/upc SetPlayerSuffix <User> <Suffix>`
  Sets a player's suffix
* `/upc registerUser <UUID> <PlayerName> <AssignDefaultGroup>`
  Manually registers a new account based on the provided UUID  
* `/upc DeleteUser <User>`
  Delete a user 
* `/upc PurgePlayerPermission <Permission>`
  Removes the permission from all players
* `/upc PurgeAllPlayerPermissions <User>`
  Removes all permissions from the player
<br>

## Transfer Commands

* `/upc Transfer <File|MySQL> <File|MySQL>`
  Transfers storage to either MySQL or File
* `/upc TransferAccount <All|Groups|Permissions> <Append|Overwrite> <From> <To>`
  Transferes the selected data from user `<From>` to user `<To>`. Append will append the new incoming datas on the existing one datas of the `<To>` user. Overwrite will remove all existing datas and add the new incoming datas.
<br>

## Symbols:
- <> = Required
- [] = Optional
- | = Or
  