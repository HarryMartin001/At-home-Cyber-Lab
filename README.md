Hi! I'm Harry. 

 College Student.





# This Project
This is a instructional step by step process to building a functional **Cybersecurity Homelab** for offensive and defensive security.

My purpose for this lab is to learn more about Security Monitoring and Detection Engineering.


# Hardware
This lab will be running on a Server/PC specifically built for the purpose of labbing.

**PC Parts:** https://pcpartpicker.com/list/xfBQXv


# Virtual Machines
This lab consists of:

  ~ **Kali:** This is the offensive machine that will be used to propagate different forms of attacks.
	
  ~ **pfsense:** This will be the firewall for controlling inbound and outbound traffic, only accessible and visible in the VM private network.
	
  ~ **Security Onion:** This will be the all-in-one IDS, Security Monitoring and Log Management solution.
	
  ~ **Splunk:** This is an additional SIEM that will be used in addition and comparison to Kibana on Security Onion.
	
  ~ **Windows DC:** This is a windows domain controller that will have two windows machines connected to it.
	
  ~ **Windows 7 & Windows *XP*:** These windows machine will vary based on individual needs.
	
  ~ **Ubuntu/Centos/Metasploitable/DVWA/Vulnhub machines:** All these are potential linux machines that can be added to the network for exploitation, detection, or monitoring purposes.


# Network Design
![Splunk and vlans](https://github.com/HarryMartin001/At-home-Cyber-Lab/assets/111730072/5b95be0a-016a-4bb7-8515-44b0dc8acd98)
