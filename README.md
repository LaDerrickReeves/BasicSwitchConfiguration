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
The show vlan brief command is used to verify the VLAN configuration on S1 and ensure the VLAN assignments are correct.:  <br/>
<img src="https://i.imgur.com/PmdIjS6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The show ip interface brief command is used toverify the IP address, interface statuses, and connectivity readiness on S1. :  <br/>
<img src="https://i.imgur.com/Tzfn3pP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The show running-config | include banner command is used  to verify that a banner message was configured.:  <br/>
<img src="https://i.imgur.com/kFRyRuv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The show interface vlan 99 command is used to verify the status, IP address, and operational condition of VLAN 99 on S1.:  <br/>
<img src="https://i.imgur.com/YaQYqkM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
The ping 192.168.1.2 command was used to test end-to-end connectivity to S1's VLAN 99.:  <br/>
<img src="https://i.imgur.com/P6kFo5N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
verify connection to Telnet :  <br/>
<img src="https://i.imgur.com/djg1Fe1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
