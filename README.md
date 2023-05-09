# Azure-Computation-and-Networking-
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this Lab, you'll observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


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

- Create a windows 10 and ubuntu OS in an azure VM 
- Download wireshark on windows 10 VM with ICMP traffic filter only 
- Open NSG on ubuntu VM enabling all traffic flow 
- Observe various traffic protocols  

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/abg5Mvy.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
While creating the VM, allow it to create a new virtual network and subnet. Verify that both VMs are in the same resource group 
</p>
<br />

<p>
<img src="https://i.imgur.com/px3fpIW.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use Microsoft Remote Desktop (MacOS) or Remote Desktop Connection (Windows) to the connected windows 10 VM 
</p>
<br />

<p>
<img src="https://i.imgur.com/VOIzdUY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Back in Wireshark, filter for SSH traffic only. From the created windows 10 VM, SSH into the ubuntu VM. Input various linux commands and observe SSH traffic spam in wireshark  
</p>
<br />
