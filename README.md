<h1>Active Directory User Creation with PowerShell</h1>

<h2>Description</h2>
This lab details the use of a PowerShell script to automate the creation of 1k+ users in an Active Directory environment. It follows the completion of the Active Directory Domain environment setup lab.
<br />


<h2>Technologies Used</h2>

- <b>Virtualization</b> 
- <b>Active Directory</b>
- <b>PowerShell</b>

<h2>Environments</h2>

- <b>Oracle VirtualBox</b>
- <b>Windows Server 2022</b>
- <b>Windows 10</b>

<h2>Program Walk-Through:</h2>

<p align = "center">
Log in to your new admin account: <br/>
  <br/>
<img src="https://i.imgur.com/hytSSCL.png" height="80%" width="80%" alt="Active Directory PowerShell"/>
<br />
<br />
Create a file on the desktop with the script and a text file with the first and last names of the users to be created:  <br/>
  (Be sure to add a memorable user so that you can log into it as a test)
  <br/>
  <br/>
<img src="https://i.imgur.com/qkzJOuH.png" height="80%" width="80%" alt="NAS setup"/>
<br />
<br />
In PowerShell ISE, navigate to the directory containing the names text file and run the script: <br/>
  <br/>
<img src="https://i.imgur.com/fsULeGd.png" height="80%" width="80%" alt="NAS setup"/>
<br />
<br />
Once the script is done running, all the users should be visible in the Active Directory Users and Computers tool:  <br/>
  <br/>
<img src="https://i.imgur.com/1Oy1GRB.png" height="80%" width="80%" alt="NAS setup"/>
<br />
<br />
Log in to one of the newly created users on a Windows 10 Client that is connected to the domain:  <br/>
  <br/>
<img src="https://i.imgur.com/WsqgegR.png" height="80%" width="80%" alt="NAS setup"/>
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
