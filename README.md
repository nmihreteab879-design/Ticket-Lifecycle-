<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticketing Lab: Creating and Managing Tickets</h1>
This tutorial outlines the creation, observation, and resolution of tickets in osTicket, simulating both end-user and help desk agent workflows.<br />

<h2>Video Demonstration</h2>
- ### [YouTube: How To Manage osTicket Tickets](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>
- Windows 10 (21H2)

<h2>Lab Objectives</h2>
- Create tickets as end-users
- Observe ticket properties as help desk agents
- Modify ticket properties (SLA, Department, Assigned To)
- Complete tickets
- Observe ticket visibility and permissions
- Understand real-world ticket intake processes

<h2>Configuration Steps</h2>

<p>
<img src="REPLACE_WITH_ADMIN_LOGIN_IMAGE_URL" height="80%" width="80%" alt="Admin Login Page"/>
</p>
<p>
<b>Step 1:</b> Admin/Analyst Login Page: <br>
URL: http://localhost/osTicket/scp/login.php
</p>
<br />

<p>
<img src="REPLACE_WITH_ENDUSER_PORTAL_IMAGE_URL" height="80%" width="80%" alt="End User Portal"/>
</p>
<p>
<b>Step 2:</b> End Users osTicket URL: <br>
URL: http://localhost/osTicket
</p>
<br />

<p>
<img src="REPLACE_WITH_DEPARTMENT_IMAGE_URL" height="80%" width="80%" alt="Department Configuration"/>
</p>
<p>
<b>Step 3:</b> Department Configuration <br>
- Change the SysAdmins Department to a Top-Level Department <br>
- DELETE the Maintenance Department (do not archive)
</p>
<br />

<p>
<img src="REPLACE_WITH_TICKET1_IMAGE_URL" height="80%" width="80%" alt="Ticket 1 Creation"/>
</p>
<p>
<b>Step 4:</b> End User Ticket Creation <br>
Ticket Title: Entire mobile/online banking system is down
</p>
<br />

<p>
<img src="REPLACE_WITH_TICKET1_OBSERVE_IMAGE_URL" height="80%" width="80%" alt="Ticket 1 Observation"/>
</p>
<p>
<b>Step 5:</b> Observe Ticket Properties (Agent John) <br>
- Priority <br>
- Department <br>
- SLA <br>
- Assigned To
</p>
<br />

<p>
<b>Step 6:</b> Set Ticket Properties <br>
- SLA: Sev-A (1 hour, 24/7) <br>
- Department: Online Banking
</p>
<br />

<p>
<b>Step 7:</b> Attempt to Access Ticket as John <br>
Observe whether the ticket can be viewed or modified.
</p>
<br />

<p>
<b>Step 8:</b> Work Ticket to Completion <br>
Assign and complete ticket as Jane
</p>
<br />

<p>
<img src="REPLACE_WITH_TICKET2_IMAGE_URL" height="80%" width="80%" alt="Ticket 2 Creation"/>
</p>
<p>
<b>Step 9:</b> Create Second Ticket (End User) <br>
Ticket Title: Accounting department needs Adobe upgrade, broken
</p>
<br />

<p>
<b>Step 10:</b> Observe and Set Properties (Agent John) <br>
- SLA: Sev-B (4 hours, 24/7) <br>
- Department: Support <br>
Work ticket to completion as John
</p>
<br />

<p>
<img src="REPLACE_WITH_TICKET3_IMAGE_URL" height="80%" width="80%" alt="Ticket 3 Creation"/>
</p>
<p>
<b>Step 11:</b> Create Third Ticket (End User) <br>
Ticket Title: CFO’s laptop will no longer turn on
</p>
<br />

<p>
<b>Step 12:</b> Observe and Set Properties (Agent John) <br>
- SLA: Sev-B (4 hours, 24/7) <br>
- Department: Support <br>
Work ticket to completion as John
</p>
<br />

<p>
<b>Step 13:</b> Escalate and Observe Tickets <br>
- Set properties to all tickets: SEV-A for SysAdmins last <br>
- Observe ticket becomes inaccessible <br>
- Switch to Admin Panel and assign View-access for SysAdmins <br>
- Switch back to Agent Panel and observe escalated ticket <br>
- Confirm that changes cannot be made
</p>
<br />

<p>
<b>Step 14:</b> Solve All Tickets <br>
Complete resolution of all tickets.
</p>
<br />

<p>
<b>Step 15:</b> Real-World Ticketing Explanation <br>
- Email notifications are sent for every ticket update <br>
- Users can respond to ticket updates via email <br>
- Tickets can be created through phone, chat, email, web form, or in-person <br>
- Even quick fixes should be recorded as tickets for metrics and reporting purposes
</p>

