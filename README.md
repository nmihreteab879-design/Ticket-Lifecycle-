OSTICKETING LAB PROJECT
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

 I opened the end-user osTicket URL and selected Open a New Ticket. I entered a fake name, fake email, and phone number. The ticket I created was about the entire mobile online banking system being down. The correct help topic for this situation should be Business Critical Outage, but many end users choose more general options, so for the sake of the lab I selected Report Problem. After filling out the information, I clicked Create Ticket. 
 
 <img width="759" height="948" alt="image" src="https://github.com/user-attachments/assets/49de5175-5723-4264-ac9b-e0c8e94a1576" />

I then logged in as John, which is a user I previously created. I opened the online banking system ticket to view the ticket details. I changed the SLA plan to Sev-A 24/7 schedule because the problem had a wide impact, due to customers not being able to do online banking. Then I changed the help topic to report problem/buisness crtical outage because no customer is able to acess online banking . I assigned the problem to online banking team and the description I used was customers cant acess the online banking portal.

   <img width="766" height="943" alt="image" src="https://github.com/user-attachments/assets/2e5dc947-ea29-4b67-a9bb-69754f255d78" />
   
   <img width="767" height="924" alt="image" src="https://github.com/user-attachments/assets/d3d4fa90-37ed-4c5e-8f99-47678b8d9548" />


I logged in as Jane, a member of the online banking team, and navigated directly to the ticket to begin the resolution process. I then officially assigned the ticket to myself to take full ownership of the outage. This step ensures the rest of the team knows the issue is being actively investigated by a specific agent.

 <img width="766" height="952" alt="image" src="https://github.com/user-attachments/assets/d465f0ca-ce79-467b-98da-74f654e62ace" />

Once I confirmed this, I performed a rollback and notified the vendor to ensure a permanent fix was being developed. I then posted a final update to inform users that the online banking portal was back online and fully functional.

<img width="759" height="229" alt="image" src="https://github.com/user-attachments/assets/709169f3-cf10-464b-9ade-f9be24775a94" />

I then changed the prioritiy level to emergency because I forgot to do so earlier, which is a key step for ensuring high-visibility issues are reviewed correctly. Once the priority was corrected to reflect the urgency of the banking outage, I pressed the resolved button to close the ticket. This ensures the final record accurately reflects the severity of the incident even though the work is complete.

<img width="757" height="865" alt="image" src="https://github.com/user-attachments/assets/f11a35ab-3de8-4c82-b217-054f2e567761" />

I returned to the end-user portal to simulate a new request from the accounting department regarding an Adobe upgrade. I entered the contact details and selected General Inquiry / Other as the help topic to reflect how users often categorize software requests. In the description, I specified that multiple staff members were unable to use their current Adobe software, signaling a departmental need.

<img width="760" height="943" alt="image" src="https://github.com/user-attachments/assets/e0eb4d7b-7d83-4111-b7fd-b362c0915e01" />

I logged back in as John and opened the ticket to review the details submitted by the user. This allowed me to assess the scope of the Adobe software issue and begin the review process. By viewing the ticket internally, I could prepare to adjust the SLA and assign the task appropriately.

<img width="764" height="911" alt="image" src="https://github.com/user-attachments/assets/a2f0b9da-9929-4f92-8906-27d889e57bea" />

I updated the SLA plan to Sev-C to reflect that the Adobe issue only affected two users, making it a lower priority compared to a full system outage. After assigning the ticket to John, I documented my troubleshooting step of performing a system restart, which successfully resolved the software error. I then posted the final resolution notes and clicked the resolved button to close out the request.

<img width="1512" height="956" alt="image" src="https://github.com/user-attachments/assets/6c18b9fe-2dbc-4ae5-b7c2-18896fa42506" />

I then went to the end url and pressed open a new ticket an entered a fake name email and phone number. The help topic was report a problem/ personal computer issue. The issue summary was that the CFO is unable to use his laptop. This setup allowed me to demonstrate how to handle an urgent hardware failure for an executive-level user.

<img width="1506" height="958" alt="image" src="https://github.com/user-attachments/assets/338d7ad1-7051-4740-a2ac-b7dbe7e25269" />

I then logged in as John and opened the ticket and then changed the priority to emergency and set the SLA Plan to Sev-B and assigned it to John. I then typed that the issue is that the CFO's laptop was not charging because the charger was broken, and then I brought new charger and the problem was resolved. Lastly I pressed resovle ticket. This scenario was designed to test how the help desk prioritizes hardware failures for executive leadership.
 
<img width="1469" height="950" alt="image" src="https://github.com/user-attachments/assets/26b31f96-70ff-42a9-966f-08991559d275" />
