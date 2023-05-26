# Permission suggestions
- Plugin will suggest you permissions of installed plugins
- **You need to make yourself `SuperAdmin` to be able to work with the plugin!** 
<br>

## Navigation:
1. Open the UltraPermissions main GUI using the command `/uperms`
2. Click on the **Bookshelf** icon named **Groups**
<br>

![Groups](https://imgur.com/ftTdpwr.png)
<br>

3. Click on a group you want to add permissions to *(e.g. `Developer`)*
<br>

![Group](https://imgur.com/cRNipdt.png)
<br>

4. In the group edit gui you will see a book 'n quill icon *(Called `View Permissions`)*
<br>

![ViewPerms](https://imgur.com/ntBw51k.png)
<br>

5. Choose a plugin from those displayed in this gui and click on it *(e.g. `InsaneAnnouncer`)*
<br>

![Plugin](https://imgur.com/esmOv8B.png)
<br>

6. Now you can see the permissions that UltraPermissions offer for your chosen plugin.
<br>

*Here's a shortend version of the above guide:*
`/uperms >> Groups >> [Group] >> View Permissions >> [Plugin]`
<br>

### **NOTES:**
* `[Group]` is the group that you need to choose yourself from your group list
* `[Plugin]` is the plugin that you need to choose yourself from your plugin list
* The permissions suggestions work with players too - Just follow the guide above 
  and instead of selecting **Groups** in the second step, select **Users**
<br>


## Adding permissions In-Game
You can also add permissions manually on your server. Here's how:
<br>

1. Open the UltraPermissions main GUI using the command `/uperms`
2. Click on the **Bookshelf** icon named **Groups**
<br>

![Groups](https://imgur.com/ftTdpwr.png)
<br>

3. Click on a group you want to add permissions to *(e.g. `Developer`)*
<br>

![Group](https://imgur.com/cRNipdt.png)
<br>

4. In the group edit gui you will see a book 'n quill icon *(Called `View Permissions`)*
<br>

![ViewPerms](https://imgur.com/ntBw51k.png)
<br>

5. Click on `Add Permission`
<br>

![AddPerm](https://imgur.com/pcl7vnm.png)
<br>

6. Write the permission node in the chat and press ENTER
<br>

*Here's a shortend version of the above guide:*
`/uperms >> Groups >> [Group] >> View Permissions >> Add Permission`
<br>

### **NOTES:**
* `[Group]` is the group that you need to choose yourself from your group list
* The above guide applies to players too - Instead of selecting **Groups** in the second step, select **Users**
<br>


## Permission storage
If you're wondering where do UltraPermissions take the plugin permissions from, here is your answer:
- First it looks into our **Permission database** and search for the permissions related to your installed plugins
- If some permissions are not found in the Permission database, it looks into your server's plugin.yml file 
  and searches for the permissions there
- If both ways result in some permissions not being found, they are not displayed in the UltraPermissions GUI
<br>

- **But if you don't see some permissions in the plugin's GUI, you can add them manually to** [our database](https://github.com/TechsCode-Team/PluginPermissions) **or add them manually In-Game** *(See the `Guide Above`)*