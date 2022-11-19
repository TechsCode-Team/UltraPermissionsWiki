# Overview
Now that we have import the API we can get the instance. With this instance you are able to use the API.

<br>

## Obtaining the instance
To retieve the instance you will need to add the following method to your class.

*We recommend adding this to your main class (or your API class) to generalise this instance*

<br>

```java
UltraPermissionsAPI api = UltraPermissions.getAPI();
```
Now that we have the instance of the api we are able to do the following;
  - Groups | *Create, remove, alter and get groups*
  - Users | *Get all users and alter there permisssions and groups*
  - Permissinos | *List all permissions and add new once*

[Next part; Managing Groups](./api/groups.md)
