# Lead Nurturing Automation

**Linguistic Communication** — Lead nurturing tool for managing and enriching CRM leads from n8n workflows.

**Live app:** [linguistic-communication.com/automation/lead-nurturing.html](https://linguistic-communication.com/automation/lead-nurturing.html)

## Features

### Import & Parse
- Paste raw lead data from n8n Google Maps workflows
- Auto-parse Place ID, name, address, phone, website, rating, reviews, school type, coordinates, city, country

### Lead Enrichment
- **Email derivation** from website domains (contact@, info@, direction@, formation@)
- **Decision maker suggestions** based on school type (Directeur de formation, Responsable pédagogique, Proviseur, etc.)
- **Category matching** — auto-assigns relevant service categories per lead

### CRM Table View
- Search and filter by name, email, city, status, or category
- Sortable columns: Name, Email, Phone, Website, Type, Rating, Status, Categories, Decision Maker
- Select leads for bulk email generation
- Pagination (25 per page)

### Email Templates (HubSpot-ready)
- **6 template categories** with your real HubSpot HTML templates:
  - BTS / Bachelor (3-step sequence)
  - MBA / Masters (3-step sequence)
  - AI Agents & Automation (3-step sequence)
  - Jury pour Examens (single email)
  - Remplacement Urgent (single email)
  - TOEIC Preparation (single email)
- **Inline HTML editor** — preview or edit HTML directly
- **Variable substitution** — `{{ contact.firstname }}` and `{{ contact.company }}`
- **LocalStorage persistence** — edits survive page reloads
- Copy HTML or plain text with one click

### Export
- **CSV export** with all enriched data
- **HubSpot-ready CSV** for direct CRM import

## Target Categories

| Category | Description |
|----------|-------------|
| BTS / Bachelor | BTS SIO, NDRC, CG, Communication, Bachelor programs |
| MBA / Masters | IT Project Management, Cloud, Cybersecurity, AI, Strategy |
| Agile Programs | SCRUM, Kanban, DevOps, Lean Startup, Design Thinking |
| AI Programs | AI, Machine Learning, GenAI, Agents IA, Prompt Engineering |
| Jury for Exams | Professional jury members for BTS, Bachelor, Master exams |
| Last Minute Replacement | Express teacher substitution within 24-48h |
| TOEIC Preparation | TOEIC prep and administration for students |

## Deployment

Auto-deployed to Hostinger via GitHub Actions on push to `main`.

## Tech Stack

Single HTML file — no dependencies, no build step. Uses vanilla JavaScript and CSS.

---

**Linguistic Communication** — [linguistic-communication.com](https://linguistic-communication.com)
