<img width="673" height="362" alt="image" src="https://github.com/user-attachments/assets/55d526a7-4460-48c6-affb-2f3a8874779d" />

# AI-Powered Lead Generation Automation using n8n

## Project Overview

This project automates lead generation using n8n and OpenAI.

The workflow reads company information from Google Sheets, processes each company individually, generates a personalized cold email using AI, and stores the generated email back into Google Sheets automatically.



## Features

- Reads company data from Google Sheets
- Processes each company individually
- Uses OpenAI GPT model
- Generates personalized cold emails
- Stores generated emails back into Google Sheets
- Fully no-code automation



## Workflow

Manual Trigger
        ↓
Google Sheets
        ↓
Loop Over Items
        ↓
AI Agent
        ↓
OpenAI Chat Model
        ↓
Google Sheets



## Technologies Used

- n8n
- Google Sheets
- OpenAI GPT-5 mini
- AI Agent
- No-Code Automation

## Screenshots

### Workflow

![workflow](workflow.png)

### AI Generated Email

![AI Output](AI_output.png)

### Google Sheet Output

![Google Sheet](Generated%20Emails.png)



## How to Import

1. Download workflow.json
2. Open n8n
3. Click Import Workflow
4. Select workflow.json
5. Connect your Google Sheets credentials
6. Connect your OpenAI credentials
7. Execute the workflow


## Future Improvements

- Gmail Integration
- LinkedIn Lead Generation
- CRM Integration
- Automatic Email Sending
- Lead Qualification using AI
