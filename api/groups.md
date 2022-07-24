# Overview
This page will explain how you can manage groups using the API. 
If you get a "NoClassDefFound" error, this means the API has not been imported correctly. Please re-read the [Dependency](./api/dependency) section of this Wiki.

First you must gain an instance of the API. Please see the [Dependency](./api/dependency) section of the Wiki.


## Creating a Group
Note: The term "api" should be replaced with whatever your UltraPermissions API variable is.

When creating a new item, it will return a Creator object. You can use this creator to edit the meta of the object.

An example is:
```
api.newGroup(api.getGroups(), "GroupName")
    .setDefault(true)
    .setServer("Optional Server Specific")
    .setWorld("Optional World Specific")
    .setPrefix("Prefix")
    .setSuffix("Suffix")
    .id(100)
    .setPriority(100)
    .setIcon(XMaterial.STONE)
    .create();
```

You can of course leave out any of the variables and still use the create method if you wish.


## Obtaining Groups
To get all groups, you can use 
```
api.getGroups()
```
This returns a GroupList object. With this object you can filter depending on servers, worlds, priority, etc. You can also just use this as a normal ArrayList and filter it that way, or get a specific object.


## Adding permission to group

Please see [Permissions](./api/permissions) for information on this.

## TODO: Adding/Removing groups from players

