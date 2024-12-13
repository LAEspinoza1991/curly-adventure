# curly-adventure
This project introduced me to the Cisco Packet Tracer simulation environment.
Packet Tracer - Create a Simple Network
Objective: Build and configure a simple network in Packet Tracer.

Part 1: Build a Simple Network
Add Devices:

PC: End Devices > End Devices > PC

Laptop: End Devices > End Devices > Laptop

Cable Modem: Network Devices > WAN Emulation > Cable Modem

Rename Devices:

Click each device.

Go to the Config tab.

Change the names to PC, Laptop, and Cable Modem.

Connect Devices with Cables:

PC to Router: Use a copper straight-through cable.

Router to Cable Modem: Use a copper straight-through cable.

Cable Modem to Cloud: Use a coaxial cable.

Part 2: Configure Devices and Verify Connectivity
Configure the PC:

Click the PC and go to Desktop > IP Configuration.

Enable DHCP and check that the PC gets an IP address.

Open Command Prompt and type ipconfig /all to see IP details.

Test connection with ping cisco.srv.

Configure the Laptop for Wireless:

Click Laptop and go to the Physical tab.

Replace the Ethernet module with the Wireless module.

Go to Desktop > PC Wireless and connect to "HomeNetwork".

Test connection in Web Browser by going to cisco.srv.

Reflection
Use ipconfig in Command Prompt to fill out the IP address table:

PC: IP Address, Subnet Mask, Default Gateway

Laptop: IP Address, Subnet Mask, Default Gateway
