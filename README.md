# PVFlow

> PVflow is a newly developed pharmacovigilance workflow management platform designed to replace spreadsheet-based tracking of Individual Case Safety Reports (ICSRs) with structured workflows, automated validation, and audit-ready case management.

---

## Overview

Many pharmacovigilance teams use spreadsheets to monitor case progress alongside dedicated safety databases. As case volume grows, spreadsheet-based workflows become difficult to maintain, audit, and scale.

PVFlow is an open-source learning project that explores how modern software engineering principles—relational databases, workflow automation, authentication, and audit logging—can improve operational case tracking while remaining independent of commercial safety databases.

---

## Problem Statement

Spreadsheet-based case tracking introduces several operational challenges:

- Manual workflow tracking across multiple review stages
- No reliable audit trail for edits and status changes
- Manual deadline calculations based on Day 0
- Limited validation of case data
- Difficult reporting and filtering as case volume increases

PVFlow aims to address these challenges through structured data management and configurable workflow automation.

---

## Planned Features

### Case Management

- Create and manage ICSR records
- Case lifecycle tracking
- Search and filtering
- Client-specific product validation

### Workflow Management

- Book-in
- Data Entry
- Medical Review
- Quality Review
- Submission
- Case Closure

### Compliance Features

- Audit log
- User authentication
- Role-based access control
- Configurable reporting deadlines
- Edit approval workflow

### Dashboard

- Open cases
- Due today
- Overdue cases
- Cases by client
- Cases by reviewer
- Workflow analytics

---

## Technology Stack

| Layer | Technology |
|--------|------------|
| Backend | Python, FastAPI |
| Database | PostgreSQL (SQLite during development) |
| Frontend | React |
| UI/UX | Figma |
| Version Control | Git & GitHub |

---

## Project Structure

```text
pvflow/
│
├── docs/
├── backend/
├── frontend/
├── database/
├── tests/
└── assets/
```

---

## Development Roadmap

- [x] Project planning
- [ ] Software requirements
- [ ] Database schema
- [ ] REST API
- [ ] Authentication
- [ ] Frontend
- [ ] Dashboard
- [ ] Testing
- [ ] Deployment

---

## Disclaimer

PVFlow is an educational and portfolio project inspired by general pharmacovigilance workflows. It is not intended to replace validated pharmacovigilance safety databases or reproduce proprietary commercial systems. No real patient data or confidential organizational information is used.

---

## Author

Developed as a software engineering and healthcare informatics portfolio project focused on applying database design, backend development, and workflow automation to pharmacovigilance operations.
