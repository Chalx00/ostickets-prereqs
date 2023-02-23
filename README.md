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

- Enable Internet Information Services (IIS)
- Install PHP
- Install MySQL
- Install osTicket
- osTicket Helpdesk

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/WPL95nH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: In order to enable internet information services, these are the steps to take: connect azure VM via remote desktop > Right-Click Start menu > Run > Control (opens control panel) > Programs > Turn Windows Features on/off > Check the IIS box & expand > Check World Wide Web box >Application Dev Features > Check CGI box >OK.


</p>
<br />

<p>
<img src="https://i.imgur.com/UNC0YgF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we need to install PHP Manager and all dependencies. Create a PHP directory in the c: drive and extract all PHP files & their contents into this directory.
</p>
<br />

<p>
<img src="https://i.imgur.com/gbESTPw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Thirdly, we need to install a database, osTicket will run on MySQL.
</p>
<br />

<p>
<img src="https://i.imgur.com/tQksM8K.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, install heidiSQL which allows you connect to MySQL server and set up a database for OsTicket to utilize. Inaddition to osTicket installation, we have to enable extensions, edit permissions and set up osTicket in browser.
</p>
<br />


<p>
<img src="https://i.imgur.com/EnWJDdQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTickets up and running.
</p>
<br />
