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

I then logged in as John, which is a user I previously created. I opened the online banking system ticket to view the ticket details. 

   <img width="766" height="943" alt="image" src="https://github.com/user-attachments/assets/2e5dc947-ea29-4b67-a9bb-69754f255d78" />

   I changed the SLA plan to Sev-A 24/7 schedule because the problem had a wide impact, due to customers not being able to do online banking. Then I changed the help topic to report problem/buisness crtical outage because no customer is able to acess online banking . I assigned the problem to online banking team and the description I used was customers cant acess the online banking portal.
   
   <img width="767" height="924" alt="image" src="https://github.com/user-attachments/assets/d3d4fa90-37ed-4c5e-8f99-47678b8d9548" />

I then signed in as jane a user I created that is apart of the online banking lab, and I will go to the ticket as jane and assign the ticket to myself. 

 <img width="766" height="952" alt="image" src="https://github.com/user-attachments/assets/d465f0ca-ce79-467b-98da-74f654e62ace" />

 I then typed an update that stated I suspect the problem was related to recent updates and I will undo them if I find out this is true then I typed it was determined the root cause was the recent update, we rolled it back, notified the vendor, and are waiting for a proper fix. Online banking should now be up and running. 

<img width="759" height="229" alt="image" src="https://github.com/user-attachments/assets/709169f3-cf10-464b-9ade-f9be24775a94" />

I then changed the prioritiy level to emergency and pressed the resolved ticket button.

<img width="757" height="865" alt="image" src="https://github.com/user-attachments/assets/f11a35ab-3de8-4c82-b217-054f2e567761" />

I then went to the enduser portal for creating tickets I then I pressed on open a new ticket again and entered a fake name email and phone number. The problem is accounting department needs an adobe upgrade I will make the help topic general inquiry/ Other the description of the problem was many people in the accounting department cannot use their adobe software.

<img width="760" height="943" alt="image" src="https://github.com/user-attachments/assets/e0eb4d7b-7d83-4111-b7fd-b362c0915e01" />

Then I logged back in as john and viewed inside the ticket

<img width="764" height="911" alt="image" src="https://github.com/user-attachments/assets/a2f0b9da-9929-4f92-8906-27d889e57bea" />

 I then made the SLA plan Sev-C because the scenario the lab director gave for this ticket is that only two people in the accounting department are unable to open and use adobe reader w and assigned it to John. I then typed as a post that I will test a restart and that ended up working so I posted that the restart fixed the issue then I pressed ticket resolved

<img width="1512" height="956" alt="image" src="https://github.com/user-attachments/assets/6c18b9fe-2dbc-4ae5-b7c2-18896fa42506" />

I then went to the end url and pressed on open a new ticket for creating tickets then I pressed open a new ticket an entered a fake name email and phone number. The help topic was report a problem/ peronal computer issues. The issue summary was that the CFO is unable to use his laptop. 

<img width="1506" height="958" alt="image" src="https://github.com/user-attachments/assets/338d7ad1-7051-4740-a2ac-b7dbe7e25269" />

I then logged in as John and opened the ticket and then changed the priority to emergency and set the SLA Plan to Sev-B then I assigned it to John. I then typed that the issue is that the CFO's laptop was not charging because the charger was broken, and then I brought new charger and the problem was resolved. Lastly I pressed resovle ticket.
 
<img width="1469" height="950" alt="image" src="https://github.com/user-attachments/assets/26b31f96-70ff-42a9-966f-08991559d275" />
