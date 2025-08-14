<h1>Basic Swicth Configuration</h1>



<h2>Description</h2>
This project uses Cisco IOS CLI and Windows PowerShell to configure a basic switch and verify connectivity.


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
-  <b>Cisco ISO CLI</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Cisco Virtual Switch</b> 

<h2>Program walk-through:</h2>

<p align="center">
topology: <br/>
<img src="https://i.imgur.com/EuEoyBW.png" height="80%" width="80%" alt="Basic Swicth Configuration steps"/>
<br />
<br />
Configure the basic settings on the switch.:  <br/>
<img src="https://i.imgur.com/ykMYOmR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XryIWdf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
<br />
<br />
Configure IPv4 and IPv6 addresses on PC-A: <br/>
<img src="https://i.imgur.com/umun8ZI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/wiXwQoM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
I used the show vlan brief command to verify the VLAN configuration on S1 and ensure the VLAN assignments are correct.:  <br/>
<img src="https://i.imgur.com/PmdIjS6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I used the show ip interface brief command to verify the IP address, interface statuses, and connectivity readiness on S1. :  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
