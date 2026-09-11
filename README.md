# AI-Powered Social Media Automation with n8n

An AI-powered workflow that uses **n8n, Google Sheets, Google Gemini, and LinkedIn** to automatically generate and publish social media content.

## Workflow

```text
Google Sheets Trigger
        ↓
Basic LLM Chain
        ↓
Basic LLM Chain
        ↓
LinkedIn Create a Post
```

## How It Works

1. An article URL is added to Google Sheets.
2. The workflow detects the new or updated row.
3. Google Gemini processes the content and generates a social media post.
4. The generated post is automatically published to LinkedIn.

## Technologies Used

- n8n
- Google Sheets
- Google Gemini
- LinkedIn

## Setup

1. Import the workflow JSON into n8n.
2. Configure your Google Sheets, Gemini, and LinkedIn credentials.
3. Select the required Google Sheet.
4. Activate the workflow.

> API keys and credentials are not included in this repository.

## Files

- `Chandu social media automation.json` — n8n workflow

## Author

**Chandu Sri Nellepalli**
