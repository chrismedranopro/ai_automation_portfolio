# BrightPath Operations Hub — AI Operating System for Energy Efficiency Program Administrators
## A unified command center for lead pipeline, compliance tracking, AI-assisted estimating, and voice AI intake, built for a home energy efficiency contractor managing state utility-rebate program work.

🌐 **Live Demo:** https://brightpath-ops-hub-demo.vercel.app

---

## Project Status

This project was built as part of a client engagement for a home energy efficiency program administrator managing weatherization and HVAC upgrade projects funded through state utility rebate programs.

To protect client confidentiality, identifying details — business name, staff names, service area, and program name — have been replaced with placeholders throughout this demo. The interface, workflow design, and feature set reflect the operating system built for the engagement.

---

# Overview

BrightPath Operations Hub is an AI-powered operations platform designed to give a small energy efficiency contractor a single command center across the full project lifecycle — from lead intake through compliance-gated reimbursement.

The platform combines:

- Executive dashboard with AI-generated daily briefings
- Action Center — a unified, priority-ranked task queue
- Lead pipeline management
- AI-assisted estimate generation
- Compliance/reimbursement document tracking
- Voice AI missed-call recovery
- Subcontractor and work order coordination
- SOP and AI-agent status visibility

into one operational system.

---

# Why I Built This

Energy efficiency contractors sit at the intersection of field operations, compliance-heavy government/utility reimbursement programs, and homeowner-facing customer service — while typically running on spreadsheets, email, and disconnected point tools.

That creates a specific set of failure modes:

- Reimbursement dollars stuck behind missing compliance documents, discovered too late
- Missed calls after hours that represent real revenue, with no structured recovery process
- Estimating bottlenecked on a single person's availability
- No single view of which projects are actually at risk this week

BrightPath Operations Hub was designed as a practical response: surface what's at risk today, automate the mechanical parts of estimating and intake, and keep a human firmly in the loop for anything customer-facing or compliance-sensitive.

---

# Business Problem

Small energy efficiency contractors managing utility/state rebate program work face:

## Compliance-Gated Revenue

Reimbursement claims are only paid once every required document is uploaded and verified. A single missing form can hold up thousands of dollars with a hard deadline attached.

## After-Hours Missed Calls

Field crews and office staff can't answer every call. Emergency situations (e.g., a flooded basement) called in overnight need same-day triage, not a voicemail that gets checked Monday.

## Manual, Bottlenecked Estimating

Turning a completed site visit into a homeowner-ready estimate is manual, slow, and dependent on one estimator's bandwidth.

## Fragmented Operational Visibility

Owners can't easily answer "what's actually at risk this week" without manually cross-referencing several systems.

---

# Proposed Solution

An AI Operating System that connects field data collection, AI reasoning, and human approval into a single workflow:

```text
Field Site Visit (Fieldwire)
      ↓
Automated Webhook (n8n)
      ↓
AI Review / Estimate Draft (Claude)
      ↓
Human Review & Approval
      ↓
Operations Hub (single source of truth)
```

Every AI-generated output — estimates, compliance risk flags, missed-call summaries — is designed to land in front of a human for approval before it reaches a homeowner or a compliance submission.

---

# Core Features

---

## Executive Dashboard

An AI-generated daily briefing surfaces the handful of things that actually need owner attention today, instead of requiring a manual scan across systems.

### Highlights

- Natural-language daily briefing generated from live operational data
- Revenue-at-risk and reimbursement-at-risk summaries
- Cross-system activity feed (field, compliance, estimating, voice AI)

---

## Action Center

A unified, priority-ranked task queue that replaces "check five different places to find out what's urgent."

### Highlights

- Deadline-aware prioritization
- One-click resolution actions per task
- Consolidated view across compliance, estimating, and dispatch

---

## Lead & Project Pipeline

A kanban-style pipeline tracking every project from intake through closeout.

### Information Tracked

- Stage, risk status, and compliance percentage
- Reimbursement value and days-to-deadline
- Assigned owner

---

## AI-Assisted Estimate Generation

Site visit data flows automatically into an AI-drafted estimate, with a confidence score and a one-click human approval step before anything reaches a homeowner.

---

## Compliance & Reimbursement Tracking

Per-project compliance checklists tied to real program document requirements, with automatic risk flags when a deadline is approaching and documents are still missing.

---

## Voice AI Missed-Call Recovery

After-hours calls are captured, triaged, and summarized automatically, with emergency situations flagged for immediate human callback rather than waiting for a morning voicemail check.

---

## Subcontractor & Work Order Coordination

Automated work order dispatch and renewal reminders (insurance, licensing) for the subcontractor network, with escalation when confirmations don't come back in time.

---

## SOP & AI Agent Status

A living view of which standard operating procedures are current, which need updates as program requirements change, and the live health/success rate of each AI agent running in the system.

---

# Workflow Design Principles

> AI drafts, humans decide — especially anywhere the output reaches a homeowner or a compliance submission.

### Design Objectives

- Protect reimbursement revenue by surfacing compliance risk early
- Recover after-hours revenue opportunities that would otherwise be lost
- Remove manual bottlenecks from estimating without removing human judgment
- Give an owner a single, trustworthy view of operational risk

---

# Technology Stack

### Frontend

- HTML / CSS / JavaScript (self-contained single-page interface)

### AI & Automation

- Claude (estimate drafting, AI briefings, risk analysis)
- n8n (workflow orchestration, webhooks)
- Fieldwire (field data source)

### Deployment

- Vercel

---

# Key Takeaways

This project demonstrates my approach to designing AI Operating Systems for operationally complex, compliance-heavy service businesses: start from where revenue actually gets stuck, keep humans in control of anything customer- or compliance-facing, and use AI to remove the mechanical bottlenecks in between.

---

# Links

🌐 Live Demo: https://brightpath-ops-hub-demo.vercel.app

---

## Project Classification

**Type:** AI Operating System / Operations Platform
**Industry:** Home Energy Efficiency & Utility Rebate Programs
**Focus Areas:** Workflow Automation, AI-Assisted Estimating, Compliance Tracking, Voice AI, Operational Intelligence, Executive Dashboards
