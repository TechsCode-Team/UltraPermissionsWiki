# Proxy Installation
There are a variety of proxies out there. BungeeCord is the usual one that is most commonly used, although Waterfall (by the Paper devs) have improved performance. Therefore we recommend [Waterfall](https://papermc.io/downloads#Waterfall).
<br>

For a proxy installation, you need to repeat the installation process for every server. Once you have finished installing the plugin on all the back-end servers, we need to install it onto the proxy.
<br>

Once the plugin has been installed on the proxy, we need to set up the MySQL connections inside the back-end servers.
<br>

## Connecting to MySQL
To connect your server to MySQL you need to join your server and use
***/uperms >> Settings >> MySQL Database >> Setup MySQL >> Credentials***. 
Here you need to fill in the credentials *(info)* of your database. 
Once you have filled in all the credentials you can now test the connection and confirm it.
When you have connected a plugin to MySQL you need to restart your server.
When you have repeated this procces for all of your servers your plugin is now proxy ready.
<br>

***NOTE:*** *If your database has not been connected or the test is taking to long, you have entered the wrong credentials.*
<br>