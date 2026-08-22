Task Description
Built an AI customer support chatbot for the fictional software company CloudFlow. The chatbot answers questions using a defined knowledge base and escalates unknown issues or human-support requests to a Zapier support-ticket workflow.
Workflow
CloudFlow Chatbot → AI/Intent Detection → Priority Detection → Filter/Path → Support Tickets Table → Notification
Test Input & Output
Tested pricing, unknown-information, human-escalation, and critical-support scenarios. The chatbot answered known questions from the knowledge base, avoided unsupported claims, and created support tickets for escalated issues.
Important Configuration
•	Starter: $19/month 
•	Professional: $49/month 
•	Business: $149/month 
•	Support: Monday–Friday, 9 AM–6 PM 
•	Refund period: 14 days 
•	Unknown information must not be invented. 
•	Human escalation collects Name, Email, and Problem. 
•	Critical = system completely down. 
•	High = cannot access account. 
•	Medium = normal question. 
•	Low = general request. 
•	Support ticket status = Open. 
How It Works
The CloudFlow chatbot answers customer questions using its approved knowledge base. When it cannot accurately answer a question or the customer requests human assistance, it collects the required information and sends it to Zapier. Zapier determines the priority and creates a support ticket in the Support Tickets table, with notifications for the support team when required.
