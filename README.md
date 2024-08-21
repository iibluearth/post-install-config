# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install of the open-source help desk ticketing system osTicket.<br />

 <h2>Environments and Technologies Used</h2>

 - Microsoft Azure (Virtual Machines/Compute)
 - Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Post-Install Configuration</h2>

- Configure Roles, Departments, and Teams
- Configure Service-Level Agreement (SLA)
- Configure Help Topics

 <h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/FjWfkIf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Configuring Supreme Admin Role:

- Navigate to http://localhost/osTicket/scp/login.php through your browser.
- Log in using the osTicket account credentials (User: kayla / Password: Labpassword1).
- After logging in, click "Admin Panel" in the top right corner.
</p>
<br />

<p>
<img src="https://i.imgur.com/qm4Q4bk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/NPC8c90.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/Y0UGdY6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/LxV9e2G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
2. Creating Supreme Admin Role:

- Go to the "Agents" tab and click on "Roles".
- Select "Add New Role".
- Name the role "Supreme Admin" under the "Definition" tab.
- Under the "Permissions" tab, check all options under Tickets/Tasks/Knowledgebase.
- Click "Add Role" to finish.
</p>
<br />

<p>
<img src="https://i.imgur.com/U0yY27E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Adding System Administrators Department:

- Under the "Agents" tab, click "Departments".
- Choose "Add New Department".
- Name the department "System Administrators" and click "Create Dept".
</p>
<br />

<p>
<img src="https://i.imgur.com/SKEoAV2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Setting Up Level II Support Team:

- Again under the "Agents" tab, click on "Teams" and then "Add New Team".
- Name this team "Level II Support" and add "John" as a member.
- Click "Create Team" when finished.
</p>
<br />

<p>
<img src="https://i.imgur.com/JiiVJIS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/JaOHgKY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/1Wa5P4r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/SWGg2sW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/Wme8FLh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Creating Agents:

- Under the "Agents" tab, click "Add New Agent".
- Create an agent named "Jane Doe" with basic information.
- Assign "Jane" to the "System Administrators" department with the "Supreme Admin" role.
- Additionally, assign "Jane" to the "Support" department with the "Supreme Admin" role.
- Create "Jane" as a member of the "Level II Support" team.
- Repeat the process to create "John Doe" with limited access to the "Support" department.
- Use the provided agent info for both.
- Name: Jane Doe / Email Address: jane.doe@osticket.com / Username: jane.doe / Password: Labpassword1
- Name: John Doe / Email Address: john.doe@osticket.com / Username: john.doe / Password: Labpassword1
</p>
<br />

<p>
<img src="https://i.imgur.com/ghOosNK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/FhrojRM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Creating Users/Customers:

- In the "Agent Panel", under the "Users" tab, select "Add User".
- Create simple users named "Alex" and "Ashley" with basic email addresses.
- Click "Add User" to finish.
- Alex / alex@osticket.com
- Ashley / ashley@osticket.com
</p>
<br />

<p>
<img src="https://i.imgur.com/vJx7IXB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/leZbtR0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/FYX3oiF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/uCATlRM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Setting SLA Plans:

- In the "Admin Panel", go to the "Manage" tab and click "SLA".
- Select "Add New SLA Plan".
- Create three SLA plans with varying severity levels, according to the provided list.
- Fill out the required fields for each plan and click "Add Plan".
1. Name: Sev-A / Grace Period: 1 / Schedule: 24/7
2. Name: Sev-B / Grance Period: 4 / Schedule: 24/7
3. Name: Sev-C / Grace Period: 8 / Schedule: Monday-Friday (Business hours)  
</p>
<br />

<p>
<img src="https://i.imgur.com/IydwP2C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/t2Q70wY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/uIsOYev.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/aCVwbjt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Creating Help Topics:

- Under the "Manage" tab, click "Help Topics" and then "Add New Help Topic".
- Create four help topics according to the provided list.
- Name the topics accordingly and click "Add Topic".
1. Business Critical Outage
2. Personal Computer Issues
3. Equipment Request
4. Password Reset
</p>
<br />

<p>
<img src="https://i.imgur.com/5ktAj9r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9. Completion:

- With the Help Topics created, the configuration of osTicket is complete.
- Testing can now commence to evaluate user ticket submission and employee ticket resolution processes.
</p>
<br />
