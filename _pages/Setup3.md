# Remote setup
Remote setup means you run server on an entirely different network than the one your client is connected to, just like how official servers function.

![NetworkMap](../_media/ee517b15e6482e293e392fdf70342b4c.png "Network Map")

## Router
The client on LAN 1 need to find the server on LAN 2. To make this happen you need to *forward* two dataports. This means you have to manually tell your router where to send incoming connections. Port **3724** and **8085** will need to be *forwarded* to the **local IP-adress** of the server. Optionally if you have a webserver you will also have to forward port **80**. (see image below)

![Port_forwarding](../_media/portforwarding.png)
![Login](../_media/HeidiSQL01.PNG)
test
