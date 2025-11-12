<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Ticketing System Lab</h1>

### Overview
This project demonstrates how IT support teams use osTicket to manage, assign, and resolve user-submitted issues. The lab simulates realistic help desk workflows, where end-users create support tickets and agents handle them using appropriate SLA levels, departments, and priorities.  
By completing this lab, I gained practical experience in ticket lifecycle management, SLA configuration, and user role workflows, all of which are key skills for help desk and IT support roles.

---

### Technologies Used
- Microsoft Azure (Virtual Machines)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)
- osTicket (Web-Based Help Desk System)
- Windows 10 (21H2)

---

### Skills Demonstrated
- Ticket creation, triage, and resolution  
- SLA plan configuration and prioritization  
- Department and agent assignment  
- Role-based access and workflow management  
- Communication and documentation in IT support  

---

### Objectives
- Create tickets as end-users  
- View and manage tickets as help desk agents  
- Modify ticket properties (SLA, Department, Priority)  
- Resolve incidents and document resolutions  
- Observe permissions and visibility differences between user roles  

---

### Key Steps and Scenarios

#### Scenario 1: Online Banking System Outage
- Created a ticket reporting that the entire mobile online banking system was down.  
- Selected Report Problem as the help topic to simulate a common user mistake (instead of Business Critical Outage).  
- As the help desk agent John, I updated the SLA to Sev-A (24/7) due to the outage’s critical impact, changed the help topic, and assigned the issue to the Online Banking Team.  
- Logged in as Jane, a member of the Online Banking Team, and took ownership of the ticket.  
- Posted updates identifying a faulty software update as the root cause, rolled it back, and resolved the ticket.

<p align="center">
  <img width="759" height="948" src="https://github.com/user-attachments/assets/49de5175-5723-4264-ac9b-e0c8e94a1576" alt="End user creating ticket"/>
  <br>
  <em>End-user creating a ticket for a system-wide outage</em>
</p>

<p align="center">
  <img width="766" height="943" src="https://github.com/user-attachments/assets/2e5dc947-ea29-4b67-a9bb-69754f255d78" alt="Viewing ticket as help desk agent"/>
  <br>
  <em>Help desk agent viewing and updating ticket details</em>
</p>

<p align="center">
  <img width="767" height="924" src="https://github.com/user-attachments/assets/d3d4fa90-37ed-4c5e-8f99-47678b8d9548" alt="Adjusting SLA and help topic"/>
  <br>
  <em>Adjusting SLA and assigning to Online Banking Team</em>
</p>

<p align="center">
  <img width="766" height="952" src="https://github.com/user-attachments/assets/d465f0ca-ce79-467b-98da-74f654e62ace" alt="Ticket assigned to Jane"/>
  <br>
  <em>Ticket assigned to Jane for resolution</em>
</p>

<p align="center">
  <img width="759" height="229" src="https://github.com/user-attachments/assets/709169f3-cf10-464b-9ade-f9be24775a94" alt="Resolution update"/>
  <br>
  <em>Resolution update posted and ticket marked as resolved</em>
</p>

---

#### Scenario 2: Adobe Software Issue (Accounting Department)
- Created a new ticket reporting that several users in Accounting could not open Adobe Reader.  
- As the help desk agent John, assigned the ticket to myself and set the SLA to Sev-C, since the issue affected only two users.  
- Documented troubleshooting (a restart fixed the issue) and resolved the ticket.

<p align="center">
  <img width="760" height="943" src="https://github.com/user-attachments/assets/e0eb4d7b-7d83-4111-b7fd-b362c0915e01" alt="New Adobe issue ticket"/>
  <br>
  <em>End-user creating Adobe Reader support ticket</em>
</p>

<p align="center">
  <img width="764" height="911" src="https://github.com/user-attachments/assets/a2f0b9da-9929-4f92-8906-27d889e57bea" alt="Agent reviewing Adobe issue"/>
  <br>
  <em>Help desk agent reviewing and updating ticket details</em>
</p>

<p align="center">
  <img width="1512" height="956" src="https://github.com/user-attachments/assets/6c18b9fe-2dbc-4ae5-b7c2-18896fa42506" alt="Ticket resolved after fix"/>
  <br>
  <em>Issue resolved and documented within osTicket</em>
</p>

---

#### Scenario 3: CFO Laptop Issue
- Created a ticket stating that the CFO’s laptop would not charge.  
- As John, changed the SLA to Sev-B and set the priority to Emergency due to executive-level impact.  
- Determined the charger was defective, replaced it, documented the resolution, and marked the ticket as resolved.

<p align="center">
  <img width="1506" height="958" src="https://github.com/user-attachments/assets/338d7ad1-7051-4740-a2ac-b7dbe7e25269" alt="CFO laptop issue ticke
