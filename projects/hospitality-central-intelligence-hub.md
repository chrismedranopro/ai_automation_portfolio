# Central Intelligence Hub — AI Operating System for Hospitality Venues
## A single operational command center unifying revenue, food & beverage, accommodation, functions, guest experience, AI reception, and workforce cost intelligence for a multi-revenue-stream regional hotel.

🌐 **Live Demo:** https://central-intelligence-hub-demo.vercel.app

---

## Project Status

This project was built as part of a client engagement for a regional hospitality venue operating accommodation, a restaurant and bar, and a functions/events business under one roof.

To protect client confidentiality, identifying details — venue name, location, and staff names — have been replaced with placeholders throughout this demo, and all figures shown are representative sample data. The interface, workflow design, and feature set reflect the operating system built for the engagement.

---

# Overview

Central Intelligence Hub is an AI-powered operations platform designed to give a hospitality operator one live view across every revenue stream and cost centre in the venue — replacing the nightly ritual of pulling separate reports from the POS, the property management system, the functions diary, the rostering tool, and the phone system.

The platform combines:

- Executive overview with an AI-generated morning briefing
- Revenue intelligence across all streams (MTD, trend, mix)
- Food & beverage performance (covers, turnover, spend per cover)
- Accommodation intelligence (occupancy, ADR, RevPAR, length of stay)
- Functions & events pipeline and revenue forecasting
- Guest intelligence (satisfaction, NPS, repeat rate, VIP arrivals)
- AI Receptionist performance and after-hours revenue recovery
- Workforce intelligence (labour cost %, utilisation, overtime)
- A consolidated Alerts Center with AI-generated insights

into one operational system.

---

# Why I Built This

A regional hotel is really three or four businesses sharing a building, a roster, and a P&L. Accommodation, F&B, and functions each have their own systems, their own rhythms, and their own definition of a good day — and almost none of them talk to each other.

That creates a specific set of failure modes:

- The operator only learns a week was bad after the week is over
- Labour cost drifts above target for days before anyone notices
- Function enquiries sit in an inbox while the pipeline quietly ages
- After-hours calls — booking enquiries with real revenue attached — go to voicemail
- "How did we actually do?" takes an hour of manual report-pulling to answer

Central Intelligence Hub was designed as a practical response: put every number an operator needs on one screen, refresh it live, and let AI do the interpretation — flagging what moved, what's off-target, and what needs a decision today.

---

# Business Problem

Multi-revenue-stream hospitality venues face:

## Fragmented Operational Reporting

Revenue, occupancy, covers, labour, and function bookings each live in a different system. Building a single picture of the day is manual, slow, and usually happens too late to act on.

## Labour Cost Blind Spots

Labour is the largest controllable cost in hospitality and it moves daily. Without live visibility against target, overruns are discovered in the monthly P&L rather than on the shift they happened.

## Lost After-Hours Revenue

Reception isn't staffed around the clock. Booking enquiries, function enquiries, and accommodation questions arriving outside business hours convert far worse than the same enquiry answered live.

## An Ageing Functions Pipeline

Events are the highest-margin revenue stream and the slowest to close. Enquiries that aren't actively worked decay silently, with no system surfacing which leads are going cold.

## Reactive Rather Than Predictive Management

Operators spend their time reconstructing what already happened instead of acting on what's about to.

---

# Proposed Solution

An AI Operating System that consolidates every venue data source into one live operational picture, with AI handling both the interpretation layer and the after-hours front door:

```text
Venue Systems (POS · PMS · Functions Diary · Rostering · Phone)
      ↓
Workflow Orchestration (n8n)
      ↓
Unified Operational Data Layer
      ↓
AI Analysis Layer (briefings · variance detection · alerts)
      ↓
Central Intelligence Hub (single source of truth)
      ↓
Operator Decision
```

AI is used for two distinct jobs: interpreting operational data into plain-language insight, and handling inbound calls when a human can't. Every commercial decision — pricing, rostering, quoting a function — stays with the operator.

---

# Core Features

---

## Executive Overview

A morning briefing that opens with what actually matters: the eight headline metrics for the venue and a natural-language summary of what changed overnight.

### Metrics Surfaced

- Revenue today and revenue this week
- Occupancy rate and average spend per guest
- Labour cost % against target
- Open function leads
- AI calls handled
- Guest satisfaction

### Highlights

- AI-generated daily briefing written from live venue data
- Variance flagged against target, not just reported
- Cross-department snapshot in a single screen

---

## Revenue Intelligence

Month-to-date analysis across every revenue stream, showing not just totals but the mix — how much of the month came from rooms, from F&B, and from functions.

### Information Tracked

- MTD revenue, with trend
- F&B revenue MTD
- Accommodation revenue MTD
- Functions revenue MTD

---

## Food & Beverage Operations

Restaurant, bar, and kitchen performance in the terms a venue manager actually uses.

### Information Tracked

- Covers today
- Table turnover
- Average spend per cover
- Bar revenue today

---

## Accommodation Intelligence

Standard hotel yield metrics, live, alongside room status across the property.

### Information Tracked

- Occupancy tonight
- ADR (average daily rate)
- RevPAR (revenue per available room)
- Average length of stay

---

## Functions & Events

A pipeline view of the venue's highest-margin revenue stream, from initial enquiry through confirmed booking, with forward revenue forecasting.

### Information Tracked

- Active pipeline value
- Confirmed events MTD
- Average event value
- Events this month, by status (confirmed / tentative / enquiry)

---

## Guest Intelligence

Satisfaction and loyalty tracked as operational metrics rather than an annual survey.

### Information Tracked

- Overall satisfaction
- NPS score
- Repeat guest rate
- VIP guests in-house tonight

---

## AI Receptionist

An AI voice agent that answers the phone when reception can't — handling booking enquiries, qualifying function leads, and escalating anything that needs a person.

### Information Tracked

- Calls this month, and share handled by AI
- Human transfers
- After-hours calls saved
- Qualified leads generated by AI
- Booking enquiries captured
- Average call duration and caller satisfaction

### Highlights

- After-hours enquiries captured as structured leads instead of voicemail
- Clean handoff to a human for anything outside the AI's scope
- Recovered revenue measured explicitly, not assumed

---

## Workforce Intelligence

Live labour cost visibility so overruns are caught on the shift, not in the monthly accounts.

### Information Tracked

- Labour cost % against target
- Staff on shift today
- Overtime this week
- Staff utilisation

---

## Alerts Center

A single consolidated queue of everything across the venue that needs attention, combining threshold-based operational alerts with AI-generated insight.

### Highlights

- One place to check instead of nine dashboards
- AI-generated insights alongside rule-based alerts
- Live badge count so nothing sits unseen

---

# Workflow Design Principles

> AI interprets and answers the phone. The operator still runs the venue.

### Design Objectives

- Compress "how are we tracking?" from an hour of report-pulling to a glance
- Make labour cost a live number, not a monthly post-mortem
- Recover after-hours revenue that would otherwise go to voicemail
- Keep the functions pipeline visible so high-margin leads don't age out
- Shift the operator's attention from reconstructing the past to acting on the present

---

# Technology Stack

### Frontend

- HTML / CSS / JavaScript (self-contained single-page interface)
- Tailwind CSS
- Chart.js (revenue, occupancy, and performance visualisation)

### AI & Automation

- Claude (daily briefings, variance analysis, operational insights)
- Voice AI (after-hours reception, lead qualification, booking intake)
- n8n (workflow orchestration, webhooks, system integration)

### Deployment

- Vercel

---

# Key Takeaways

This project demonstrates my approach to designing AI Operating Systems for venues running several businesses at once: unify the data before adding intelligence, express every metric in the operator's own vocabulary, and use AI where it genuinely removes work — interpreting numbers and covering the phone — while leaving commercial judgement with the people accountable for it.

---

# Links

🌐 Live Demo: https://central-intelligence-hub-demo.vercel.app

💻 Demo Repository: https://github.com/chrismedranopro/central-intelligence-hub-demo

---

## Project Classification

**Type:** AI Operating System / Operations Intelligence Platform
**Industry:** Hospitality — Hotels, Venues & Functions
**Focus Areas:** Executive Dashboards, Revenue Intelligence, Voice AI, Workforce Analytics, Operational Visibility, Business Reporting
