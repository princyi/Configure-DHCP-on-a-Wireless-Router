# Configure-DHCP-on-a-Wireless-Router
Packet Tracer - Configure DHCP on a Wireless Router


HCP (Dynamic Host Configuration Protocol): Automatically assigns IP addresses and other network configuration parameters to devices on a network. This simplifies network administration.
Steps to Configure DHCP on a Wireless Router in Packet Tracer
1. Create the Network Topology:

Open Cisco Packet Tracer.
Drag and drop the following devices onto the workspace:
One Wireless Router
Two PCs
2. Connect the Devices:

Connect the PCs to the wireless router using Ethernet cables.
3. Configure the Wireless Router:

Access the Configuration Mode:
Click on the wireless router to select it.
In the dialog box that appears, click on the "Config" tab.
Configure LAN Settings:
In the left-hand menu, select "LAN".
Configure the following parameters:
IP Address (e.g., 192.168.1.1)
Subnet Mask (e.g., 255.255.255.0)
Default Gateway (same as IP address)
Configure DHCP Pool:
In the left-hand menu, select "DHCP".
Configure the following parameters:
Start IP Address (e.g., 192.168.1.100)
End IP Address (e.g., 192.168.1.200)
Subnet Mask (same as LAN subnet mask)
Default Gateway (same as router's IP address)
DNS Server (optional, if you have a DNS server)
4. Configure PCs:

Select a PC.
Go to the "Desktop" tab.
Click on "IP Configuration".
Set the configuration to "DHCP".
Save the settings.
Repeat the process for the other PC.
5. Verify DHCP Assignment:

Check the IP addresses assigned to the PCs. They should be within the DHCP pool range.
Try pinging the router's IP address from the PCs to verify connectivity.
