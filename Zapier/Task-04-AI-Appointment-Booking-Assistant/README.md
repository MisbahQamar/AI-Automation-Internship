Task Description
Built an AI appointment booking assistant for a fictional clinic. The chatbot understands doctor, date and time requests, checks appointment availability, collects patient details, creates appointments, and confirms successful bookings.
Workflow
Chatbot → AI Extraction → Appointment Search → Availability Filter → Create Record → Confirmation
Test Input & Output
Tested a request for Dr. Sara at 4 PM the following day. The chatbot extracted the doctor, date and time, collected patient details, checked availability, and created an appointment when the slot was available.
A second test using the same doctor, date and time was rejected to prevent double booking.
Important Configuration
•	Dr. Ahmed — General Physician 
•	Dr. Sara — Dermatologist 
•	Dr. Ali — Cardiologist 
•	Appointment ID generated automatically. 
•	Date converted from relative expressions such as “tomorrow.” 
•	Availability checked before booking. 
•	Existing Doctor + Date + Time combination cannot be booked twice. 
•	Unavailable slots offer 3 PM or 5 PM alternatives. 
•	Successful appointments are marked Confirmed. 
How It Works
The chatbot extracts the requested doctor, date and time from natural language. It checks the Appointments table before booking to ensure the requested slot is available. If available, it collects the remaining patient information and creates a confirmed appointment; if unavailable, it offers alternative times instead.
