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

- Configure Roles and Departments 
- Configure Teams and allow anyone to create ticekts 
- Now we will configure agents/workers and user/customers 
- Configure SLA
- Configure Help Topics 

<h2>Configuration Steps</h2>

<p>
<a href="https://imgur.com/pxmkcgp"><img src="https://i.imgur.com/pxmkcgp.png" title="source: imgur.com" /></a>
<p>
In this first part of post installition for osTicket, we will create a role called Supreme Admin. To essentially give out "agents" access to everything. Tickets circualte through departments in help desk so we will create one for this project as well. 
</p>
<br />
<p>
<a href="https://imgur.com/W1GjZfR"><img src="https://i.imgur.com/W1GjZfR.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/cZbDjBj"><img src="https://i.imgur.com/cZbDjBj.png" title="source: imgur.com" /></a>
 
Creating our teams, allows you to pull agents from differnt departments into one team which is demonstrated above. To create said team you will select admin panel, locate the agents tab and click on teams then add new team and fill out information. Adding agents to the team and checking corresponding box next to the team name. Then allow anyone to create tickets through setting, user settings fill out registration and login back in to create tickets. 
</p>
<br/>
<a href="https://imgur.com/6ypubdo"><img src="https://i.imgur.com/6ypubdo.png" title="source: imgur.com" /></a> 
<a href="https://imgur.com/2a3CIEX"><img src="https://i.imgur.com/2a3CIEX.png" title="source: imgur.com" /></a>
</p>
<p>
In this step we will add agents. I created the user(essentially our workers)  Jane and john Doe for the activity. Through again the admin panels and under agents to add new agents. With the creation of user through the agent panel you can add the user to an organzistion of the help desk 
</p>
<br />
<a href="https://imgur.com/GuShSWi"><img src="https://i.imgur.com/GuShSWi.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/IJprHbS"><img src="https://i.imgur.com/IJprHbS.png" title="source: imgur.com" /></a>
</p>
<p>
SLA Plans are placed to provide a lenght of time in which Admin expects tickets to tbe closed. They can be creatd by the admin panel, manage, SLA Plans adding a new SLA plan. Finally we will configure Help topics, creating topics such as Business Criical Outage, Personal Computer Issues, Equipment Request, and Password Reset to be used in the next project set. 
 Now you're finish!
</p>
<br/>
