# AI Lead Qualification Automation System

An AI-powered lead qualification workflow built using n8n and OpenAI APIs that automatically analyzes incoming leads, classifies them based on business criteria, and routes them through different workflows.

---

## Overview

This system helps businesses reduce manual lead screening by automatically identifying high-quality, medium-quality, and low-quality leads.

The workflow collects lead information, evaluates it using AI, updates the CRM, and performs different actions depending on the qualification result.

---

## Features

- AI-powered lead qualification
- Automated CRM updates
- Structured AI output parsing
- Lead classification (High / Medium / Low)
- Automatic email responses
- Slack notifications for sales teams
- Meeting scheduling workflow
- Workflow-based lead routing

---

## Workflow Logic

### 1. Lead Submission
A lead submits their details through a form or webhook.

Collected information may include:
- Name
- Email
- Company
- Budget
- Requirement
- Urgency

---

### 2. CRM Record Creation
The lead data is automatically stored in the CRM system.

---

### 3. AI Lead Qualification
The AI analyzes the lead based on:
- Budget
- Business intent
- Requirement clarity
- Decision-maker status
- Urgency
- Business maturity

The AI returns a structured output with:
- Lead Quality
- Qualification Reason
- Recommended Action

---

### 4. Lead Routing

## High Quality Lead
If the lead matches strong qualification criteria:
- Thank-you email is sent
- Sales team gets notified on Slack
- Meeting scheduling email is triggered

## Medium Quality Lead
- Lead is stored for future follow-up
- Optional nurturing workflow can continue

## Low Quality Lead
- Polite rejection email is sent
- Workflow ends automatically

---

## Tools Used

- n8n
- OpenAI API
- Gmail
- Slack
- CRM
- Structured Output Parser

---

## Use Case

This workflow helps businesses:
- reduce manual work
- save response time
- prioritize serious leads
- improve sales efficiency
- automate repetitive tasks

---

## Demo

Demo video:
https://drive.google.com/file/d/1afP8yyWFmHnB3IToK8kQO3a4PzRf6-ZW/view?usp=sharing



---

## Future Improvements

- WhatsApp integration
- Advanced CRM integrations
- Multi-step nurturing workflows
- Analytics dashboard
- Voice AI support
