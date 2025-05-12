# Cybersecurity Home Lab: Detecting Attackers with Azure and Microsoft Sentinel

## Overview
This project demonstrates a cybersecurity home lab to detect real-world cyber attacks using a honeypot virtual machine (VM) in Microsoft Azure, Log Analytics Workspace, and Microsoft Sentinel. The lab captures failed RDP login attempts, parses them with a PowerShell script, and visualizes attacker geolocations on a world map.
This lab provides me hands-on experience with cloud security, SIEM tools, PowerShell scripting, and Kusto Query Language (KQL).

## Project Steps
1. Create a Resource Group

   • Created a Resource Group named “HoneyPot-Lab” in Azure to organize lab resources. 
   
   • Selected region: Central India

   Scrrenshot: ![RG](Screenshots/RG_creation.png)


2. Create Virtual Network

    ![Vnet](Screenshots/Virtual_net_creation.png)
    ![Vnet](Screenshots/Virtual_net_creation(2).png)

3. Next, create a virtual machine for attackers to attack

    ![Vnet](Screenshots/)
