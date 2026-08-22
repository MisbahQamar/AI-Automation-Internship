Recruitment Management System

Task Description
Built a recruitment management system for developer hiring. Candidates submit applications through a form and automatically enter a Kanban pipeline. The system analyzes experience, assigns candidate priority, and triggers appropriate actions as candidates move through recruitment stages.
Workflow
Application Form → Candidate Table → Experience Analysis → Priority → Kanban → Paths → Delay → Email/Notifications
Test Input & Output
Tested a developer application with 6 years of experience. The candidate was assigned High Priority and placed in the Applied stage. Moving the candidate to Screening triggered the screening email workflow.
Important Configuration
•	Form: Developer Recruitment Application 
•	Table: Candidates 
•	Initial stage: Applied 
•	5+ years = High 
•	2–4 years = Medium 
•	Less than 2 years = Low 
•	Recruitment stages: Applied → Screening → Technical Interview → HR Interview → Offer → Hired → Rejected 
•	No update for 5 days → Recruiter notification. 
How It Works
A candidate submits the recruitment form and their information is stored in the Candidates table and added to the Applied stage of the Kanban pipeline. The automation analyzes experience and assigns priority. Paths trigger screening, interview, HR, hiring, or rejection communications as the candidate moves through the pipeline, while a delayed check reminds the recruiter about candidates without updates.
