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
<img src="https://i.imgur.com/k1Mswpi.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
 Using a straight-through cable connect Phone A to FSNA-SW1
 
 

</p>
<br />

<p>
<img src="https://i.imgur.com/iUk1KhJ.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
 #show running-config (on FSNA-RTR, to verify ephone 1 is automatically added)
</p>
<br />



<p>
<img src="https://i.imgur.com/VMzu0bz.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Using a straight-through cable connect Phone B to FSNA-SW2
</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/1jLDU1H.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
#show running-config (on FSNA-RTR, to verify ephone 2 is automatically added)
</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/7EaBoFG.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Configure Directory Numbers
</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/XsLWZMA.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Confirm Phone Registration
</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/xEcMH1V.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Confirm Internal & Outbound Dialing
</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/aFWvA8C.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Review VoIP Configurations on FSNA-RTR
</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/uHBPpnn.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Review Access Control List allowing VoIP Provider
</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/Pi8cPnA.png" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Review VoIP Quality of Service across the WAN
</p>
<br />
</p>
<br />
