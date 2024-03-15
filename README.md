# osTicketPostConfig

<p align="center">
<img src= "https://github.com/josemiguel-nunez/osticket-prereqs/assets/163205170/8fef7bdb-1d4e-49c6-a3df-5568bb1db650" height="80%" width="80%" />

</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system .<br />

<p>

</p>
</p>
<p>
Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup.
first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. 
Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.
</p>
<img src= "https://github.com/josemiguel-nunez/osTicketPostConfig/assets/163205170/c00b030b-7326-4339-adf1-0006639aa64d" height="80%" width="80%" />

</p>
<br />
<p>
</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab. 
</p>
<br />
<p>
  <img src= "https://github.com/josemiguel-nunez/osTicketPostConfig/assets/163205170/f0c9d641-2fea-4b41-ba5b-3781eb86cf0c" height="80%" width="80%" />

</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team. 
</p>
<br />
<p>
  <img src="https://github.com/josemiguel-nunez/osTicketPostConfig/assets/163205170/6bd9051a-4bd2-4b20-a80f-e4da24659d86" height="80%" width="80%"

</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.

</p>
<br />
<img src="https://github.com/josemiguel-nunez/osTicketPostConfig/assets/163205170/6c4bebd8-3ac2-4044-a295-c9eb6d4f645d" height="80%" width="80%" />
/>
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab. 
</p>
<br />
<img src="https://github.com/josemiguel-nunez/osTicketPostConfig/assets/163205170/d8744453-960d-42a4-9c05-05624973e7bc" height="80%" width="80%" />
"/>
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<img src="https://github.com/josemiguel-nunez/osTicketPostConfig/assets/163205170/8f7d28ca-ff9e-4f9a-bb59-ddab98ae65a5" height="80%" width="80%" />
/>
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<img src="https://github.com/josemiguel-nunez/osTicketPostConfig/assets/163205170/96063298-4c3b-44e2-a26d-8867c217b836" height="80%" width="80%" />
"/>
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 
</p>
<br />
<img src="https://github.com/josemiguel-nunez/osTicketPostConfig/assets/163205170/1bd8446c-6e28-4598-b621-3e3ba297f3d0" height="80%" width="80%" />

</p>
<p>
