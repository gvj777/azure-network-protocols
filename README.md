<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Azure Resource Groups and Inspecting Traffic within Azure Virtual Machines</h1>
In this tutorial, we observe resource groups in Azure and entering Azure Virtual Machines with Wireshark. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1
- Step 2 
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/kZU2zkS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Microsoft Azure I created a resource group called osTicket. Within this resource group included a vitural machine with an public IP address which was used on remote desktop to install and operate osTicket. In addition my resource group included a network security group, virtual network, network interface, and a disk.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZYuJ9iL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once tapped into the osTicket virtual machince, I am able to see all properties, as well as networking configurations such as the public and private IP address. This virtual machine is operating using Windows 10.
</p>
<br />
