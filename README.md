<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Life Cycle</h1>
This tutorial outlines the configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Configuration requirements</h2>

- Internet Connection
- RDP(Remote Desktop Connection)
- VM (Vitual Machine)
- osTicket Installed

<h2>Configuration Steps</h2>

<p>This is the installation portion of the osTicket Lab. If you missed the previous steps here is the <a href="https://github.com/DevilDog2001/post-install-config/blob/main/README.md">Link.</a></p>
<p>
<img src="https://i.imgur.com/xc4u9sF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Welcome to the configuration portion of the osTicket Lab. To start off this portion we will click on staff link on the right hand side and see this page appear. Login to the credentials created for the user_admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/3RdJRJl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we are logged into the account make sure that we are in the admin panel. From the admin panel we will head to the <strong>Agents tab --> then select Roles --> and add a new role.</strong> Next name the role whatever you like for the Lab, after head over to the permissions and give that role all the permissions from Ticket Tasks and Knowledgebase. After that save changes and see the role appear within the roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/H6r3Jz1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we finish creating are new role we will head over to create a new department. From the same agents tab select <strong>Departments --> then add Department</strong>, from there name the department whatever you would like for the lab. After creating a name select create Dept and leave everything defualt. You should see the new Department within the Department list
</p>
<br />
<img src="https://i.imgur.com/JWnS4pc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we finish creating are new Department we will head over to create a new Team. From the same agents tab select <strong>Teams --> then add Team</strong>, from there name the Team whatever you may like for the Lab. After go over to Members and add your created user to the team, once added create the team.
</p>
<br />
<p>
<img src="https://i.imgur.com/m4ufuUM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we want to head over to settings Tab to allow any user to create tickets. Having the setting like so will allow users to create tickets without logging on.
</p>
<br />
<p>
<img src="https://i.imgur.com/l6gf9jk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After setting the user's, move on over to the Agents Tab and select to add a new agent. Create 2 agents as shown above. repeat that same step for the second agent and then move on to giving the agent a Primary Department, permissions, and a team.
</p>
<br />
<p>
<img src="https://i.imgur.com/Md4ZLyA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we have created are agents, we will switch over to the agents panel. From the agents panel we will create 2 new users as shown above. To get over we will select <strong>Agent panel on the top right --> Then select Users --> and once we are inside we select create user.</strong>
</p>
<br />
<p>
<img src="https://i.imgur.com/MJg4MRI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now after creating are users we can head over back to the admin panel to create are SLA's. Once we are in the admin panel and have selected SLA, select create SLA. From there we will create the 3 following SLA'S <strong>SEV-A(1 hour.24/7),SEV-B(8 hour.24/7),SEV-C(8 hour,Business hours)</strong> 
</p>
<br />
<p>
<img src="https://i.imgur.com/K7weuRP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating the 3 SLA's we will now navigate over to the Help Topics. There we will add 4 new Help Topics. Those 4 new Help Topics are <strong>Business Critical Outage, Personal Computer Issues, Equipment Request and Password Reset.</strong> Above shows the page in where we will enter the information.
</p>
<br />
<p>
<img src="https://i.imgur.com/emfAIp4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now after adding those new Help Topics, lets logout of the Staff osTicket and log into the user page. The user page will allow us to create Tickets to send over to are Staff, here's the link to copy down and paste on your browser to enter the user page shown above. <strong>(http://localhost/osTicket/index.php)</strong>
</p>
<br />
<p>
This will conclude the Configurations for the osTicket Lab. The next section we will begin to use osTicket and begin with Ticket Lifecycle. Next section <a href='https://github.com/DevilDog2001/ticket-lifecycle'>Ticket Lifecycle</a> .
</p>
