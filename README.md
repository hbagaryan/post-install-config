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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/hYJTODO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured role-based permissions within osTicket to enhance security and access management. Navigated to the Admin Panel → Agents → Roles and created custom roles to define specific access levels for agents. Assigned the Supreme Admin role to users requiring full administrative control over the system. Successfully implemented role-based access control (RBAC) to ensure secure and efficient user management within the help desk system.
</p>
<br />

<p>
<img src="https://i.imgur.com/A6trr4w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured department-based ticket visibility in osTicket to streamline workflow and enhance access control. Navigated to Admin Panel → Agents → Departments and created structured departments to categorize support requests efficiently. Assigned the SysAdmins department to handle system administration-related tickets, ensuring appropriate ticket routing and visibility. Successfully implemented a departmental structure to improve help desk efficiency and enforce role-based ticket access.
</p>
<br />

<p>
<img src="https://i.imgur.com/V4lbF3m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured teams in osTicket to facilitate collaboration across multiple departments. Navigated to Admin Panel → Agents → Teams and created a structured team to pull agents from different departments for specialized support. Assigned agents to the Online Banking team to ensure efficient handling of banking-related inquiries and technical issues. Successfully implemented a team-based support structure, enhancing workflow efficiency and cross-departmental coordination within the help desk system.
</p>
<br />

<p>
<img src="https://i.imgur.com/ec0Hxh1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured user access settings in osTicket to manage ticket submission requirements. Navigated to Admin Panel → Settings → User Settings and adjusted permissions to restrict unregistered users from creating tickets by unchecking the "Unregistered users can create tickets" option. Enabled "Registration Required", ensuring that only registered users with login credentials can submit support requests. Successfully implemented ticket access control, enhancing security and maintaining an organized help desk system.
</p>
<br />

<p>
<img src="https://i.imgur.com/YWupzkQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured agents in osTicket to establish a structured support team. Navigated to Admin Panel → Agents → Add New and onboarded new agents with specific departmental roles. Assigned Jane to the SysAdmins department to manage system administration tasks and John to the Support department for general customer assistance. Successfully implemented a departmental agent structure, ensuring efficient ticket routing and role-based access control within the help desk system.
</p>
<br />

<p>
<img src="https://i.imgur.com/D1Dpat4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured users in osTicket to manage customer support requests effectively. Navigated to Agent Panel → Users → Add New and registered new users in the system. Added Karen and Ken as customers, enabling them to submit and track support tickets. Successfully implemented a user management system, ensuring seamless customer interaction and ticket resolution within the help desk platform.
</p>
<br />

<p>
<img src="https://i.imgur.com/YBqg50p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured Service Level Agreements (SLAs) in osTicket to ensure timely ticket resolution. Navigated to Admin Panel → Manage → SLA and created SLA policies based on ticket severity. Defined Sev-A with a 1-hour grace period and a 24/7 schedule, Sev-B with a 4-hour grace period and a 24/7 schedule, and Sev-C with an 8-hour grace period restricted to business hours. Successfully implemented an SLA framework, optimizing response times and prioritizing ticket resolution based on urgency.
</p>
<br />

<p>
<img src="https://i.imgur.com/MmWnN7g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured Help Topics in osTicket to categorize and streamline user ticket submissions. Navigated to Admin Panel → Manage → Help Topics and created predefined topics for user inquiries. Added Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other to ensure efficient ticket routing and resolution. Successfully implemented a help topic structure, improving user experience and support team workflow.
</p>
<br />
