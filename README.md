# ticket-lifecycle

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

1)INTAKE

 - We'll start by accessing the page where tickets can be created, as if we're an external user:
 - On the web browser, go to the End User Ticket Page (http://localhost/osTicket/).
 - Click on "Open a New Ticket".

<img src="https://i.imgur.com/LpFntNU.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

 - Enter an Email Address and Full Name (this example uses karen@osticket.com / Karen Karen)
 - Select any Help Topic or one that was created in the previous demo (this example uses Business Critical Outage).
 - Type a quick Header and a short description under Issue Sumamry (anything can be typed for demonstration purposes).
 - Once done, click "Create Ticket".

<img src="https://i.imgur.com/jM4T04z.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

 - Here are a few more examples.

<img src="https://i.imgur.com/GWqiCh7.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/LvETsia.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

2)Assignment and Communication

- Now that tickets have been made! We'll now go into the Agent's perspective of their end:
  - On the web browser, go to the Help Desk Login Page (http://localhost/osTicket/scp/login.php).
  - Log into the osTicket Help Desk using an Agent account (this example uses username jane.doe / jane.doe@osticket.com).
  - Once logged in, you should see the created tickets from the clients.
  - Click on any available ticket (this example selects entire mobile online banking is down).

<img src="https://i.imgur.com/U5p8ABN.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

- As an Agent, we'll observe and configure information of this ticket.

-  Having the entire mobile online banking down is something that could have a major impact on the company, resulting in losing money. The severity on this should be higher and should be assigned to the departments/teams that can be responsible to resolve this issue ASAP!!!
   - Set Priorty from Normal to a higher level (this example uses Emergency).
   - Assign to a higher-tier department (this example uses System Administrators).
   - Assign a specific person(s) the responsbility to manage this ticket (this example uses the current user, Jane Doe).
   - Modify the SLA Plan from Normal to a higher level (this example uses SEV-A).

<img src="https://i.imgur.com/mniP7Gv.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

3)Working the Issue
 - Observing the overview page, we can see every update happening within the Ticket Thread. As an Agent, we can communicate under Post Reply to bring status updates to anyone viewing this ticket or for conversational purposes regarding the issue at-hand.

<img src="https://i.imgur.com/McVwKmt.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ZOk9tHW.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/E9vicWy.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

 - Under Post Reply, type in a random message.
 - Keep the Ticket Status to "Open (current)", assuming the issues isn't resolved.
 - Click "Post Reply".

<img src="https://i.imgur.com/qSKDXDR.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

4)Resolution

 - Let's say the issue has finally been resolved:
   - Under Post Reply, type in a random message stating a final update of the matter.
   - Change the Ticket Status to "Resolved".
  
<img src="https://i.imgur.com/i1KZGFd.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/> 

 - Once a ticket is resolved, it is considered "closed", so it will disappear from the Open Tickets page.
You can find it under the "Closed" tab, where you can see how many was closed at a certain time frame.


<img src="https://i.imgur.com/sdPg401.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

 - Continue to go through the rest of the remaining tickets and use best judgement on their Priorty, assignment to departments and teams, etc.

<img src="https://i.imgur.com/dFPAOsF.png.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

          !!!! COMPLETE !!!!





