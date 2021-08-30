# Proxy Installation
There are a variety of proxies out there. BungeeCord is the usual one that is most commonly used, although Waterfall (by the Paper devs) has improved performance. Therefore we recommend **[Waterfall](https://papermc.io/downloads#Waterfall)**.
<br>

For a proxy installation, you need to repeat the installation process for every server. Once you have finished installing the plugin on all the back-end servers, we need to install it onto the proxy.
<br>

Once the plugin has been installed on the proxy, we need to set up the MySQL connections inside the back-end servers.
<br>

## Connecting to MySQL
To connect your server to MySQL you need to join your server and use
***/uperms >> Settings >> MySQL Database >> Setup MySQL >> Credentials***
<br>

Here you will need to fill in the credentials *(info)* of your database.
<br>

Once you have filled in all the credentials, you can now test the connection and confirm it.
<br>

When you have connected all server with the same database (Inside uperms) you need to restart all the servers including the proxy (Bungee).
<br>

Once you have already made groups and set permissions without bungee you can use ***/upc transfer file mysql*** to transfer the permissions, users and groups.
<br>

**`NOTE:` If your database has not connected or the test takes too long, you have entered the wrong credentials.**
