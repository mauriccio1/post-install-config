<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>
<ul>
 <li> Create New Agents </li>
<li>create a new department </li>
<li>create a new role as well as a team</li>
<li> Create 3 SLA's (service Level Agreement)</li>
</ul>

<h1>Configuration Steps</h1>

<p>
<img src="https://i.imgur.com/ntF1G8p.png" height="80%" width="80%" alt="startup"/>
</p>
<p>
  This is the osTicket dashboard after successfully installing logging in for the first time.
</p>
<br />

<p>
<img src="https://i.imgur.com/N7RdgR3.png" height="80%" width="80%" alt="Agents"/>
</p>
<p>
  <h2> Creating New Agents </h2>
From the dashboard (make sure to be on the "admin" panel) select Agents tab. 
  Here you can create new Agents who will be the actual employees assigned to tickets by Admins. <br>
  Agents can also be the administrators assigning incoming tickets.
From the agents tab you can you can also create new departments, roles, and different teams. 
</p>
<br />

<p>
<img src="https://i.imgur.com/L9EHnKd.png" height="80%" width="80%" alt="SLA's"/>
</p>
<p>
Now select the manage tab  (still in the admin panel). Here you can create new SLA's. In this example the SLA was names SEV-A (high severity ticket) and was only given a grace period of 1 hour to respond. This ticket would need to be worked on 24/7 until the ticket was resolved. 
</p>
<br />
