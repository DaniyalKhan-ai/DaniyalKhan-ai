 # 🚀 AI LinkedIn Auto-Posting Automation with n8n

An AI-powered LinkedIn automation workflow built with **n8n** that automatically creates and publishes LinkedIn posts on a scheduled basis.

## ✨ What This Workflow Does

This automation takes pending content ideas from **Google Sheets**, finds the related image from **Google Drive**, generates a professional LinkedIn caption using **AI**, publishes the post on **LinkedIn**, and finally updates the Google Sheet to mark the content as **Posted**.

## 🔄 Workflow
### 📸 Workflow Preview

![LinkedIn Workflow](LinkedIn%20Workflow%20Screenshot.jpg)

```text
Schedule Trigger
       ↓
Google Sheets
       ↓
Google Drive
       ↓
Download Image
       ↓
AI Agent
       ↓
Merge
       ↓
LinkedIn
       ↓
Google Sheets
🤖 AI Content Generation
The AI Agent automatically creates a LinkedIn post based on the workflow name and description.
It generates:
Professional LinkedIn content
Problem and solution explanation
Workflow explanation
AI & n8n usage
Business benefits
Relevant emojis
5–8 relevant hashtags
The AI is instructed not to invent features that are not included in the workflow description.
⚙️ Technologies Used
n8n — Workflow automation
OpenAI — AI-powered caption generation
Google Sheets — Content queue and status tracking
Google Drive — Image storage
LinkedIn — Automatic post publishing
⏰ Automatic Scheduling
The workflow is configured to run automatically:
Tuesday — 5 PM
Thursday — 5 PM
Saturday — 5 PM
📊 Google Sheets Queue
Each content row contains information such as:
Workflow
Description Topic
Image File Name
Status
Posted Date
The automation picks the first pending item, publishes it, and then updates its status to Posted.
🔁 Fully Automated Process
Once the content and image are added to the Google Sheet and Google Drive, the rest of the process happens automatically:
Content → AI Caption → Image + Caption → LinkedIn → Status Update
🔐 Setup
Import the workflow JSON into n8n.
Connect your Google Sheets credentials.
Connect your Google Drive credentials.
Connect your OpenAI credentials.
Connect your LinkedIn credentials.
Configure your Google Sheet.
Upload the required images to Google Drive.
Configure the schedule.
Activate the workflow.
⚠️ Make sure to replace all credentials and personal IDs with your own accounts before running the workflow.
📁 Workflow File
The n8n workflow JSON is available here:
LinkedIn Workflow Automation.json
🎯 Use Case
This automation is useful for developers, creators, agencies, and businesses that want to maintain a consistent LinkedIn presence without manually creating and publishing every post.
⭐ If you find this workflow useful, feel free to star the repository!
