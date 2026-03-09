# AI Job Aggregator using n8n

<img width="1917" height="866" alt="image" src="https://github.com/user-attachments/assets/da7bd446-22f5-4d93-9d37-11d906630a46" />

This project is an automated job discovery workflow built using **n8n**.

It collects job listings from multiple sources and filters them for **fresher / entry-level roles** using AI.

## Features

- Fetch jobs from multiple APIs
- Normalize job data
- Merge multiple job sources
- AI filtering for fresher roles
- Store results in Google Sheets

## Job Sources

- Remotive API
- WeWorkRemotely RSS
- Jobicy API

## Workflow Architecture

Trigger → Fetch Jobs → Normalize Data → Merge Sources → AI Filter → Google Sheets

## Target Roles

- Internship
- Trainee
- Associate
- Junior Developer
- Entry-level jobs

## Tools Used

- n8n
- Gemini AI
- Google Sheets API

## How to Use

1. Import the `workflow.json` into n8n
2. Configure API credentials
3. Run the workflow or schedule it

---

