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
- Human Resources 
  
Company ticketing systems are generally organized into departments such as System Administration, Payroll, Support, Leave of Absence, and Human Resources. This structure ensures that tickets are efficiently routed to the appropriate teams, promoting faster resolutions, streamlined SLA management, and accountability by allowing each department to handle requests relevant to their specialized roles and protocols.

</p>
<p>
<img width="710" alt="image" src="https://github.com/user-attachments/assets/020fa493-7d26-4c14-a528-ac20bd1cf125">

</p>
<br />

<p>
Once a new department is configured, the next step is to establish a specialized team. Teams enable cross-departmental collaboration by assembling agents from various departments, allowing for the creation of high-performing groups with top technicians from specific areas.

For instance, a representative from Human Resources could be granted access to Payroll and Leave of Absence functions, empowering them to work on and resolve relevant tickets. This structure enhances operational flexibility and ensures that high-priority tickets are managed by the most qualified personnel. 

  
</p>
<br />
<p>
<img width="720" alt="image" src="https://github.com/user-attachments/assets/1af8d5e3-703c-4255-8d14-f495335a4c61">
</p>
<p>

With the new team established, the next step is to configure a setting that enables all users to create tickets. Navigate to Admin Panel > Settings > User Settings to apply this configuration.

</p>
<br />
<img width="701" alt="image" src="https://github.com/user-attachments/assets/cd7f2a6c-f54e-4bb8-ae65-afdbd174e465">

</p>

<p>
The next step is to create Agents. Below is a list of agents already created, followed by images detailing the steps to assign agents to specific departments and set their levels of access.

<img width="720" alt="image" src="https://github.com/user-attachments/assets/00699565-e695-4fec-b0b3-2e4be852c047">

</p>
<b> STEP 1 </b> ADMIN PANEL -> AGNENTS -> ANGENTS -> ADD NEW AGENT
<img width="704" alt="image" src="https://github.com/user-attachments/assets/da18c6e8-39ac-4e88-94c1-48f85b7402b8">

<b> STEP 2 </b> Fill out user information
<img width="511" alt="image" src="https://github.com/user-attachments/assets/0a254ac5-3fae-40d4-9844-a0ccf3d5580e">


<b> STEP 3 </b> Assign the agent’s designated department and access level; additional access privileges can be configured as necessary.

<img width="604" alt="image" src="https://github.com/user-attachments/assets/7852e90d-d36d-4d19-9977-a07a971c9881">


<b> STEP 4 </b> Assigning Permissions
<img width="338" alt="image" src="https://github.com/user-attachments/assets/9a4d21a3-b0b9-4f51-9ca8-d0acc8c03a53">

<b> STEP 5 </b> Team assignments can be configured here and updated from the Teams tab when adding multiple agents simultaneously.

<img width="490" alt="image" src="https://github.com/user-attachments/assets/98b0955f-4d1f-433f-b1bd-a93381306f63">




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
