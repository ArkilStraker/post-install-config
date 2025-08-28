# post-install-config
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

- Windows 11 Pro</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p><img width="612" height="286" alt="image" src="https://github.com/user-attachments/assets/1a3447d1-2532-4d79-a12d-3101796da8c9" /><img width="397" height="477" alt="image" src="https://github.com/user-attachments/assets/795f92b0-3d5d-4b3a-a9c6-8a33fb137f59" />


</p>
<p>
Roles in osTicket define the permissions granted to Agents within specific Departments. They are a critical part of access control, ensuring that agents only have the ability to perform actions that align with their responsibilities.
  
  Role Permissions for Tickets include:

Assign: Ability to assign tickets to agents or team

Close: Ability to close tickets

Create: Ability to open tickets on behalf of users

Delete: Ability to delete tickets

Edit: Ability to edit tickets

Edit Thread: Ability to edit thread items of other agents

Link: Ability to link tickets

Mark as Answered: Ability to mark a ticket as Answered/Unanswered

Merge: Ability to merge tickets

Post Reply: Ability to post a ticket reply

Refer: Ability to manage ticket referrals

Release: Ability to release ticket assignment

Transfer Ability to transfer tickets between departments
</p>
<br />

<p><img width="608" height="427" alt="image" src="https://github.com/user-attachments/assets/5e567249-2793-432d-ab00-672fa29a06bd" /><img width="317" height="326" alt="image" src="https://github.com/user-attachments/assets/27caf4f7-7942-42e0-9e94-84b2504f2ec5" />


</p>
<p>
In osTicket, Departments serve as the primary channels for ticket routing and agent assignment. Because tickets flow through specific departments (like IT, HR, or Customer Service), each department can be configured with its own unique settings to support its workflow. Because tickets are routed through Departments in osTicket, configuring each department with its own settings ensures the help desk can adapt to different support areas. This allows each team to operate independently while maintaining consistency and efficiency across the help desk system.
</p>
<br />

<p>
<img width="609" height="316" alt="image" src="https://github.com/user-attachments/assets/ff39c403-c44e-4766-bb07-697a853f9314" /><img width="295" height="222" alt="image" src="https://github.com/user-attachments/assets/5738e7b4-dab9-459e-a64b-3defde90b515" />


</p>
<p>
Teams in osTicket allow administrators to group agents from multiple departments into a single unit that can handle specific tickets, topics, or user groups—regardless of their individual department assignments. Suppose you have Agents in both the Billing and Technical Support departments who specialize in a product called X-Pro. You can create a Team called "X-Pro Specialists" and assign tickets from the "X-Pro Help Topic" to this Team. Even though the agents belong to different departments, they will receive and manage those tickets collaboratively.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
