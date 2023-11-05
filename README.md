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

- Setting up Roles, Departments, and Teams
- Giving end users the ability to create tickets 
- Configuring Agents, Users, and SLAs

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Start by heading to "http://localhost/osTicket/scp/login.php." From there, log into osTicket using the credentials you created during installation. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to the "Admin Panel", then head to "Agents", and click on "Roles." Make a new role named "Supreme Admin."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, head back to the "Admin Panel", then make your way to "Agents" and select "Departments." Create a new department named "System Administrators."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, head back to the "Admin Panel" again, then head to "Agents" and then "Teams" after.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once done setting up teams, head to "Settings" (under "Admin Panel"), then hit "User Settings." Hit the check box next to "Require registration and login to create tickets." This will allow end users to create tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This next step will be a demonstration on how to add "agents" (employees who receive and work on tickets submitted by end users). Head to the "Admin Panel", click on "Agents", then select "Add New." Create two agents named "Jane" and "John" (this is for demonstrative purposes only, you have the ability to create as many agents and name them as you see fit).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will create some end users and give them the ability to submit tickets. Head to the "Agent Panel", go to "Users", then hit "Add New". Make two user accounts and name them "Karen" and "Ken."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After making the end user accounts, we can begin working on the SLA (Service Level Agreement). Start by heading to "Admin Panel", then click on "Manage", then select "SLA." Make three SLA plans as follows: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

