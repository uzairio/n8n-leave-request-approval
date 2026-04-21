# Leave Request Approval — n8n Workflow

Automated staff leave request system built in n8n.

## What it does
- Employee submits a Google Form
- Workflow checks for date clashes with approved leave
- If clash → employee notified instantly
- If no clash → manager receives approve/reject email
- Manager clicks link → sheet updated, employee notified

## Tools used
- n8n
- Google Forms
- Google Sheets
- Gmail

## Workflow preview
![Workflow](workflow-preview.png)

## How to use
1. Import `leave-request-approval.json` into n8n
2. Connect your Google and Gmail credentials
3. Update the sheet ID and email addresses
4. Activate the workflow
