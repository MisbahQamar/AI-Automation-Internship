Task Description
Built an autonomous AI customer support resolution agent that determines customer intent, severity, required data, appropriate tools, and the correct resolution action. The agent can search customer and ticket data, create or update tickets, send emails, and escalate urgent issues to humans.
Workflow
Customer Message → Intent Detection → Severity → Customer/Ticket Search → Decision → Create/Update Ticket → Email/Escalation
Test Input & Output
Tested with: “I was charged twice for my subscription.”
The agent identified the issue as a Duplicate Payment/Billing Issue, assigned High Priority, searched for existing tickets, and created or updated the appropriate finance ticket.
Important Configuration
•	Customer Table: Customers 
•	Ticket Table: Support Tickets 
•	Duplicate payment → Finance Ticket 
•	Technical issue → Technical Support Ticket 
•	Password issue → Password reset instructions 
•	Angry/urgent customer → Human escalation 
•	Existing ticket → Update instead of creating duplicate 
•	New issue → Create ticket 
•	Status: Open 
How It Works
The agent analyzes each customer message and autonomously determines the intent, severity, required information, and appropriate action. It searches existing customer and ticket records before taking action. If an existing ticket is found, it updates that ticket instead of creating a duplicate; otherwise, it creates the appropriate support ticket and sends the required communication.
