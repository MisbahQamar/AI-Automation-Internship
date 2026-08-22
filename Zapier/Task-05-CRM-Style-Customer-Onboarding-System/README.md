CRM Style Customer Onboarding System

Task Description
Built a CRM-style customer onboarding system that captures new customers through an onboarding form and automatically creates customer records and Kanban cards. The workflow manages customers through predefined onboarding stages and triggers appropriate actions as stages change.
Workflow
Onboarding Form → Customer Table → Kanban → Stage Paths → Delay → Email/Notifications
Test Input & Output
A sample customer from ABC Company was submitted through the onboarding form. The customer record and Kanban card were created with the initial stage New Lead, the account manager was assigned, and a confirmation email was sent.
Important Configuration
•	Form: Customer Onboarding Form 
•	Table: Customers 
•	Initial stage: New Lead 
•	Kanban stages: New Lead → Qualified → Proposal → Won → Onboarding → In Progress → Completed 
•	Qualified for more than 3 days → Account Manager notification 
•	Stage changes trigger the appropriate email, task, or notification. 
How It Works
When a customer submits the onboarding form, their information is stored in the customer table and represented as a Kanban card in New Lead. As the card moves through the onboarding stages, Paths trigger the appropriate tasks, emails, and notifications. A delayed check alerts the account manager if a lead remains in Qualified for more than three days.
