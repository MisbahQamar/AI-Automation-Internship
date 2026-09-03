# Task 2 — Build the UrbanCart Solution

## Overview

The UrbanCart automation system was implemented as an end-to-end AI customer support and business automation solution.

## Implemented Components

### 1. RAG Knowledge Pipeline
Google Drive documents are processed through n8n, text is extracted, content is chunked, embeddings are generated, and the resulting vectors are stored in Supabase for knowledge retrieval.

### 2. Customer Support Workflow
The main n8n workflow handles:
- Customer identification
- Customer creation
- Conversation management
- Knowledge-base retrieval
- Grounded AI responses
- Order lookup
- Lead capture
- Lead readiness
- Escalation
- Conversation logging

### 3. Vapi Voice Agent
A dedicated UrbanCart AI Voice Agent was created in Vapi and connected to the existing n8n customer-support webhook.

The agent handles customer requests naturally through voice while relying on the automation workflow for accurate information.

### 4. Airtable Operations
Airtable is used for operational records including:
- Customers
- Leads
- Support Tickets
- Tasks

New leads captured through the workflow are synchronized into the UrbanCart Leads table.

### 5. Slack Notifications
Slack is used for important operational events such as:
- Sales lead notifications
- Customer support escalations
- High-priority issues

Normal customer questions do not generate unnecessary Slack notifications.

### 6. Zapier Automation
Zapier automations were implemented using Airtable as the trigger source for business follow-up actions, including Gmail notification and Google Calendar event creation.

## AI Safety and Reliability

The system is designed to avoid invented information by retrieving relevant UrbanCart knowledge before responding.

Complex cases such as complaints, refunds and damaged-item issues are escalated instead of being handled entirely by AI.

Notification failures are isolated so that a failed internal notification does not block the customer-facing response.

## Demonstrated Scenarios

The implementation was tested with realistic UrbanCart scenarios covering:
- Product and policy questions
- Existing order lookup
- New lead capture
- High-priority customer complaints
- Internal team escalation
- Voice-agent interaction

## Evidence

Implementation screenshots are included with the final project submission to demonstrate the workflows, database records, AI responses, escalations, notifications and integrations.

## Technologies

Vapi, n8n, Airtable, PostgreSQL, Supabase, Google Drive, Notion, Slack, Zapier and RAG.
