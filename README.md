# LinkedIn Job Application Automation with OpenAI & n8n

## Overview
This project automates the job application process using n8n and OpenAI's GPT. It extracts job postings from LinkedIn RSS feeds, evaluates job fit against your resume, generates personalized cover letters, recommends resume modifications, and logs all details in a Google Sheet.

## Features
- Extracts job postings from LinkedIn RSS feeds.
- Uses GPT to:
  - Compare resume with job description (score 1-5).
  - Suggest modifications to the resume.
  - Generate personalized cover letters.
- Collects all details (Job Title, JD, Link, Company, Date, Rating, Cover Letter) in a Google Sheet.
- Helps target high-fit jobs efficiently.

## Tools & Technologies
- n8n (workflow automation)
- OpenAI GPT (resume analysis & cover letter generation)
- Google Drive / Google Sheets API
- LinkedIn RSS feeds

## Setup Instructions
1. Import `workflow.n8n` in your n8n instance.
2. Configure your OpenAI API token.
3. Connect Google Sheets for logging job data.
4. Run the workflow.

## Results
- Automated scoring and recommendations to improve job targeting.
- Saves time by centralizing job application tasks.
