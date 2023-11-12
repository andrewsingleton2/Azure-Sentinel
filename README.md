# Azure-Sentinel
Created a honeypot and moderated RDP login attempts via Sentinel
Categorizing and discovering the IP and geolocations of the attempts within Azure’s SIEM Platform.

Tasks Performed:

1. I first created a resource group (RG) to manage all of my resources.

2. Created a virtual machine on the east US region and added it to my RG

3. Created a network security group and added it to my RG, making a rule that allows all inbound and outbound connections to the VM to make it easily discoverable.

4. Created a log analytics workspace and connected it to the VM to monitor the logs of the VM.

5. Enabled Azure Defender to provide security management for the VM.

6. Enabled the ability to retrieve logs from the VM using Azure Security Center.

7. Set up Azure Sentinel and connect it to the VM.

8. Used RDP from my main workstation to connect to the VM.

9. Disabled all firewalls within the VM to make it pingable from anywhere (making it a honeypot)

10. Then, I monitored Azure Sentinel to see the honeypot’s failed RDP login attempts from different threat actors around the world trying to brute force the VM. I created a SIEM to detect failed login attempts from attackers around the world using a honeypot I created with Azure VM. Categorizing and discovering the source IP and geolocations of the attempts within Azure’s SIEM Platform.

## Skills: Microsoft Azure · Security Information and Event Management (SIEM) · VM
