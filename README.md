<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket: How to Create Tickets and Resolve Them</h1>
In this tutorial, osTicket will be utilized to show how to create a ticket as a user. Then on the backend, it will show how administrators and agents assign tickets, work them, and resolve them. This tutorial will build intuition on how to use a ticket system for both users and IT professionals.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Intake</h3>

First go to http://localhost/osTicket/ in your browser. We are going to act like a end user and create a ticket regarding a problem that user might have. 

![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/147f0fcb-de69-4d78-80cf-71f78dc9957a)
![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/2f7b7bfe-0f15-47bf-bb56-708ce73e1b74)
![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/3a496a8b-b90f-4027-9aa0-2f487da9b4d2)

<h3>Assignment and Communication</h3>

First go to http://localhost/osTicket/ in your browser and login using the information from the agent created from the post instalation of osTIcket. 

Usually, an administrator or manager/supervisor will manage which employee will handle which ticket.  The person assigning the ticket will also assign and set the priority of the ticket that varies from low to high priority or an emergency. In this example, Jane is assigning the ticket to herself and setting the priority level to emergency. The department responsible was changed from support to system administrators because in this scenario the support department is not equiped to handle this issue. The issue is an SLA Sev-A and will need an experienced person to work the issue. 

![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/0b4c794c-41ee-474d-a6b3-a86d7d2ee4da)
![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/c59539bf-5993-45c1-8dbf-fe222a02e191)
![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/907c71fb-c858-4b69-95b0-3c923432fc88)
![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/a9102801-4ec3-4410-bd0d-79a1411e4b64)


<h3>Working the Issue</h3>
In this example, Jane is working the ticket by answering to the user. On the backend, Jane is working with another department to have the issue fixed. 

![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/daeb2c95-178f-4b15-bcd3-22e35be8ecde)

<h3>Resolution</h3>
In this final example, Jane was able to get the appropriate parties notified of the issue and got it resolved. Ticket was closed. 

![image](https://github.com/mathew-perez/ticket-lifecycle/assets/144407220/6aa64a88-d71f-49a2-b93b-adef75ace13d)


Hopefully this lab was able to provide an understanding about osTIcket and the ticket lifecycle.
