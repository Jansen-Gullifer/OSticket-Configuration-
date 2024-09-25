# OSticket-Configuration-
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install </h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Access Login Pages
- Set Up Teams
- Manage Ticket Creation Settings
- Configure Agents
- Configure Users
- Configure SLAs
- Configure Help Topics

<h2>Configuration Steps</h2>

//Step 1: Access Login Pages
Admin/Analyst Login: Go to http://localhost/osTicket/scp/login.php.
End Users URL: Visit http://localhost/osTicket.

//Step 2: Configure Roles and Departments
Roles: Navigate to Admin Panel > Agents > Roles and create roles (e.g., Supreme Admin).
Departments: Go to Admin Panel > Agents > Departments and set up departments (e.g., Help Desk, SysAdmins) for ticket visibility.

//Step 3: Set Up Teams
In the Admin Panel, go to Agents > Teams and create teams (e.g., Online Banking) by selecting agents from the designated departments.

//Step 4: Manage Ticket Creation Settings
Navigate to Admin Panel > Settings > User Settings. Uncheck the option for unregistered users to create tickets and enable Registration Required for ticket creation.
<p>

![image](https://github.com/user-attachments/assets/ebbfff98-2a89-418c-81ef-fb558e34040b)


</p>
<p>

  //Step 1: Configure Agents
Go to Admin Panel > Agents > Add New.
Add agents:
Jane (Department: SysAdmins)
John (Department: Support)

//Step 2: Configure Users
In the Agent Panel, navigate to Users > Add New.
Add users:
Karen
Ken

//Step 3: Configure SLAs
Go to Admin Panel > Manage > SLA.
Create SLAs:
Sev-A: Grace Period: 1 hour, Schedule: 24/7
Sev-B: Grace Period: 4 hours, Schedule: 24/7
Sev-C: Grace Period: 8 hours, Schedule: Business Hours

//Step 4: Configure Help Topics
Navigate to Admin Panel > Manage > Help Topics.
Add help topics:
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other

</p>

![image](https://github.com/user-attachments/assets/0be11423-cd27-4fa8-a095-c9947bf109fb)


</p>
<br />

