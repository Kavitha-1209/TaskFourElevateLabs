#### Setup and Use a Firewall on Windows



##### **🎯 Objective**



To configure and test basic firewall rules using Windows Defender Firewall, including blocking port 23 (Telnet), allowing port 22 (SSH), and testing the rules.





---



##### **🛠 Tools Used**



Windows Defender Firewall with Advanced Security



Telnet Client (for testing)



Snipping Tool (for screenshots)







---



##### **📋 Steps Performed**



1\. Opened Windows Defender Firewall with Advanced Security



Accessed via Start Menu → Searched and opened Advanced Firewall Settings







2\. Created an Inbound Rule to Block Port 23 (Telnet):



Chose Port → Selected TCP → Specified port 23



Action: Block the connection



Applied to all profiles (Domain, Private, Public)



Named the rule: Block Telnet 23







3\. Tested the Rule Using Telnet



Opened Command Prompt



Ran the command:



telnet localhost 23



Result: Connection failed — confirming the firewall successfully blocked port 23







4\. Created an Inbound Rule to Allow Port 22 (SSH):



Followed same process



Port: 22



Action: Allow the connection



Named the rule: Allow SSH 22







5\. Deleted the Block Rule to Restore Original State



Right-clicked on Block Telnet 23 in Inbound Rules



Selected Delete







6\. Took Screenshots as Deliverables



Screenshot of Block Telnet 23 rule



Screenshot of Allow SSH 22 rule



Screenshot of Telnet connection test result



---



##### **📎 Firewall Rules Applied**



✅ Blocked: Port 23 (Telnet)



✅ Allowed: Port 22 (SSH)







---





