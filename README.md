<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://i.imgur.com/dJ3Sk3F.png" height="75%" width="100%" alt="Definitions"/>
  <img src="https://i.imgur.com/VzSk44H.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://i.imgur.com/VbO11Me.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://i.imgur.com/37vhCKs.png" height="75%" width="100%" alt="Even More Permissions"/>
  
</p>
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://i.imgur.com/s7gxKBO.png" height="75%" width="100%" alt="System Administrators"/>
  <img src="https://i.imgur.com/PeprXd2.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Level II Support:
</p>
<p>
  <img src="https://i.imgur.com/wveBIEE.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>
  <img src="https://i.imgur.com/4FknXCK.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  John Doe:
</p>
  <img src="https://i.imgur.com/zXOqKTc.png" height="75%" width="100%" alt="agent one access"/>
<p>
  Jane Doe: Account Picture not included
</p>
<p>
  <img src="https://i.imgur.com/49sgVa4.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/2meca93.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Ken User:
</p>
  <img src="https://i.imgur.com/xVNPDqD.png" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Karen User.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://i.imgur.com/dkeTndb.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/3pKElTc.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/ZgZ4e3o.png" height="75%" width="100%" alt="sev three"/>
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://i.imgur.com/lNBWHtY.png" height="75%" width="100%" alt="business critical outage"/>
 
</p>
<br />
<br />
<p>
  This concludes of different topics you can play around with in osTicket. One should try exploring the system on their own to see how it works.This is a important skill to have for any help desk specialist role, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>
