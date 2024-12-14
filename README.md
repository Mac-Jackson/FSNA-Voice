<p align="center">
<img src="https://i.imgur.com/mPP5trz.png" alt="Voice Over IP Logo"/>
</p>

<h1>Connect VoIP Phones</h1>
This tutorial focus on the implementation and configuration of Voice over IP (VoIP).<br />


<h2>Networking Technologies Used</h2>

- VoIP (Voice over IP)
- DHCP (Dynamic Host Configuration Protocol)
- CME (Cisco Unified Communications Manager Exspress)
- Directory Numbers (DN)
- Access Control Lists (ACL)
- QoS (Quality of Service)


<h2>Environments Used </h2>

- Command-Line Interface (CLI)
- Cisco IOS Router or Switch


<h2>Tools Used </h2>

- Cisco Packet Tracer
- Cisco Router
- Cisco Switches
- VoIP Phones

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1  Voice DHCP and CME configuration are already in place on FSNA-RTR
- Step 2  Connect VoIP Phones to each corresponding switch
- Step 3  Configure Directory Numbers
- Step 4  Confirm Phone Registration
- Step 5  Confirm Internal Dialing
- Step 6  Confirm Outbound Dialing
- Step 7  Review VoIP Configurations on FSNA-RTR
- Step 8  Review Access Control List allowing VoIP Provider
- Step 9  Review VoIP Quality of Service across the WAN
<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/EKj7xBG.png" height="80%" width="80%" alt="FSNA-Security"/>
</p>
<p>
 Configure SSH and Disable Telnet
 (config)#ip domain-name fsna.local
 (config)#crypto key generate rsa (Modulus: 2048)
 (config)#ip ssh version 2
 (config)#line vty 0 15
 (config-line)#transport input ssh
 (config-line)#transport output ssh
</p>
<br />

<p>
<img src="https://i.imgur.com/AUoVis6.png" height="80%" width="80%" alt="FSNA-Security"/>
</p>
<p>
Enable SSH version 2
</p>
<br />



<p>
<img src="https://i.imgur.com/8dNFJuE.png" height="80%" width="80%" alt="FSNA-Security"/>
</p>
<p>
Lock Down for no Telnet Access.
</p>
<br />
</p>
<br />
