# Task 2 – Employee Expense Approval

## Task Description

Build an internal expense management system using a Zapier Interface, Zapier Table, and automation. Employees submit expenses through the Employee Expense Portal, and the automation evaluates the expense risk and determines whether approval is required.

## Interface / Form

Interface Name: Employee Expense Portal

### Form Fields
- Employee Name
- Employee Email
- Department
- Expense Type
- Amount
- Expense Date
- Description
- Receipt Upload
- Manager Email

### Expense Type Options
- Travel
- Food
- Software
- Equipment
- Other

## Zapier Table

Table Name: Expense Requests

### Columns
- Request ID
- Employee
- Department
- Type
- Amount
- Description
- Receipt
- Manager
- Approval Status
- Risk Level
- Submitted At

## Default / Approval Logic

The automation determines risk according to the expense amount:

- Amount below $100 → Low Risk
- $100–$500 → Medium Risk
- Amount above $500 → High Risk

Approval actions:

- Low Risk → Automatically Approved
- Medium Risk → Approval request sent to Manager
- High Risk → Approval request sent to Manager and Finance

If the receipt is missing:

- Approval Status → Receipt Required

## Automation Workflow

Employee submits form → Capture expense data → Generate Request ID → Store record in Zapier Table → Determine Risk Level → Check Receipt → Filter/Path → Approval or Notification

## Test Input

Software | $750 | No receipt

## Expected Output

Request ID: EXP-0045  
Risk Level: High  
Approval Status: Receipt Required

## Important Configuration

The workflow uses:
- Zapier Interfaces for the expense form
- Zapier Tables for storing expense requests
- Formatter for data processing and Request ID generation
- Filter/Paths for risk-based decisions
- Email/Slack for approval notifications
- Approval step for manager/finance review

## How the Automation Works

When an employee submits an expense, the form captures the expense details. A unique Request ID is generated and the complete request is stored in the Expense Requests table. The automation evaluates the amount to determine the risk level. Low-risk expenses are automatically approved, while medium- and high-risk expenses require approval. If the receipt is missing, the request is marked as Receipt Required.

## Evidence / Screenshots

The following evidence should be included:
1. Employee Expense Portal / Form
2. Expense Requests Zapier Table
3. Automation Workflow
4. Test Input
5. Test Output / Approval Result
