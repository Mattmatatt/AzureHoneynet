# Setting up SIEM + Honeynet in Azure (Live Traffic)

## Introduction

In this project, I build a mini honeynet in Azure and ingest log sources from various resources into a Log Analytics workspace, which is then used by Microsoft Sentinel to build attack maps.

## Attack Maps After Being Open to the Internet
![RDP Map over 24 hours with an exposed VM Honeynet](https://i.imgur.com/kkpRk6J.gifv)<br>

## Conclusion

In this project, a mini honeynet was constructed in Microsoft Azure and log sources were integrated into a Log Analytics workspace. Using the geolocation data from failed login attempts to the machine Microsoft Sentinel was employed to create a live attack map that showed where attacks were coming from and the importance of securing your workstation. 
