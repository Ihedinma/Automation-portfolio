# AI Certificate Maker – Automated Google Slides to Webflow Pipeline

A Make.com automation that generates personalized course certificates, converts them to JPG, uploads them to Webflow, and writes the final asset link back to Google Sheets.

## Features
- Watches Google Sheets for new certificate triggers
- Generates certificates from a Google Slides template
- Dynamically fills name, course title, date
- Converts PDF → JPG using iLovePDF API
- Creates Webflow asset via API + uploads to S3 endpoint
- Updates the Google Sheet row with the asset link
- Cleans up temporary Google Drive files

## Tech Stack
- Make.com
- Google Sheets / Slides / Drive
- iLovePDF API
- Webflow Assets API

## Impact
- Fully automated certificate pipeline
- Eliminated manual design/export work
- Improved delivery speed and consistency
