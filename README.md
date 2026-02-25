Email Summary Agent (N8N + Google Gemini AI)
Overview
  This N8N workflow is an AI-powered email summarizer. It automatically fetches recent emails from your Gmail inbox, summarizes them using the Google Gemini Chat Model (AI), and drafts a summarized report back to your Gmail—all fully automated!

Features
  Scheduled Automation: Runs on a schedule to keep you updated automatically.

  Fetches Recent Emails: Retrieves all emails received in the past 24 hours.

  AI-Powered Summarization: Uses Google Gemini AI to generate concise summaries of your email content.

  Aggregates Results: Collects and organizes the summaries for clarity.

  Automated Drafting: Generates a summary email draft in Gmail for your review.

Workflow Structure
  Schedule Trigger: Determines when the workflow runs (e.g., daily).

  Get many messages: Collects emails from Gmail (last 24 hours).

  Aggregate: Combines email data for summarization.

  Google Gemini Chat Model: Calls Gemini AI to summarize the collected messages.

  Email Summarizing Agent: Handles the interaction with the AI and processes the summaries.

  Drafting all Summarized Data: Creates a draft email with all summarized content in Gmail.

Prerequisites
  N8N installed (self-hosted or cloud)

  Gmail account (connected in N8N)

  Google Gemini AI API key

  Basic familiarity with N8N workflows

Setup Instructions
Import Workflow:

  Download and import the workflow JSON file into your N8N instance.

Connect Gmail:

  Configure the Gmail node with your account credentials in N8N.

Insert Gemini API Key:

  Set up the Gemini AI node with your API key from Google AI Studio.

Schedule the Trigger:

  Adjust the schedule as needed (default: every 24 hours).

Run Workflow:

Test and activate the workflow. Review summarized email drafts in your Gmail.
