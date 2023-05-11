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

- Computer
- Microsoft Azure 
- Resource Group
- Virtual Machines


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Ioau9ci.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First we need to install IIS (Internet Information Services) which is essentially a webserver that allows computers to serve up websites. Since OsTicket runs on a website. CGI needs to be installed so we can use PHP manager.

PHP is a backend programming language and OsTicket runs off PHP.
</p>
<br />

<p>
<img src="https://i.imgur.com/GaNF3Ky.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download PHP.
</p>
<br />

<p>
<img src="https://i.imgur.com/jkad7CN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download Rewrite Module.
</p>
<br />

<p>
<img src="https://i.imgur.com/mcXCFBn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create the directory C:\PHP.
</p>
<br />

<p>
<img src="https://i.imgur.com/9neBZfA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I downloaded PHP 7.3.8 and began extracting all the files into the C:\PHP directory,
</p>
<br />

<p>
<img src="https://i.imgur.com/oCMEElc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2nd part of the extraction.
</p>
<br />

<p>
<img src="https://i.imgur.com/MyLRHJW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download Microsoft Visual C++.
</p>
<br />

<p>
<img src="https://i.imgur.com/lo69S1H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Downloading SQL means we are downloading a databse on the computer. For example, OsTicket needs a database to store information such as tickets and users.
</p>
<br />

<p>
<img src="https://i.imgur.com/qUam0pl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select "Typical".
</p>
<br />

<p>
<img src="https://i.imgur.com/ew6CbKJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the installation, select "Standard Configuration".
</p>
<br />

<p>
<img src="https://i.imgur.com/0TLnmtL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a root password.
</p>
<br />

<p>
<img src="https://i.imgur.com/lFzsmSb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Run IIS as an Administrator 
</p>
<br />

<p>
<img src="https://i.imgur.com/tgJUV0q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Register PHP from within IIS. Once registered, reload IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/RXWkAps.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once OsTicket is downloaded, within the IIS, click “Browse *:80”.
</p>
<br />

<p>
<img src="https://i.imgur.com/PeDHlNh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After clicking “Browse *:80”, the OsTicket webpage will open.
</p>
<br />

<p>
<img src="https://i.imgur.com/nqmhIOc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the webpage is open, you'll notice that there are some "X's". Select PHP Manager so we can enable some extentions.
</p>
<br />

<p>
<img src="https://i.imgur.com/1vYvFGz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
What we see after selecting PHP Manageer.
</p>
<br />

<p>
<img src="https://i.imgur.com/U8SJZIC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After enabling the required extentions, this is what the updated webpage will look like.
</p>
<br />

<p>
<img src="https://i.imgur.com/KOoUQ1Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now Heidi SQL will be installed so we can connect to the MySQL server in order to setup our database.
</p>
<br />

<p>
<img src="https://i.gyazo.com/8c138b74efc451af20cd5a2d24fa5ef1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here a new databse is being created.
</p>
<br />

<p>
<img src="https://i.gyazo.com/7a9d7f7bcbfc0ac2e5126cf2f1d460e1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the database is created, the required information can be entered.
</p>
<br />

<p>
<img src="https://i.gyazo.com/3002908f3f5792876fd6143211bbb54b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After "Install Now is selected, this is the webpage you will see.
</p>
<br />

<p>
<img src="https://i.gyazo.com/0ddb295525ef1add4e8dd5f554f72fc6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use information that was entered previously to login.
</p>
<br />

<p>
<img src="https://i.gyazo.com/d5f929f28556ce697e184e41c5cdd9f7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login was successful into the OsTicket system.
</p>
<br />

