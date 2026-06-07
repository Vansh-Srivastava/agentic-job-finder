# 🤖 Agentic Job Finder

An AI-powered job discovery and application intelligence platform that automates the entire job search process. The system continuously scans LinkedIn job listings based on user-defined preferences, evaluates each opportunity against a candidate's resume using Google Gemini, generates personalized cover letters, and ranks opportunities by relevance.

Built using n8n workflow automation, Google Gemini, LinkedIn job scraping, Google Sheets, and Slack integrations, the platform transforms a traditionally manual and time-consuming job search into an intelligent, fully automated workflow.

---

## 📌 Project Overview

The Agentic Job Finder is designed to help job seekers discover high-quality opportunities without manually searching through hundreds of listings.

The workflow automatically retrieves a candidate's resume, reads job preferences from Google Sheets, searches LinkedIn for matching positions, extracts job details, and uses Google Gemini to analyze compatibility between the candidate profile and job requirements.

For each opportunity, the system:

- 🔍 Searches and collects relevant job listings from LinkedIn
- 📄 Extracts detailed job descriptions and company information
- 🤖 Calculates an AI-powered match score using Google Gemini
- ✍️ Generates a personalized cover letter for each role
- 📊 Stores results in Google Sheets for tracking
- 🔔 Sends high-scoring opportunities directly to Slack

This creates an end-to-end autonomous job search assistant capable of finding, evaluating, and prioritizing job opportunities in real time.

---

## 🎯 Problem Statement

Finding relevant jobs is often repetitive and time-consuming. Candidates typically need to:

- Search multiple job portals every day
- Read hundreds of job descriptions
- Evaluate job suitability manually
- Create customized cover letters
- Track opportunities across different platforms

This process is inefficient and can result in missed opportunities.

---

## 💡 Solution

The Agentic Job Finder automates the entire workflow by combining AI reasoning with workflow automation.

The system:

1. Monitors job opportunities automatically.
2. Matches jobs against a candidate's resume.
3. Scores each opportunity based on relevance.
4. Generates personalized cover letters.
5. Saves opportunities in a structured database.
6. Notifies users only about high-quality matches.

This significantly reduces manual effort while improving the quality and relevance of job applications.

---

## 🚀 Features

- Automated LinkedIn job discovery
- Resume-based job matching
- AI-powered compatibility scoring
- Personalized cover letter generation
- Google Sheets integration for tracking
- Slack notifications for qualified opportunities
- Scheduled daily execution
- End-to-end workflow automation with n8n

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| n8n | Workflow Automation |
| Google Gemini | AI Matching & Cover Letter Generation |
| JavaScript | Dynamic Search URL Generation |
| Google Drive | Resume Storage |
| Google Sheets | Job Tracking Database |
| LinkedIn | Job Source |
| Slack | Real-Time Notifications |

---

## ⚙️ Workflow

```text
Schedule Trigger
       │
       ▼
Download Resume from Google Drive
       │
       ▼
Extract Resume Content
       │
       ▼
Read Job Preferences from Google Sheets
       │
       ▼
Search LinkedIn Jobs
       │
       ▼
Extract Job Details
       │
       ▼
Google Gemini Analysis
       │
       ├── Generate Match Score
       └── Generate Cover Letter
       │
       ▼
Store Results in Google Sheets
       │
       ▼
Filter High-Scoring Jobs
       │
       ▼
Send Slack Notifications
```
---
## 📷 Workflow Screenshots

<img width="1240" height="657" alt="image" src="https://github.com/user-attachments/assets/44c51b49-fc3d-4bcc-852c-bbda66f4d329" />

---

## 📊 Key Outcomes

- Reduced manual job search effort by over 70%
- Automated resume-to-job matching
- Instant job opportunity notifications
- AI-generated cover letters for every application
- Centralized application tracking system
- Scalable architecture for multiple job categories

---

## 👨‍💻 Author

**Vansh Srivastava**

B.Tech – Computer Science & Engineering (Data Science)  
Raj Kumar Goel Institute of Technology, Ghaziabad
