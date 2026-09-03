# UrbanCart AI Customer Support & Automation System

## Final Internship Task

UrbanCart is a Pakistan-based e-commerce business selling electronics, accessories, home and lifestyle products.

This project implements an AI-powered customer support and business automation system designed to provide reliable 24/7 customer assistance while escalating complex and high-priority cases to human staff.

## Solution Overview

The system combines:

- **Vapi** — AI voice customer support
- **n8n** — workflow orchestration and automation
- **Airtable** — leads, customers, support tickets and operational records
- **PostgreSQL** — structured relational data
- **Supabase** — database and vector search for RAG
- **Google Drive** — source documents and knowledge files
- **Notion** — internal documentation and knowledge management
- **Slack** — important sales and support notifications
- **Zapier** — business process automation
- **RAG** — grounded responses using current UrbanCart information

## Key Capabilities

- Product information and availability questions
- Price and delivery questions
- Returns and warranty information
- Customer identification
- Order lookup
- Lead capture
- Lead readiness classification
- Customer conversation logging
- High-priority complaint escalation
- Internal Slack notifications
- Airtable lead synchronization
- Voice-based customer interaction through Vapi
- Grounded AI responses using the UrbanCart knowledge base

## RAG Pipeline

UrbanCart documents are collected from Google Drive, text is extracted, content is divided into chunks, embeddings are generated, and the resulting information is stored in Supabase for vector-based retrieval.

The AI retrieves relevant knowledge before generating customer responses, reducing the risk of invented or outdated information.

## Human Escalation

Complex complaints, refund requests, damaged-item cases and other high-priority issues are routed toward human support rather than being handled entirely by AI.

Important operational events can be sent to Slack for the appropriate team.

## Project Structure

- `Task-1-Propose-and-Design` — solution analysis and design
- `Task-2-Build` — implementation documentation and evidence
- `screenshots` — implementation and testing evidence

## Reliability & Security

The solution uses validation, conditional logic, database operations, controlled escalation and error-tolerant notification handling.

API keys, passwords, tokens and other private credentials are not included in this repository.

## Implementation Goal

The solution is designed to be reliable, scalable, maintainable and cost-conscious while providing accurate automated customer support and preserving human control for cases that require staff intervention.
