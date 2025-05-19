<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial demonstrates the full ticket lifecycle in osTicket, from the moment a user submits a ticket through assignment, communication, troubleshooting, and resolution. This process generally simulates a real-world IT help desk workflow.
osTicket.<br />


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

**INTAKE**
![end user](https://github.com/user-attachments/assets/e32ae39a-aa64-40af-a9ca-cd5c43316ca5)
![new ticket](https://github.com/user-attachments/assets/54146b50-8ca9-42d6-9621-d382a48f9ff8)
![new ticket submitted](https://github.com/user-attachments/assets/77205473-723e-469d-84ff-bbc3dba5b1a3)
- the above images shows the typical ticket submission proccess for an end-user through the user panel
- Ticket fields typically include:
  - Help Topic
  - Issue Summary
  - Message/Description
- After submission, the ticket appears in the system with a timestamp and a ticket number.

**AGENT VIEW AND CATAGOTIZATION**
![agent see ticket](https://github.com/user-attachments/assets/8ba9f319-4552-42d7-b328-673b85efd6b6)

- this is the typical dashboard for an agent showing all tickets organized into several catagories.
- From the Agent Dashboard, staff can view incoming tickets.
- Tickets are automatically or manually categorized to:
  - Open
  - Assigned
  - Overdue
  - Closed
- This ensures visibility and allows agents to prioritize their workload.

**WORKING THE ISSUE**
![handling tickets 1](https://github.com/user-attachments/assets/1553cc53-baea-4b96-9123-fd509c2edfb5)
![handling ticket 2](https://github.com/user-attachments/assets/dff7f6f5-f76d-44e8-b8dd-ad10f9754d22)
- This is where tickets gets handled with options to assign a priority, department, user, and/or SLA so that it can be worked and directed efficiently
- When handling a ticket, agents can:
  - Assign it to a department or specific team
  - Set priority level (e.g., Low, Normal, High, Emergency)
  - Attach a Service Level Agreement (SLA) to enforce response deadlines
  - Communicate with the user via threaded messages, mostly updates
  - the threads can also be used for general updates or transparent internal communication, there is also internal notes which can be seen exclusively by agents and admins
- Communication typically happens in the comments and status gets updated until it is resolved

**RESOLUTION**
- Once the issue is resolved:
  - The agent updates the ticket status to Resolved or Closed
  - The system can trigger a confirmation or feedback request to the user
  - A full ticket history remains available for auditing, knowledge base creation, or SLA review

*This simulates the flow of how IT teams work through user issues. Leveraging osTicket’s built-in features, agents maintain clarity, admins track performance, and end-users experience professional service delivery.*
