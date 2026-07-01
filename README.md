<h1>Group Policy Tickets</h1>

<h2>Description</h2>
Project consists of using a virtual homelab environment to perform Group Policy related tasks between a Domain Controller and User computers. 
<br />



<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
1. Search Group Policy Management: <br/>
<img src="https://i.imgur.com/usWWH2U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click onto the Domain:  <br/>
<img src="https://i.imgur.com/1FNeAR3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create New Organizational Unit: <br/>
<img src="https://i.imgur.com/6pESv0I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create New User within New OU:  <br/>
<img src="https://i.imgur.com/RHyoygK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
New User Profile Made:  <br/>
<img src="https://i.imgur.com/TSsHT1p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2. Right Click OU to create new GPO:  <br/>
<img src="https://i.imgur.com/eoR00EA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right Click New GPO to Edit:  <br/>
<img src="https://i.imgur.com/5Iggplg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Prohibit Control Panel access on GPO Management Editor:  <br/>
<img src="https://i.imgur.com/D5FqLjL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable New Policy:  <br/>
<img src="https://i.imgur.com/o0tqyBg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log onto User Account:  <br/>
<img src="https://i.imgur.com/BG32SDs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Access Command Line to force the Group Policy update:  <br/>
<img src="https://i.imgur.com/VHq6ezD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Observe access to Control Panel is denied:  <br/>
<img src="https://i.imgur.com/gskYbmW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right Click New GPO to Edit:  <br/>
<img src="https://i.imgur.com/5Iggplg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Prohibit Control Panel access on GPO Management Editor:  <br/>
<img src="https://i.imgur.com/D5FqLjL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>
