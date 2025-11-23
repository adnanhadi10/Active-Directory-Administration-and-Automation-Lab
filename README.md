## Active Directory Administration and Automation Lab

### Description
This project focuses on building an **Active Directory** and **Windows network administration** environment using **PowerShell automation**, **Remote Access Server (RAS)** configuration, and **Windows Server** management. Deploying and managing this lab environment strengthens understanding of Active Directory operations and Windows networking principles.

PowerShell scripts are developed and executed to automate the **provisioning, maintenance, and deprovisioning** of user accounts within Active Directory, improving efficiency in identity and account lifecycle processes.

The **RAS** role is configured to support **Network Address Translation (NAT)** and **Port Address Translation (PAT)**, enabling secure and efficient remote access for network connectivity.

In addition, **Windows DNS** and **DHCP** services are administered to provide reliable, automated network addressing. **Windows File Servers** are configured with **quotas** and **NTFS permissions** to maintain secure, organized, and controlled file storage.

This lab demonstrates critical network administration tasks and automation practices, providing hands-on experience with managing **Active Directory** and **Windows networking** environments.

---

### Technologies and Tools
- PowerShell  
- Active Directory  
- Oracle VM VirtualBox

### Operating Environments
- **Windows 10 (22H2)** — CLIENT1 VM  
- **Windows Server 2019** — Domain Controller VM

---

<h2>Network Environment Overview</h2>
<p align="center">
<br/>
<img src="https://github.com/adnanhadi10/Active-Directory-Administration-and-Automation-Lab/blob/a77ff6ef49e5f0368729c0551562d4dc31f53c49/Network%20Diagram.png" height="80%" width="80%" alt="Active Directory Administration Steps"/>
 <br />
</p>

<h2>Screenshots of Key Stages:</h2>

<p align="center">
1. Admin account connected to the domain - mydomain.com: <br/>
<img src="https://github.com/adnanhadi10/Active-Directory-Administration-and-Automation-Lab/blob/188f00b88ae691937dd98c098233ff71087d1e1c/Admin%20Account%20conncected%20to%20Domain.png" 
     height="80%" width="80%" alt="Active Directory Administration Steps" />
<br /><br />

<p align="center">
2. Create a new Admin User in AD _ADMINS Organizational Unit (OU):  <br/>
<img src="https://github.com/adnanhadi10/Active-Directory-Administration-and-Automation-Lab/blob/5f9a56851b03ab9dd6ca272ae578ad13401dc670/Step%207%20Creating%20new%20Admin%20User.png" 
     height="80%" width="80%" alt="Active Directory Administration Steps" />
<br /><br />

<p align="center">
3. Logging into the Newly Created User: <br/>
<img src="https://github.com/adnanhadi10/Active-Directory-Administration-and-Automation-Lab/blob/bd4c668d348acdab6d7bb16443eeb425084c58f9/Logging%20with%20the%20Admin%20account.png" 
     height="80%" width="80%" alt="Active Directory Administration Steps" />
<br /><br />


<p align="center">
4. Configuring RAS for NAT and PAT:  <br/>
<img src="https://i.imgur.com/w9QEE7o.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />

<p align="center">
5. Setting up DHCP:  <br/>
<img src="https://i.imgur.com/WdhgMp8.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />


<p align="center"> 
6. Run PowerShell Script to Create 1k+ Users in AD:  <br/>
<img src="https://i.imgur.com/CrhIES1.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />

<p align="center">
7. Overview of 1k+ Created Users in AD using PS script:  <br/>
<img src="https://i.imgur.com/qpUVPKU.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />

<p align="center"> 
8. Check if "CLIENT1" is connected to default gateway and joined to domain:  <br/>
<img src="https://i.imgur.com/bvpin7v.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />

<p align="center"> 
9. "CLIENT1" gets assigned an IP address by the DHCP server:  <br/>
<img src="https://i.imgur.com/opoV54e.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>




