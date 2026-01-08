# Customer Feedback Triage & Sentiment Escalation (AI)

## Overview
An AI-powered workflow that automatically processes raw customer feedback,
classifies it, detects sentiment, and escalates critical issues to the right teams.

This workflow is designed to reduce manual effort in feedback analysis and ensure
high-impact customer issues are not missed.

## What Problem It Solves
Customer feedback is often:
- Unstructured
- High in volume
- Spread across tools and teams

Manually reviewing this data leads to delays, missed insights, and slow response
to critical issues.

## Workflow Steps
- Accepts raw customer feedback (forms, sheets, or tools)
- Uses an AI agent to:
  - Categorize feedback (Complaint, Feature Request, Compliment, Query)
  - Detect customer sentiment
  - Generate a concise summary
- Merges AI insights with original feedback for context
- Routes feedback using logic-based conditions:
  - Negative or critical feedback is escalated
  - Positive feedback is logged for insights
- Sends alerts or structured outputs to Slack / Notion / Sheets

## Why This Matters for Product Teams
- Faster issue detection
- Better prioritization of customer pain points
- Data-backed product decisions
- Reduced operational overhead

## Built With
- n8n
- LLM (Groq / OpenAI)
- Slack / Notion / Google Sheets

## Example Use Case
Automatically alert the product or support team when a customer submits
a highly negative complaint, while storing all feedback in a structured format
for analysis.

