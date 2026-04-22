# HR Interview Automation Workflow (n8n)

## Overview

This n8n workflow automates the HR interview processing pipeline. It processes incoming candidate emails, extracts and analyzes candidate data, structures the information, checks interview scheduling availability, updates connected systems, and sends automated email responses.

The workflow reduces manual HR effort, improves processing speed, and standardizes recruitment operations.

## Features

- Automated email monitoring for job applications
- Extraction of candidate information from emails and attachments
- AI-based resume/CV analysis
- Structured candidate data generation
- Interview scheduling validation
- Integration with external systems (ATS, databases, spreadsheets, etc.)
- Automated email responses based on workflow results

## Workflow Steps

1. Email Trigger  
   The workflow starts when a new application email is received.

2. Data Extraction  
   Email content and attachments are extracted for processing.

3. AI Processing  
   Candidate resume/CV is analyzed to extract:
   - Name  
   - Contact details  
   - Skills  
   - Experience  
   - Education  

4. Data Structuring  
   Extracted data is converted into a structured format for storage and processing.

5. Scheduling Check  
   The system checks availability for interview scheduling based on defined rules or calendar integration.

6. System Update  
   Candidate data is stored or updated in external systems such as ATS, CRM, or databases.

7. Email Response  
   Automated email responses are sent based on the result:
   - Application received confirmation  
   - Interview invitation  
   - Rejection or follow-up message  

## Requirements

- n8n instance (cloud or self-hosted)
- Email integration (IMAP/Gmail/SMTP)
- AI API for document parsing
- Optional integrations:
  - Google Sheets / Airtable / Database
  - Google Calendar or similar scheduling tool
  - ATS system

## Output

- Structured candidate profiles
- Updated HR/ATS records
- Scheduled interview slots (if applicable)
- Automated email communication logs

## Benefits

- Reduces manual HR workload
- Speeds up candidate response time
- Standardizes candidate data processing
- Reduces human error
- Scales recruitment operations efficiently
