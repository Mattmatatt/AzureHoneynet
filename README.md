# Setting up SIEM + Honeynet in Azure (Live Traffic)

## Introduction

In this project, I build a mini honeynet in Azure and ingest log sources from various resources into a Log Analytics workspace, which is then used by Microsoft Sentinel to build attack maps.

## SIEM Setup
[Turning off the firewall](https://imgur.com/A1RGY2i)<br>
[Pinging the machine](https://imgur.com/9iisNfT)<br>
[Connect to Honeypot](https://imgur.com/pt4NtB3)<br>
[Mattfailer login attempt](![image](https://github.com/user-attachments/assets/57d42f34-f76b-40d5-9989-937e590cd6df)<br>
[Mattfailer proof of login attempt](https://imgur.com/8xyWILO)<br>

[Image 1](https://imgur.com/q3V4Whz)<br>
[Image 2](https://imgur.com/ZvDfTTF)<br>
[Image 3](https://imgur.com/PZJNfVK)<br>
[Image 4](https://imgur.com/zs3whvN)<br>
[Image 5](https://imgur.com/7Wusnr4)<br>

## Attack Maps After Being Open to the Internet
![RDP Map over 24 hours with an exposed VM Honeynet](https://i.imgur.com/kkpRk6J.gif)<br>

## Conclusion

In this project, a mini honeynet was constructed in Microsoft Azure and log sources were integrated into a Log Analytics workspace. Using the geolocation data from failed login attempts to the machine Microsoft Sentinel was employed to create a live attack map that showed where attacks were coming from and the importance of securing your workstation. 
