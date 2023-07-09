<h1>Active Directory Home Lab</h1>



<h2>Description</h2>
This project consists of a creating a home lab environment using Oracle Virtual Box. We will be installing and configuring Windows Server OS as a domain controller, adding users in Active Directory using Powershell scripts and connecting a client PC to our domain.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Active Directory</b>
- <b>Server Manager</b>
- <b>DHCP</b>
- <b>Routing and Remote Access</b>

<h2>Environments Used </h2>

- <b>Windows Server OS 2019</b>
- <b>Windows 10</b> (21H2)
- <b>VirtualBox</b>

<h2>Lab walk-through:</h2>

<p align="center">Roadmap: <br/>
<img src="https://i.imgur.com/ixpOonX.png" height="60%" width="60%" alt="Home Lab"/>
<br />
<br />
Using Virtual Box Install Windows Server OS with 2 Network Adapters. NAT and Internal :  <br/>
<img src="https://i.imgur.com/yVrbqt0.png" height="50%" width="50%" alt="Home Lab"/>
<img src="https://i.imgur.com/mAsc757.png" height="50%" width="50%" alt="Home Lab"/>
<br />
<br />
Assign IP to Internal Network Adapter: <br/>
<img src="https://i.imgur.com/9u99bf4.png" height="70%" width="70%" alt="Home Lab"/>
<br />
<br />
Install Active Directory:  <br/>
<img src="https://i.imgur.com/M508rCK.png" height="60%" width="60%" alt="Home Lab"/>
<br />
<br />
Create Domain:  <br/>
<img src="https://i.imgur.com/t8Kr6hE.png" height="60%" width="60%" alt="Home Lab"/>
<br />
<br />
Install Routing and Remote Access Tool:  <br/>
<img src="https://i.imgur.com/DeVUqvm.png" height="80%" width="80%" alt="Home Lab"/>
<br />
<br />
Configure NAT:  <br/>
<img src="https://i.imgur.com/eM9O4F0.png" height="60%" width="60%" alt="Home Lab"/>
<br />
<br />
Install DHCP Tool: <br/>
 <img src="https://i.imgur.com/yBQob9u.png" height="60%" width="60%" alt="Home Lab"/>
<br />
<br />
Configure IP Scope: <br/>
<img src="https://i.imgur.com/yX62kn1.png" height="60%" width="60%" alt="Home Lab"/>
<br />
<br />
Run Powershell script to add users from .txt file: <br/>
<img src="https://i.imgur.com/T1r4SxR.png" height="65%" width="70%" alt="Home Lab"/>
<br />
<br />
Using Virtual Box install Windows 10 image with the network adpater set to "internal network": <br/>
<img src="https://i.imgur.com/ha1XIfz.png" height="50%" width="50%" alt="Home Lab"/>
<br />
<br />
Once Desktop is finished setting up, verify Client Desktop IP configurations are correct according to Roadmap: <br/>
<img src="https://i.imgur.com/yBxDAxh.png" height="50%" width="50%" alt="Home Lab"/>
<br />
<br /> 
Verify internet connectivity on Client Desktop: <br/>
<img src="https://i.imgur.com/KZYpG63.png" height="50%" width="50%" alt="Home Lab"/>
<br />
Home Domain Lab Is Setup!
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
