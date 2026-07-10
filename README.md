# ai-news-email-agent
# AI News Email Agent

An AI-powered automation workflow built with **n8n** that automatically fetches the latest AI news, summarizes it using Google Gemini, and emails the results.

## Features

- Fetches AI news from an RSS feed
- Summarizes articles using Google Gemini
- Generates an email summary
- Sends the summary via Gmail
- Runs automatically on a schedule

## Technologies

- n8n
- Google Gemini
- Gmail OAuth
- RSS Feed

## Workflow

Schedule Trigger
↓
RSS Feed
↓
Aggregate Articles
↓
Google Gemini
↓
Send Email

## Setup

1. Import `workflow.json` into n8n.
2. Configure your own Google Gemini API credentials.
3. Configure your Gmail OAuth credentials.
4. Replace the recipient email.
5. Activate the workflow.

## License

MIT.
