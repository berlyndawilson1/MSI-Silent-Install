<h1>Google Chrome Enterprise MSI Installer</h1>

 

<h2>Description</h2>
My project will showcase a streamlined method for deploying Google Chrome Enterprise using an MSI installer via command line. This silent installation process executes automatically without any user interaction, minimizing disruptions to workflow. The primary goal is to implement Chrome Enterprise seamlessly in the background, allowing users to remain focused on their tasks without being interrupted by installation prompts or procedures
<br />


<h2>Utilities Used</h2>

- <b>Windows Server 2019</b> 
- <b>PowerShell</b>

<h2>Environments Used </h2>

- <b>Azure Virtual Machine</b>

<h2>Program walk-through:</h2>

<p align="center">
Download Google Chrome Enterprise MSI 64-bit file: <br/>
<img src="https://imgur.com/P8fDhzW.png" height="80%" width="80%" alt="MSI Installer Download Steps"/>
<br />
<br />
Choose File Type and Download MSI Installer:  <br/>
<img src="https://imgur.com/rpWQztV.png" height="80%" width="80%" alt="MSI Installer Download Steps"/>
<br />
<br />
Open PowerShell as Admin Navigate to Install_Chrome Folder: <br/>
<img src="https://imgur.com/hTkSnHM.png" height="80%" width="80%" alt="MSI Installer Download Steps"/>
<br />
<br />
Create Installation Troubleshooting Log File Using /L*V:  <br/>
/L Turns on Logging V add Verbose to Output for Detailed Information:  <br/>
<img src="https://imgur.com/S6pCkE4.png" height="80%" width="80%" alt="MSI Installer Download Steps"/>
<br />
<br />
Install Google Chrome Enterprise Business:  <br/>
/QN Quiet Mode No Prompts N No User Interaction or Visual Feedback:  <br/>
<img src="https://imgur.com/Zzqz297.png" height="80%" width="80%" alt="MSI Installer Download Steps"/>
<br />
<br />
Installation Logs:  <br/>
<img src="https://imgur.com/cFRZGx3.png" height="80%" width="80%" alt="MSI Installer Download Steps"/>
<br />
<br />
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
