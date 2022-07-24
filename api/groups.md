# Overview
This page will explain how you can manage groups using the API. 
If you get a "NoClassDefFound" error, this means the API has not been imported correctly. Please re-read the [Dependency](./api/dependency) section of this Wiki.
<br>

First you must gain an instance of the API. Please see the [Dependency](./api/dependency) section of the Wiki.

<br>
<br>

## Creating a Group
Note: The term "api" should be replaced with whatever your UltraPermissions API variable is.
<br>

When creating a new item, it will return a Creator object. You can use this creator to edit the meta of the object.
<br>

An example is:
```java
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
<br>

You can of course leave out any of the variables and still use the create method if you wish.
<br>
<br>

## Obtaining Groups
To get all groups, you can use
```java
api.getGroups()
```
This returns a GroupList object. With this object you can filter depending on servers, worlds, priority, etc. You can also just use this as a normal ArrayList and filter it that way, or get a specific object.
<br>
<br>

## Adding permission to group
<br>

Please see [Permissions](./api/permissions) for information on this.
<br>

## TODO: Adding/Removing groups from players

