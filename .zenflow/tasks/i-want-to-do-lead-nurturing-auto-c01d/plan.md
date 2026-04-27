# Lead Nurturing Automation

## Overview
Build a self-contained web app (single HTML file) for lead nurturing. Users paste raw n8n lead data, the app parses it, enriches with derived emails and decision maker roles, allows category tagging, and displays in a CRM-like table with export and email template features.

### [x] Step 1: Build the Lead Nurturing Web App
- Paste area for raw n8n lead data
- Parser for the n8n format (Place ID, name, address, phone, website, rating, reviews, type, coords, city, country, query, timestamp)
- Email derivation from website domains (contact@, info@, direction@, formation@)
- Decision maker role suggestions (Directeur de formation, Responsable pédagogique, etc.)
- Category selection: BTS/Bachelor, MBA/Masters, Agile Programs, AI Programs, Jury for Exams, Last Minute Teacher Replacement
- Service matching from Linguistic Communication offerings
- CRM-like table view with columns: Name, Email, Phone, Website, Type, Rating, Lead Status, Category, Decision Maker
- CSV export
- Email template generation for outreach per category
- Clean minimal UI similar to the Webile Uploader style
- Deploy-ready as single HTML file for Hostinger

### [x] Step 2: Test and Verify
- Test with sample lead data from the task description
- Verify parsing, enrichment, table display, export, and email templates
- Browser test via dev server
