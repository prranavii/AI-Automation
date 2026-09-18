# AI-Automation

automation built using Make.com.

## Workflow

Airtable
   ↓
Router
   ↓
Gmail
   ↓
Airtable
   ↓
Slack

## What it does

The automation monitors Airtable records and processes them through
different workflow paths.

### Email path
- Reads lead information from Airtable
- Checks the workflow condition
- Sends a personalized Gmail message
- Updates the Airtable record

### Notification path
- Processes information using Text Parser
- Extracts the required data
- Sends a notification to Slack

## What I learned

- Triggers and actions
- Data mapping
- Routers and filters
- Data transformation
- API integrations
- Authentication
- Error handling and debugging
- Designing end-to-end workflows

## Tools

- Make.com
- Airtable
- Gmail
- Slack
- Text Parser

## Blueprint

The `blueprint/` folder contains the exported Make.com
scenario blueprint.

To use it, import the JSON into Make.com and configure
your own application connections.
