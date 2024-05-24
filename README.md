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

- Configure Roles
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/27HkeMc.png"/>
</p>
<p>
1) We are currently in the Agent Panel click Admin Panel to change views.
</p>
<br />

<p>
<img src="https://i.imgur.com/fpUBYN6.png"/>
</p>
<p>
2) Now let’s configure an Agents’ role and give them Supreme Admin. (Admin Panel -> Agents -> Roles -> Add a new role -> Grant all permissions in every tab)
</p>
<br />

<p>
<img src="https://i.imgur.com/iZfpziF.png"/>
</p>
<p>
3) Create a new Department called System Administrators. (Admin Panel -> Agents -> Departments)
</p>
<br />

<p>
<img src="https://i.imgur.com/oOFhdKs.png"/>
</p>
<p>
4) Create a new team and add the previous account created as a team member
</p>
<br />

<p>
<img src="https://i.imgur.com/hnHaCMk.png"/>
</p>
<p>
5) Allow anyone to create tickets, ensure that “Require registration and login to create tickets” is unchecked (Admin Panel -> Settings -> User Settings)
</p>
<br />

<p>
<img src="https://i.imgur.com/0zDBUS8.png"/>
</p>
<p>
6) Create two new agents, set their username and password. Uncheck “Send the agent a password reset email” and “Require password change at next login.” (Admin Panel -> Agents -> Add New)
</p>
<br />

<p>
<img src="https://i.imgur.com/FYspnxq.png"/>
</p>
<p>
7) Configure two users (Customers). (Agent Panel -> Users -> Add New)


</p>
<br />

<p>
<img src="https://i.imgur.com/rQ2aRtH.png"/>
</p>
<p>
8) Create three severities varying priority (Admin Panel -> Manage -> SLA)
</p>
<br />

<p>
<img src="https://i.imgur.com/h33DWIf.png"/>
</p>
<p>
9) Configuring Help Topics for ticket options. (Admin Panel -> Manage -> Help Topics)                                                              You've successfully successfully learned how to create users, configured SLAs and Help Topics!
</p>
<br />
