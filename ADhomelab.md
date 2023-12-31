<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://www.youtube.com/watch?v=MHsI8hJmggI&list=PLqBeiU46hx1H--SNfTrohTOWeqkK-M2Y0)

<h2>Description</h2>
In this lab I created a domain controller using windows 2019 server and a domain using windows 10. I will run a script to create a thousand users to simulate an enterprise environment, this will enhance my knowledge of Active Directory and Windows networking, gaining a deeper understanding of their functioning. After completing the lab setup, I not only had a functional Active Directory environment but also the skills to recreate it independently. This hands-on experience familiarized me with various network configuration options and the essential tools needed to configure Windows Server 2019 and Windows 10 clients, effectively simulating an enterprise-grade environment.
<br />




<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>CMD</b>
- <b>Active Directory</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Microsoft Server 2019</b>

## Links 
- https://www.virtualbox.org/
- https://www.microsoft.com/en-us/software-download/windows10ISO
- https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019

<h2>Program walk-through:</h2>

<p align="center">
Active Directory Project Topology : <br/>
<img src="Screenshot from 2023-09-03 21-24-37.png" height="80%" width="80%" alt="Project Topology"/>
<br />
<br />
Downloaded 2019 and windows 10 ISO:  <br/>
<img src="Screenshot from 2023-09-03 22-25-57.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured Internal and external nic cards and configured internal networks address <br/>
<img src="Screenshot from 2023-09-03 22-52-25.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Added DCHP, RAS/NAT and remote access roles:  <br/>
<img src="Screenshot from 2023-09-03 23-17-30.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating users:  <br/>
<img src="Screenshot from 2023-09-03 23-46-03.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Experiment and Explore:  <br/>
- Now that your homelab is up and running, take the time to experiment and explore various features and services offered by Windows Server 2019 and Active Directory.
- Set up additional roles like DNS, DHCP, and File Server to expand your lab's capabilities and simulate real-world scenarios.
- Try integrating Windows Server with other technologies, such as Microsoft Exchange or Microsoft SQL Server, to enhance your learning.
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
