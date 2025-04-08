<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. osTicket will be used for this simulation.<br />


<h2>Prerequisites</h2>

- Install osTicket [https://github.com/BrianRivera22/osticket_prereqs]
- Configure osTicket [https://github.com/BrianRivera22/post_install_config]

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/BrianRivera22/ticket_lifecycle/blob/main/osTicket%20-%20Ticket%20Lifecycle/1.png"/>
</p>
<p>
Begin by entering http://localhost/osTicket into the browser. This will bring us to the end user ticket creation page. Here we can submit a ticket as Karen. After the ticket is submitted, log in at http://localhost/osTicket/scp/login.php as agent John Doe.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/ticket_lifecycle/blob/main/osTicket%20-%20Ticket%20Lifecycle/2.png"/>
</p>
<p>
Karen has submitted a ticket regarding users not being able to use the online banking platform. We can view this ticket as an agent.

We can assign the ticket to Jane or a team if one is created. Take note of the SLA and priority. In my lab I set the priority as "Normal" when is should be set to "Emergency" in this instance. These can be modified if needed when we find out more about the ticket.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/ticket_lifecycle/blob/main/osTicket%20-%20Ticket%20Lifecycle/3.png"/>
</p>
<p>
Now as an agent we can acknowledge Karen's ticket and begin "working" it to completion. We can first acknowledge the ticket by replying publicly to Karen

Using the internal notes tab, we can submit notes where only the support team can see. This is helpful to have communication between agents on the progress of the ticket or new developments.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/ticket_lifecycle/blob/main/osTicket%20-%20Ticket%20Lifecycle/4.png"/>
</p>
<p>
osTicket keeps track of all correspondance between the agents and users to keep track of progress.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/ticket_lifecycle/blob/main/osTicket%20-%20Ticket%20Lifecycle/5.png"/>
</p>
<p>
Once we "work" this ticket to resolution, we can scroll up to the top and change the status to "resolved". In the overview page under the tickets tab, we can view closed tickets. These are tickets that have been resolved and closed.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/ticket_lifecycle/blob/main/osTicket%20-%20Ticket%20Lifecycle/6.png"/>
</p>
<p>
To simulate ticket intake via phone or email, we can navigate to tickets as an agent and create a new ticket. The new ticket can be created based on the nature of the issue being reported.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/ticket_lifecycle/blob/main/osTicket%20-%20Ticket%20Lifecycle/7.png"/>
</p>
<p>
We can submit replies to the ticket and "work" the ticket to resolution. The ticket can be given a priority and it can be assigned to an agent. As we learn more information about the ticket we can change various elements about the ticket like the SLA. Instead of the entire department not being able to use Adobe we realize it is just 2 users, this prompts a change in the SLA.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/ticket_lifecycle/blob/main/osTicket%20-%20Ticket%20Lifecycle/8.png"/>
</p>
<p>
Once we arrive at a resolution, we can change the status of the ticket at the top from "Open" to "Resolved". Hooray for ticket resolution!

There are lots of other things that can be done within osTicket so feel free to explore around to build more intuition with osTicket.

This conlcudes the Ticket Lifecycle lab!
</p>
<br />
