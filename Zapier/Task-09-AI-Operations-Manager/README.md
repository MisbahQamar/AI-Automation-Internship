Task Description
Built an autonomous AI Operations Manager that analyzes sales, tasks, and support activity every morning. The agent identifies operational problems, prioritizes them, recommends actions, performs predefined safe actions, and generates a Daily Operations Report for human review.
Workflow
Schedule → AI Agent → Sales/Tasks/Support Tools → Analysis → Prioritization → Safe Action → Daily Operations Report → Human
Test Input & Output
The agent was configured to analyze sales, task, and support data and identify stalled deals, overdue tasks, and critical unresolved support issues. It prioritizes the findings, recommends appropriate actions, creates permitted follow-up tasks when necessary, and stores the Daily Operations Report.
Important Configuration
•	Daily schedule: 9:00 AM Asia/Karachi 
•	Sales Table 
•	Tasks Table 
•	Support Table 
•	Daily Operations Report 
•	Stalled deal detection 
•	Follow-up detection 
•	High-value deal detection 
•	Overdue task detection 
•	Workload detection 
•	Critical support detection 
•	Safe follow-up task creation 
•	Human approval for external/high-risk actions 
Safety Rules
The agent cannot delete records, change financial information, send external messages without approval, or perform irreversible actions. Only predefined safe operational actions are permitted.
How It Works
Every morning, the AI Operations Manager analyzes sales, task, and support data instead of simply summarizing it. It identifies problems, prioritizes them, recommends actions, performs permitted safe actions such as creating follow-up tasks, and stores a Daily Operations Report for human review.
