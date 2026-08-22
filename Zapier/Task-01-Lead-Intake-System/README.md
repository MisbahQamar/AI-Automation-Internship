# Task 1 – Lead Intake System

## Task Description
Build a Zapier Interface containing a lead submission form. Submitted leads are automatically stored in a Zapier Table, scored, categorized, and high-priority leads trigger a sales notification.

## Interface
Page: Sales Lead Intake Form

Fields:
- Full Name
- Email
- Phone
- Company
- Industry
- Budget
- Lead Source
- Requirement
- Urgency

## Zapier Table
Table: Leads

Columns:
- Lead ID
- Name
- Email
- Phone
- Company
- Industry
- Budget
- Lead Source
- Requirement
- Urgency
- Lead Score
- Status
- Created At

Default Status: New

## Automation
1. Capture form data.
2. Calculate Lead Score.
3. Generate a unique Lead ID.
4. Store the complete lead in Zapier Tables.
5. Categorize the lead as Hot, Warm, or Cold.
6. Notify the sales team when the lead is high priority.

## Lead Scoring
- High urgency: +30
- Medium urgency: +20
- Low urgency: +10
- Budget above $5,000: +30
- Budget $1,000–$5,000: +20
- Budget below $1,000: +10
- Referral: +20
- LinkedIn: +15

Categories:
- 70+: Hot
- 40–69: Warm
- Below 40: Cold

## Test Input
Ahmad | ABC Company | $8,000 | LinkedIn | High

## Expected Output
Lead ID: LEAD-2026-001
Lead Score: 75
Status: New
Priority: Hot

## Workflow
Interface Form → Capture Data → Calculate Score → Generate Lead ID → Zapier Table → Filter/Path → Sales Notification

## Evidence
Screenshots to be added:
- Interface/Form
- Zapier Table
- Workflow/Automation
- Test input
- Test output
- Important configuration
