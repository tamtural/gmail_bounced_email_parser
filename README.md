# Gmail Bounced Email Parser

This Python script connects to your Gmail inbox, scans unread messages labeled "Bounced", extracts failed recipient email addresses from bounce notifications, and exports them into Excel files in batch format.


## Features

- OAuth 2.0 Gmail API authentication  
- Searches unread emails by label  
- Regex-powered extraction of bounced addresses  
- Batch processing with pagination  
- Automatically marks emails as read after parsing  
- Outputs clean Excel files (`.xlsx`) by batch


## Dependencies

Install these packages before running the script:

```bash
pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client pandas openpyxl
