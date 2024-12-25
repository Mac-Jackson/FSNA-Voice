<p align="center">
<img src="https://github.com/user-attachments/assets/f7bc25d8-3276-48ae-a47f-5d1de9584c53" alt="Voice Over IP Logo"/>
</p>

<h1>Connect VoIP Phones</h1>
This tutorial focus on the implementation and configuration of Voice over IP (VoIP).<br />


<h2>Networking Technologies Used</h2>

- VoIP (Voice over IP)
- DHCP (Dynamic Host Configuration Protocol)
- CME (Cisco Unified Communications Manager Express)
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
<img src="https://github.com/user-attachments/assets/590f7e5b-4720-41e2-8272-a37c595a20fd" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
 Using a straight-through cable, connect Phone A to FSNA-SW1
 


</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/c39cbbb7-34c2-4383-bb2b-a1a292386324" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
 #show running-config (on FSNA-RTR, to verify ephone 1 is automatically added)
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/0be839aa-9166-48a4-ab98-c4067f0d40b6" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Using a straight-through cable, connect Phone B to FSNA-SW2
</p>
<br />
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/13ad2c51-b2a2-4898-a770-269fbe8f00e4" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
#show running-config (on FSNA-RTR, to verify ephone 2 is automatically added)
</p>
<br />
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/cf53b4e9-0747-4925-8790-1fda6344f817" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Configure Directory Numbers
</p>
<br />
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/19553c81-15e9-4f53-afb2-7f22f447a842" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Confirm Phone Registration
</p>
<br />
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/45fc3991-b144-4c4a-af43-aa89e69e0914" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Confirm Internal & Outbound Dialing
</p>
<br />
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/a9ac06f4-23d3-4690-aa36-f6cfa26e1094" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Review VoIP Configurations on FSNA-RTR
</p>
<br />
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/94d0d0c1-dcc3-4c47-8800-4f2cceed4786" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Review Access Control List allowing VoIP Provider
</p>
<br />
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/65dbb67b-7c51-470c-8a13-3af4b5c35706" height="80%" width="80%" alt="FSNA-Voice"/>
</p>
<p>
Review VoIP Quality of Service across the WAN
</p>
<br />
</p>
<br />
