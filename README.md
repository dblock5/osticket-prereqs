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

- Enable Internet Information Services (IIS) with CGI and common HTTP Features
- Install PHP Manager for Internet Information Services (IIS) and install rewrite     module
- Download and install C++ Redistributable (VC_redist.x86.exe)
- Install MySQL server and install HeidiSQL (database client)
- Configure IIS permissions and install osTicket

<h2>Installation Steps</h2>

<p>
  <img width="523" alt="image" src="https://github.com/dblock5/osticket-prereqs/assets/102873312/2da9e63a-e3af-443f-93cf-547705d58ed4">

</p>
<p>
  Using a virtual machine through Azure, I installed and enabled Internet Information Services (IIS), a web server that will allow osTicket to run. Then I enabled CGI and other common HTTP features. Then checked to see if IIS was correctly installed by typing the loopback address (127.0.0.1) into the browser which displayed a page thst says Internet Information Services.

</p>
<br />

<p>
<img width="495" alt="image" src="https://github.com/dblock5/osticket-prereqs/assets/102873312/c9ad5810-9f7d-4af3-968f-1400ff37140a">


</p>
<p>
Installed PHP Manager for Internet Information Services and then installed Rewrite Module which is required for osTicket to work. Then created a directory for PHP on the local hard drive and extracted the files from the PHP download and unzipped it into C:\PHP directory that was created.
</p>
<br />

<p>
<img width="500" alt="image" src="https://github.com/dblock5/osticket-prereqs/assets/102873312/ad19275a-8629-40ae-8ba8-ee9064789e75">

</p>
<p>
Then, I installed a C++ redistributable (VC_redist.x86.exe) which may be required for PHP to work.
</p>

<br />
<p>
<img width="515" alt="image" src="https://github.com/dblock5/osticket-prereqs/assets/102873312/7d3d965f-8f47-434b-80f6-cabde32eb223">


<img width="492" alt="image" src="https://github.com/dblock5/osticket-prereqs/assets/102873312/ae90bdbf-6326-48f9-b9a6-1f1506c501f4">

</p>
<p>
Installed a database called MySQL server because osTicket requires this in order to store application data such as users, tickets etc. Then I installed HeidiSQL which allows you to connect to MySQL database that osTicket will use. Then I registered PHP from within ISS in order to enable PHP. 
</p>
<br />
<p>
  <img width="488" alt="image" src="https://github.com/dblock5/osticket-prereqs/assets/102873312/766a2b1c-22a6-4491-a561-9226f8568afb">

<img width="859" alt="image" src="https://github.com/dblock5/osticket-prereqs/assets/102873312/f2071535-3633-46a5-ad72-ac4e550d737e">
  
</p>
<p>
Then, I configured IIS permissions and enabled different extensions in the PHP manager and installed osTicket and created a new session/created a database on HeidiSQL that osTicket will use. Then I connected the database to osTicket, finished osTicket download/signup and successfully connected to osTicket. 
</p>
