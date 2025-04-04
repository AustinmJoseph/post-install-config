<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the how to configure osTicket and go over a few terms we might see in the work force.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

Now that we have installed and got the the admin panel let configure it. 

If you havent installed osTicket please refer to my [osTicket installation Lab](https://github.com/AustinmJoseph/ostiket-prereqs).

Lets fogin into the admin panel with our admin account first. 

When you first log in click the admin panel you can see that alot more things pop up. 

To start off we are going to make a few roles that give different levels of acces to different groups, groups give permisions to different people within the group.

we are going to make a group called system admins and give them all permissions.

now we will go to the departments panel and make one called sys admins.

now switch to teams we are going to name this one Shield and create. Teams pull agents from different departmants to the same team.

For this lab we want anyone to be able to registar tickets so go to settings > Users > and make sure the box is unchecked.

now we will make some workers/agents. Go to agents  and click agents, then make a random email make sure to record this information I named my first agent Gwen Stacy, i gave gwen the superior adnmin role access and and put her on team Shield.
Then I made another agent named Harry Osborn and only gave him  the support role and view access for this lab. 

Now that we have made agents we can make a USer.

go to the top right and click gent panel, then go to users and create a new user i name mine Norman osborn. we will only make a single user for now.

now we are going to g back into the admin panel to configure SLA's, SLA's give the agent a notice on how quickly a ticket should be handled.

we are going to create 3 SLA's

SEV-A - really nad
SEV-B - not as bad
SEV-C - not terrible

now we are going to make Help topics. Help Topics help users create tickets/ gives users a direction when creating one. Go to manage >Help Topics > and create a new help topic. I made 4 help topics Personal Computer with report a problem, Equipment request with General inquiry,

This Lab is a prequisit to my next lab to practice using the ticketing system.




