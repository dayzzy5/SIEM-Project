# SIEM-Project
<h1>Failed RDP to IP Geolocation Information</h1>


<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attacker's location.
</b>
<br />
<br />
The script is used in this demo where I set up Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
I will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attacker's Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/fWL0FD5.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from Tunisia coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/0QNfBFb.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 12 hour (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/TfhIegZ.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
