# Post-Install-Config
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

<p>
  <img width="612" height="286" alt="image" src="https://github.com/user-attachments/assets/1a3447d1-2532-4d79-a12d-3101796da8c9" /><img width="397" height="477" alt="image" src="https://github.com/user-attachments/assets/795f92b0-3d5d-4b3a-a9c6-8a33fb137f59" />
</p>
<p>
Roles in osTicket define the permissions granted to Agents within specific Departments. They are a critical part of access control, ensuring that agents only have the ability to perform actions that align with their responsibilities.
  
  Role Permissions for Tickets include:

- Assign: Ability to assign tickets to agents or team

- Close: Ability to close tickets

- Create: Ability to open tickets on behalf of users

- Delete: Ability to delete tickets

- Edit: Ability to edit tickets

- Edit Thread: Ability to edit thread items of other agents

- Link: Ability to link tickets

- Mark as Answered: Ability to mark a ticket as Answered/Unanswered

- Merge: Ability to merge tickets

- Post Reply: Ability to post a ticket reply

- Refer: Ability to manage ticket referrals

- Release: Ability to release ticket assignment

- Transfer Ability to transfer tickets between departments
</p>
<br />

<p>
  <img width="608" height="427" alt="image" src="https://github.com/user-attachments/assets/5e567249-2793-432d-ab00-672fa29a06bd" /><img width="317" height="326" alt="image" src="https://github.com/user-attachments/assets/27caf4f7-7942-42e0-9e94-84b2504f2ec5" />
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
 <img width="607" height="366" alt="image" src="https://github.com/user-attachments/assets/df77e73b-bec3-425b-b03f-60dd9a345936" />
 <img width="408" height="297" alt="image" src="https://github.com/user-attachments/assets/17d053d5-32d4-417b-8698-e41fb96cdae5" /><img width="424" height="260" alt="image" src="https://github.com/user-attachments/assets/e8c0293a-9e60-42b0-8c75-f0e4a7dbb1a7" /><img width="556" height="184" alt="image" src="https://github.com/user-attachments/assets/4ed65013-fd98-4a94-964f-d887b0075d4e" />
</p>
<p>
Agents are staff users who are granted access to the osTicket help desk system to view, respond to, and resolve tickets. Their access and capabilities are defined by the departments they belong to and the roles assigned to them, with the flexibility to assign extended access across multiple departments. Administrators can manage their credentials, including secure password resets, directly from the admin panel.
</p>
<br />

<p>
<img width="324" height="273" alt="image" src="https://github.com/user-attachments/assets/d4b15f25-b892-44bd-8b70-92e1e5ba658c" />
<p>
In osTicket, a User is the ticket requester or owner—typically a customer, client, or end-user seeking help. Users create tickets through the client portal, email, or phone, and are identified in the system primarily by their email address. They can track, and reply to tickets, while agents can organize users into Organizations, assign Account Managers, and manage ticket history via the User Directory.
</p>
<br />

<p>
<img width="392" height="291" alt="image" src="https://github.com/user-attachments/assets/2c197d89-22c6-479a-a8a2-0e91684d89a9" /> <img width="367" height="278" alt="image" src="https://github.com/user-attachments/assets/0b3e02af-0694-4ad7-a5eb-51e527e2b3b1" />
<img width="385" height="273" alt="image" src="https://github.com/user-attachments/assets/1357d4f1-c72b-44a9-8909-c75370f32eed" />

</p>
<p>
SLA Plans (Service Level Agreements) in osTicket define the expected timeframe for ticket resolution. They help ensure accountability and timely responses by applying specific deadlines to tickets based on departments, help topics, or filters. With flexible assignment through Departments, Help Topics, Filters, and manual overrides, osTicket offers a powerful way to manage ticket deadlines and prioritize support efficiently.
</p>
<br />

<p>  
<img width="375" height="299" alt="image" src="https://github.com/user-attachments/assets/056e94ce-5348-477f-b16a-c6ac183618d4" /> <img width="388" height="267" alt="image" src="https://github.com/user-attachments/assets/61e330ab-e18f-444b-ba22-19a4af50adf0" />
<img width="384" height="268" alt="image" src="https://github.com/user-attachments/assets/9947fa0c-9c99-48f9-9ad6-64053a9dc554" /> <img width="389" height="270" alt="image" src="https://github.com/user-attachments/assets/9ef2ef06-55e3-4f24-9ef9-6694a962db65" />
<img width="384" height="267" alt="image" src="https://github.com/user-attachments/assets/766db84c-e83f-4c3c-8878-096995f5f46e" />
</p>
<p>
Help Topics are customizable categories that allow you to guide users to the correct department and ensure tickets are handled efficiently. Help Topics in osTicket streamline ticket assignment and automate support workflows by linking each ticket to a Department, SLA Plan, and Priority level. Though invisible to the user, they play a critical role in ensuring tickets are handled by the right team, at the right speed.
</p>
<br />
