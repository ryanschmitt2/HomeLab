<h1>Home Lab</h1>

<h2>Description:</h2>
This is the start of my home lab. This will cover initial hardware choices, setup, and troubleshooting. A new version of this project will be made for each gateway upgrade. Until then, all upgrades will be logged here.

<h2>Upgrades: </h2>

[UDR7](https://techspecs.ui.com/unifi/cloud-gateways/udr7?s=us)

<h2>Tools and Skills: </h2>

- Ethernet Standards
- UniFi OS
- UniFi App
- Wifi Configuration
- Wifi Interference
- Plug-and-Play Switching

<h2>Setup: </h2>
UDR7 setup is with the UniFi App. Initial setup is easy adoption, and you set your SSID and password. Device checks for updates and runs setup. Next the user goes to unifi.ui.com and inputs their credentials to access the device. Most of the features are available on the app, but it's much easier to work within the browser UI.

<img src="https://i.imgur.com/ToHDBR9.jpeg" height="30%" width="30%" alt="UDR7"/>

This router only has three 2.5GbE ports, so one will go to my personal PC, one will go to a TP-Link 8 port gigabit switch, and the last one left open for future expansion (for now). 

<img src="https://i.imgur.com/lup1yMu.jpeg" height="30%" width="30%" alt="UDR7 Back">/

The switch is just plug-and-play, so there is no management to do. It connects to second computer and the Nvidia Shield media streamer. The clients connecting to it have low demand for bandwidth so limiting the 2.5GbE port to a 1GbE switch is acceptable for now. 
