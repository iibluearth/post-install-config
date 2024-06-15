# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install of the open-source help desk ticketing system osTicket.<br />

<h2>Video Demonstration</h2>

 ### [YouTube: How To Configure osTicket, Post-Installation](https://www.youtube.com)

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
<img src="https://i.imgur.com/hlfPQ0A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Configuring Supreme Admin Role:

- Navigate to http://localhost/osTicket/scp/login.php through your browser.
- Log in using the osTicket account credentials (User: john / Password: Labpassword1).
- After logging in, click "Admin Panel" in the top right corner.
</p>
<br />

<p>
<img src="https://i.imgur.com/mNBJy3y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/Rm4bvCM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/mHmCpFY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/QuAXRWz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/waRYQhP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Adding System Administrators Department:

- Under the "Agents" tab, click "Departments".
- Choose "Add New Department".
- Name the department "System Administrators" and click "Create Dept".
</p>
<br />

<p>
<img src="https://i.imgur.com/Wg2PaDY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Setting Up Level II Support Team:

- Again under the "Agents" tab, click on "Teams" and then "Add New Team".
- Name this team "Level II Support" and add "John" as a member.
- Click "Create Team" when finished.
</p>
<br />

<p>
<img src="https://i.imgur.com/dQXcfIX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/YmQLnvO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/F2TB4cq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/DoUHAOy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/O7BrnZF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
- Name: Jane Doe / Email Address: jane.doe@osticket.com / Username: jane.doe / Password: Password1
- Name: John Doe / Email Address: john.doe@osticket.com / Username: john.doe / Password: Password1
</p>
<br />

<p>
<img src="https://i.imgur.com/1b5niGd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/m7GLfb9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Creating Users/Customers:

- In the "Agent Panel", under the "Users" tab, select "Add User".
- Create simple users named "Karen" and "Ken" with basic email addresses.
- Click "Add User" to finish.
- Karen / karen@osticket.com
- Ken / ken@osticket.com
</p>
<br />

<p>
<img src="https://i.imgur.com/CUvVjWr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/txZdq5h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/qPgIX3w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/5PuhaVv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/EYeVQ1t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/KDgPF92.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/8MZBNqd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/va0fzci.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/Pbndfcf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9. Completion:

- With the Help Topics created, the configuration of osTicket is complete.
- Testing can now commence to evaluate user ticket submission and employee ticket resolution processes.
</p>
<br />
