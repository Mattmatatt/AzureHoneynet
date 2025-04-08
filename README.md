# Setting up SIEM + Honeynet in Azure (Live Traffic)

## Introduction

In this project, I build a mini honeynet in Azure and ingest log sources from various resources into a Log Analytics workspace, which is then used by Microsoft Sentinel to build attack maps.

## SIEM Setup
<p align="center">
Turning off the firewall <br/>
<img src="https://imgur.com/A1RGY2i.png" height="80%" width="80%"/>
<br />
<br />
Pinging the machine <br/>
<img src="https://imgur.com/9iisNfT.png" height="80%" width="80%"/>
<br />
<br />
Connect to Honeypot <br/>
<img src="https://imgur.com/pt4NtB3.png" height="80%" width="80%"/>
<br />
<br />
Mattfailer login attempt <br/>
<img src="https://imgur.com/whdXST0.png" height="80%" width="80%"/>
<br />
<br />
Mattfailer proof of login attempt <br/>
<img src="https://imgur.com/8xyWILO.png" height="80%" width="80%"/>

## SIEM Setup
<p align="center">
Geolocation API <br/>
<img src="https://imgur.com/PZJNfVK.png" height="80%" width="80%"/>
<br />
<br />
Running script on honeypot that grabs geolocation of login attempts <br/>
<img src="https://imgur.com/ZvDfTTF.png" height="80%" width="80%"/>
<br />
<br />
Honeypot Logs <br/>
<img src="https://imgur.com/7Wusnr4.png" height="80%" width="80%"/>
<br />
<br />
Create workbook to track location of attacks based on log data <br/>
<img src="https://imgur.com/q3V4Whz.png" height="80%" width="80%"/>
<br />
<br />
  
## Attack Maps After Being Open to the Internet
![RDP Map over 24 hours with an exposed VM Honeynet](https://i.imgur.com/kkpRk6J.gif)<br>

## Conclusion

In this project, a mini honeynet was constructed in Microsoft Azure and log sources were integrated into a Log Analytics workspace. Using the geolocation data from failed login attempts to the machine Microsoft Sentinel was employed to create a live attack map that showed where attacks were coming from and the importance of securing your workstation. 
