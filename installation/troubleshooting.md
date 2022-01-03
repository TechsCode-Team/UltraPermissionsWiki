## Troubleshooting guide
<br>

**`My plugin is not connecting to MySQL`**
* If your plugin is not connecting to MySQL or is taking to long to test the connection it means that you have filled in the wrong credentials, or haven't setup your MySQL correctly on your hosting provider's end.
<br>

**`Proxy isn't connected`**
* If your proxy isn't connected you need to do it manually.
  First, we need the MySQL key from a connected server. 
  This can be found in there *\SERVER_DIRECOTRY\plugins\UltraPermissions*. 
  Here you need to copy the MySQL key, and paste it inside the config of the proxy (same directory as above).
<br>

**`NOTE:` This key can continue on a second line, so make sure to copy it all!**
<br>

**`My bungee permissions are not working`**
* If your bungeecord / proxy permissions are not working then it's possible you added the permissions via the wrong way.
  How do I add them correctly?
  First go to your permission viewer in /uperms (group / user), are the bungee / proxy permissions green? If yes go to second step.
<br>

* Second, we need to delete first the green bungee / proxy permissions.
  Now the not working permissions are gone (Green bungee/proxy permissions), Go to your permission viewer again.
  In your permission viewer press with a right click on the *NameTag*.
<br>

* Now you can add the bungee/proxy permission via the chat.
  If you have done correctly it should now show up in the permission viewer in **Red**.
