# Microsoft Copilot Finance Reporting AI Agent

/finance-reporting-ai-agent
 ├── README.txt
 ├── sample_data.xlsx
 ├── prompts/
 │    └── system_prompt.txt
 ├── flows/
 │    └── power_automate_description.txt

## Overview

This project presents a Microsoft Copilot Finance Reporting AI Agent for financial and operational reporting built using Microsoft Copilot Studio, Power Platform, and Python-based data processing.

The agent enables business users to query financial data in natural language and receive structured answers enriched with business insights.



## Use Case

The agent supports common business scenarios such as:

* Analyzing costs and trends
* Identifying key cost drivers
* Generating financial summaries
* Triggering automated workflows (e.g. sending reports)

### Example questions:

* What are the main cost drivers this month?
* Show me cost trends for the last quarter
* Why did expenses increase?

---

## Architecture

```
User (Teams / Chat)
        ↓
Copilot Studio (LLM + Instructions)
        ↓
Knowledge Base (sample_data.xlsx)
        ↓
Python Logic (data processing, analysis)
        ↓
Power Automate (workflows)
        ↓
Response to user
```

---

## Tech Stack

* Microsoft Copilot Studio
* Power Automate
* Python 
* Excel
---

## Sample Data

The agent operates on structured financial data with the following fields:

* Date	
* Department	
* Cost_Type	
* Amount_EUR


Departments include:

* Marketing
* IT
* HR
* Finance

---

## Prompt Design

The agent is guided by structured system instructions that ensure:

* Accurate and reliable responses
* No hallucination of financial data
* Clear and business-friendly explanations
* Structured outputs (bullet points, summaries)

---

## Automation (Power Automate)

Workflows include:

* Sending weekly financial reports via email
* Triggering alerts for unusual cost patterns
* Storing generated summaries

---

## Project Goal

This project demonstrates how AI, automation, and data integration can be combined to support business decision-making and process optimization.
