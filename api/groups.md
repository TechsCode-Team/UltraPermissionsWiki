# Overview
You can use the group method after you've retrieved the API. In the examples, we replace 'upermsApi' for 'UltraPermissions.getAPI()'.
Please see the [instance](./instance) guide if you haven't already obtained the API instance.

<br>

# Table of content
- [Creating a Group](#creating-a-group)
- [Obtaining a Group](#obtaining-a-group)
  - [Get Group Information](#get-group-inormation)

<br>

# API methods

<br>

## Creating a Group {#creating-a-group}
When you create a new group, you are creating a new object. This object contains options for configuring the Group information.

```java
GroupCreator newGroup = upermsApi.newGroup("VIP")
    .id(10)
	.setIcon(XMaterial.Diamond)
	.setDefault(false)
	.setPrefix("&6VIP")
	.setSuffix("&aAwsome Supporter")
	.setPriority(5)
	.setServer("Survival")
	.setWorld("world");

newGroup.create();
```

<br>

**NOTE;** .id(int) is required because it is the plugin's group identifier. Duplicate IDs will cause problems!

You can, however, ignore the following methods: `[setIcon, setDefault, setPrefix, setSuffix, setPriority, setServer, setWorld]`

<br>

`setIcon` needs an XMaterial. XMaterial is an enum that is used to retrieve the selected item's itemStack

<br>

## Obtaining a Group {#obtaining-a-group}
When you want to edit details of a Group you will need to get all the Groups first.

```java
GroupList groups = upermsApi.getGroups()
```
This method generates a list of all Groups. You are able to use this list to find the group you want to modify

<br>

### Get Group Inormation {get-group-inormation}
To begin, we'll need to create a loop to find the group we want to edit/use.
You can either A) alter/use the group directly, or B) save the group and use it later. In this example, we are saving the group in the `vipGroup` variable.
```java
Group vipGroup = null;
for(Group group : groups) {
	if (group.getName().equals("VIP")) {
		vipGroup = group;
        continue;
	}
}
```

<br>

## Geting Group details {#geting-group-details}
To get information about a group you first need to get the right group see [Obtaining a Group](#obtaining-a-group) for more information

For this example we use `vipGroup` as placeholder for the group that you have retrieved
```java
vipGroup.
