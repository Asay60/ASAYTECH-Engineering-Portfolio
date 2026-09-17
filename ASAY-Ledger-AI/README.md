# ASAY Ledger AI — AI-Assisted Accounting Operations

ASAY Ledger AI is a multi-tenant operations platform for accounting offices (SMMM) and their clients. It combines document intake, asynchronous OCR, AI-assisted review, risk prioritization and follow-up workflows while keeping the accountant in control of final decisions.

![ASAY Ledger AI architecture](assets/architecture.jpg)

## What It Solves
Accounting offices repeatedly chase clients for missing documents, review uploads manually and decide who needs follow-up. ASAY Ledger AI turns that work into a managed workflow instead of replacing the core ERP/general ledger.

## Core Pipeline
`Client / Accounting Office → Document Intake → Async OCR → AI Review → Risk Classification → Follow-up Queue → Accountant Review → Communication History`

Supporting layers include Celery workers, PostgreSQL + Redis, a Next.js dashboard, document matching, reminder automation and an operational status panel.

## Core Capabilities
- Document intake and asynchronous OCR
- AI-assisted document classification and risk review
- Prioritized follow-up queue
- Drafted reminders and communication history
- Multi-tenant company-scoped data access
- Provider boundaries for OCR and messaging
- Human accountant review and approval

## Engineering Stack
Python/FastAPI · async SQLAlchemy · PostgreSQL · Celery · Redis · Next.js · TypeScript · Playwright · Docker Compose

## Verified CI Evidence
Verified GitHub Actions CI includes:
- Backend tests: **SUCCESS**
- Frontend typecheck: **SUCCESS**
- Frontend build: **SUCCESS**
- Playwright frontend smoke tests: **SUCCESS**

## My Role
Product architecture, full-stack system design, AI workflow design, provider boundaries, multi-tenant security, testing strategy and deployment engineering.

## Source Availability
Production source remains private. This case study exposes sanitized architecture and verified CI evidence without publishing production source, credentials or customer data.
