<h1>Virtual Machine Home Lab</h1>


<h2>Description</h2>
In this lab, I set up four virtual machines using Oracle VirtualBox: one Windows 10, one Windows Server 2022, one Ubuntu, and one Kali Linux, all connected via a NAT network to create a secure testing environment. Each VM was created by allocating appropriate system resources and configuring network settings to ensure they can communicate internally while maintaining internet access. After installing the operating systems from their respective ISO images and performing necessary updates, I verified connectivity between the VMs and the internet. This setup allows for safe experimentation and testing of various tools and applications without exposing the host machine or the VMs to external threats.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b> 

<h2>Environments Used </h2>

- <b>Virtual Box</b>
- <b>Windows 10</b>
- <b>Kali Linux</b>
- <b>Windows 2022 Server</b>
- <b>Ubuntu</b>

<h2>Program walk-through:</h2>

<p align="center">
Setup Elastic Account: <br/>
<img src="https://i.imgur.com/K7h238x.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Download Kali VM:  <br/>
<img src="https://i.imgur.com/AP0w2ka.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Download Virtual Box: <br/>
<img src="https://i.imgur.com/bZwzmSP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add Kali VM to Virtual Box:  <br/>
<img src="https://i.imgur.com/K6Ez3NW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setup Defend Inetgration on Elastic and add to Kali VM:  <br/>
<img src="https://i.imgur.com/LCfeybq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check Status:  <br/>
<img src="https://i.imgur.com/R2UeFEu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run Nmap command:  <br/>
<img src="https://i.imgur.com/xZ24ifF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check logs on Elastic stack:  <br/>
<img src="https://i.imgur.com/ZTH550X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Visualization:  <br/>
<img src="https://i.imgur.com/j27tKZl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Rule:  <br/>
<img src="https://i.imgur.com/luykfwP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Email Alert:  <br/>
<img src="https://i.imgur.com/UEWJTDc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
