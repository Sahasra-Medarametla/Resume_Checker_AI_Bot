**AI Resume Evaluator Agent**

**Introduction**

The AI Resume Evaluator Agent is an automation system that analyzes resumes automatically and generates a structured evaluation report.

The system uses AI, automation tools, and messaging platforms to evaluate a resume and send the results directly to the user without manual review.

Users simply send a Google Docs resume link through Telegram, and the AI agent evaluates the resume and delivers a detailed report via email.

**What the System Does**

-The AI Resume Evaluator Agent performs the following tasks:

-Accepts a resume link from Telegram

-Fetches and extracts the resume content

-Uses an AI model to analyze the resume

-Generates a structured evaluation report

-Sends the report via email

-Notifies the user on Telegram

**Tools & Technologies Used**

Make.com – Automation platform

AI Provider (GPT-based model) – Resume evaluation

Telegram Bot (BotFather) – User interaction

Google Docs API – Resume content retrieval

Text Parser – Extract resume data

Gmail Integration – Sends evaluation report

**Workflow Steps**

1. Telegram Input

The user sends a Google Docs resume link through the Telegram bot.

2. Resume Content Extraction

The system retrieves the resume from Google Docs and extracts the text content.

3. AI Resume Evaluation

The AI agent analyzes the resume and evaluates key sections such as:

-Technical Skills

-Work Experience

-Projects

-Leadership & Achievements

-Overall Profile Strength

4. Generate Evaluation Report

The AI generates a structured report containing:

Section-wise scores

Strengths and weaknesses

Hiring recommendation

Suggestions for improvement

5. Send Email Report

The report is formatted as an HTML email and sent to the user via Gmail.

6. Telegram Notification

Once the report is sent, the user receives a confirmation message on Telegram.

**Automation Architecture**

Telegram Bot

↓

Capture Resume Link

↓

Fetch Resume from Google Docs

↓

Extract Resume Content

↓

AI Resume Evaluation

↓

Generate Report

↓

Send Email via Gmail

↓

Notify User on Telegram

**Output**

The system provides:

-Resume evaluation score

-Section-wise feedback

-Improvement recommendations

-Hiring decision insights

**Key Benefits**

-Automated resume analysis

-Fast and structured evaluation

-Professional recruiter-style report

-Easy interaction through Telegram

-Saves time in manual resume screening

**Future Improvements**

-Add PDF resume support

-Include ATS compatibility analysis

-Provide job-specific resume suggestions

-Add resume ranking for multiple candidates
