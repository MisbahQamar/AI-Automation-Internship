Task Description
Built an autonomous AI Instagram Content Agent that decides what content should be posted based on previous content, audience needs, and research. The agent generates content, evaluates its quality using a second AI critic, stores approved content in a calendar, and sends it for human approval instead of publishing automatically.
Workflow
Trigger → Agent → Research → Decision → Content Generation → Critic AI → Approval Decision → Content Calendar → Human Approval
Test Input & Output
Tested with a request to create Instagram content for an AI automation course targeting business owners. The agent generated the content, evaluated it with the AI critic, achieved a score above 7, stored the approved content in the Instagram Content Calendar, and set its status to Awaiting Approval.
Important Configuration
•	Content Ideas table 
•	Instagram Content Calendar 
•	Previous-content analysis 
•	Content-type repetition detection 
•	AI content generation 
•	Second AI quality evaluation 
•	Score below 7 → Rewrite 
•	Score 7 or higher → Approve 
•	Status = Awaiting Approval 
•	Marketing person receives the content 
•	Direct Instagram publishing disabled 
How It Works
The agent analyzes previous content and independently decides what should be posted next. It generates the post and sends it through a second AI quality check before storing approved content in the calendar. The content is then sent to the marketing person for human approval and is never published automatically.
