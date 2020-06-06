# smartthings

Smart things device handler for Venstar thermostat, This utilizes the REST local API of the thermostat

On the venstar goto WIFI -> local API options -> enable API

In the code change the local ip of your thermostat on lines 119 and 138 to match the iP of your venstar

The code will send commands to your smartthings hub then push the API code locally so use the local LAN IP address of the Venstar not your public IP, make sure your venstar and hub are on the same subnet. This does work over the internet since your phone can communicate securly with the hub, then the stat info is transmitted on the local lan

*** Please note enabling the API in the thermostat can become a security risk if you thermostat is on a public network, please use only behind a firewall.


<img src ="https://github.com/freshfitz/smartthings/blob/master/image0.png">
