🏗️ Construction Quotation Automation using n8n & AI

Overview

An AI-powered construction quotation workflow built with n8n. It collects customer requirements through a WhatsApp-based assistant and generates a preliminary construction quotation PDF.

Key Features

- Conversational collection of customer and project details
- Plot size, built-up area, construction quality, budget, and timeline capture
- Customer confirmation before quotation generation
- Google Sheets integration for storing and retrieving information
- Automated HTML-to-PDF quotation generation
- Google Drive file upload and sharing
- WhatsApp delivery of the quotation link

Workflow

Webhook → AI Agent → JavaScript Processing → Validation → Google Sheets → HTML Template → PDF Generation → Google Drive → WhatsApp

Technologies

- n8n
- AI Agent and Google Gemini
- Google Sheets
- HTML and JavaScript
- PDF generation
- Google Drive
- Twilio WhatsApp integration

Project Status

Demo workflow built and tested with sample construction project details. Production use requires valid credentials, verified pricing rules, and end-to-end testing.

Important Note

The generated quotation is a preliminary estimate. Final pricing should be confirmed after site inspection and detailed requirements review.
