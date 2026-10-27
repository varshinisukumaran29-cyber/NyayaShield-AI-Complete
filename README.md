# NyayaShield AI
### Automated Detection and Redaction of Personally Identifiable Information in Indian Legal Judgments

NyayaShield AI is an AI-assisted legal document privacy protection system designed to identify, assess, and redact Personally Identifiable Information (PII) from Indian legal judgments.

## Features
- Upload and extract text from legal documents
- Detect personal names, residential addresses, phone numbers, emails, and other sensitive identifiers
- Context-aware PII detection using regex, legal patterns, and optional NLP
- Privacy risk assessment
- Pseudonymization and document redaction
- Residual PII leakage verification
- Sanitized text export
- Document review dashboard

## Technology Stack
**Frontend:** React, TypeScript, Vite, Tailwind CSS

**Backend:** Python, FastAPI, NLP, Regular Expressions

**Version Control:** Git and GitHub

## Project Structure
```text
NyayaShield-AI-Complete/
├── frontend/
│   ├── src/
│   ├── package.json
│   └── vite.config.ts
├── backend/
│   ├── app/
│   ├── tests/
│   └── requirements.txt
└── README.md
```

## How to Run

### Backend
```bash
cd backend
pip install -r requirements.txt
python -m uvicorn app.main:app --host 127.0.0.1 --port 8000
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

The frontend must be configured to use the running backend API.

## Project Repositories

This repository contains both the frontend and backend source code.

## Important Note
PII detection and residual verification are automated processes and may miss sensitive information. Human review is required before publishing redacted legal documents.

## Project Status
Source code uploaded to GitHub. Local backend functionality has been tested using a fictional legal judgment. Complete frontend-to-backend integration and deployment require further verification.
