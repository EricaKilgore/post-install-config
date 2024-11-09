<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial outlines the post-configuration setup of the osTicket system.

<br />

<p>

</p>
</p>
<p>
We have successfully configured osTicket from scratch. Now, we will focus on system administration and perform some post-installation setup.

First, we will configure new roles within the help desk: To do this, navigate to Admin Panel > Agents > Roles. Click "Add New Role" and enter the name of the new role. You can also modify specific role permissions. In this case, as we are creating a "Supreme Admin," we will assign all permissions to this role. It is important to note that roles define an agent's permissions, so not all agents will have unrestricted access. 

If you followed the steps correctly, your screen should resemble the example shown, where the "Supreme Admin" role has been successfully created.
</p>

<img width="713" alt="image" src="https://github.com/user-attachments/assets/f2125f54-20ee-4a02-8f02-500240d68b0e">


</p>
<br />
<p>
</p>
<p>
Navigate to the Agents tab and select the "Departments" button. In this section, you can create new departments, with each agent being assigned to a specific department based on their role within the helpdesk.  <br>
  
For this tutorial, we will create the  four departments <br>
- System Administrators
- Payroll
- Support
- Leave of Absence
- Human Resouces 
  
Company ticketing systems are generally organized into departments such as System Administration, Payroll, Support, Leave of Absence, and Human Resources. This structure ensures that tickets are efficiently routed to the appropriate teams, promoting faster resolutions, streamlined SLA management, and accountability by allowing each department to handle requests relevant to their specialized roles and protocols.

</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department we will set up new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. 
  
For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team. 

  
</p>
<br />
<p>
<img src="https://i.imgur.com/cYzWBD2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.

</p>
<br />
<img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab. 
</p>
<br />
<img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 
</p>
<br />
<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
