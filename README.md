<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP Manager
- Rewrite Module
- PHP 7.3.8
- VC_redist.x86
- MySQL
- OsTicket
- HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/rwsDH3w.png"/>
</p>
<p>
Create a virtual machine in Azure that runs Windows 10 and has 2-4 cores. Once it's intiated connect to it with remote desktop and enable IIS. Do this by clicking on the search bar and searching control panel then go to programs and then click Windows features on or off and enable Internet Information Serves and then enable CGI inisde of Application Development Features and Common HTTP Features also make sure IIS Management Console is enabled inside of WebManagement Tools.
  
</p>
<br />

<p>
<img src="https://i.imgur.com/8h1Wvvb.png"/>
</p>
<p>
Open a web browser and type in 127.0.0.1 and if the installation worked then this page should appear. This address is the loopback address.
</p>
<br />

<p>
<img src="https://i.imgur.com/SYRLT8t.png"/>
</p>
<p>
Install PHP Manager band be sure to click download anyway. then install the rewrite module and do the same. Use these links: <br />
  PHP Manager: https://drive.google.com/file/d/1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_/view?usp=share_link
  <br />
  Rewrite module: https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view?usp=share_link
</p>
<br />

<p>
<img src="https://i.imgur.com/7xgSxDS.png"/>
</p>
<p>
Create a folder in the C drive called PHP this is directory C:\PHP. Next install PHP 7.3.8 by using the link below: <br />
  https://drive.google.com/file/d/1snNMtLdCOpMtkCyD4mvl9yOOmvVIp9fP/view?usp=share_link
</p>
<br />

<p>
<img src="https://i.imgur.com/zfLe0GP.png"/>
</p>
<p>
This will download a ZIP file go to downloads in file explore right click on the folder and extract to C:\PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/urpGkfs.png"/>
</p>
<p>
Install VC_Redist and MySQL. The links will be below. When the setup wizard for MySQL launches do a typial and standard setup. Then set the password to be password1. <br \>
VC: https://drive.google.com/file/d/1s1OsGF3-ioO0_9LYizPRiVuIkb3lFJgH/view?usp=share_link
MySQL: https://drive.google.com/file/d/1_OWh9p7VQLcrB0q_V7qT8yHl0xo5gv7z/view?usp=share_link
</p>
<br />

<p>
<img src="https://i.imgur.com/RtJ3X2v.png"/>
</p>
<p>
Go to the Windows search bar and type in Internet Information Services to open its management window. Click on PHP manager and then register PHP with the directory shown in the above screen shot. After registering PHP reload IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/cfzo00u.png"/>
</p>
<p>
Use the installation file link to install OsTicket and extract the upload folder to c:\inetpub\wwwroot  and rename it to osTicket then reload IIS. Be sure to be running IIS as an administrator <br \>
Installation File: https://drive.google.com/drive/u/2/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6
</p>
<br />

<p>
<img src="https://i.imgur.com/T85wCxZ.png"/>
</p>
<p>
If every step was done correctly then you should see this screen when you click browse 80 on IIS after going to the Default Website branch on the left of the IIS managaer. 
</p>
<br />

<p>
<img src="https://i.imgur.com/o5jn685.png"/>
</p>
<p>
Go to the PHP manager and click on enable extensions and enable the extensions listed below by scrolling to it, right clicking and clicking enable rule: <br \>
Enable: php_imap.dll
  <br \>
Enable: php_intl.dll
  <br \>
Enable: php_opcache.dll

  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

