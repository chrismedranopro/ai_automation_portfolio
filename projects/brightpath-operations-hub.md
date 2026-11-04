# BrightPath Operations Hub — Contractor Operations & AI Enablement

**Completed and deployed client implementation · Energy-efficiency contracting · Public-facing project alias**

[View the illustrative demo](https://brightpath-ops-hub-demo.vercel.app)

> **Confidentiality note:** BrightPath is a portfolio alias for a real client engagement. The demo is a separate, sanitized illustration, not a public connection to the client's production environment. Client identity, records, credentials, pricing, and proprietary implementation details are intentionally omitted. Features visible in the demo should not be interpreted as the production scope.

## At a glance

I designed and delivered an operations foundation for a US residential energy-efficiency contractor. The engagement connected homeowner intake, lead review, project visibility, compliance tracking, and AI-assisted estimate preparation, while keeping staff responsible for consequential decisions.

**Delivery status:** Phase 1 implementation delivered and operating in production; staff training completed. This is client work, not a speculative concept or an uncommissioned prototype.

## The operational challenge

Contractor teams handling energy-efficiency rebate work often coordinate across email, field tools, document storage, spreadsheets, and program portals. Disconnected handoffs make it difficult to prioritize new enquiries, see missing paperwork, and prepare consistent estimates.

The objective was not to replace every tool. It was to create a practical operating layer that made existing workflows easier to follow, monitor, and maintain.

## What I delivered

### 1. Homeowner landing page and intake

- Built a dedicated energy-efficiency landing page and homeowner intake experience.
- Used custom HTML within WordPress, hosted on Bluehost, with WPForms for structured submissions.
- Configured related domain/subdomain settings through Squarespace.
- Designed the intake as the customer-facing entry point to the wider operational workflow.

### 2. Centralized Operations Hub

- Delivered a staff-facing application for tracking leads, projects, operational priorities, compliance, and estimating work.
- Created clearer visibility into ownership, status, and tasks requiring staff attention.

### 3. Lead pipeline and AI-assisted qualification

- Connected incoming enquiries to a structured lead workflow.
- Supported review of relevant documentation, service-area suitability, and program eligibility.
- Kept AI recommendations advisory, with staff retaining responsibility for qualification decisions.

### 4. Compliance tracking

- Organized project document requirements and status tracking.
- Supported staff visibility into missing items, deadlines, and follow-up work.

### 5. AI-assisted estimating

- Designed workflows to organize field information and prepare estimate drafts for review.
- Preserved estimator and authorized staff approval before homeowner-facing communication.
- Integrated the estimating process into the broader operational workflow rather than treating AI output as an automatic final answer.

### 6. Automation, training, and handoff

- Implemented workflow automation across intake, coordination, document processing, and estimating.
- Delivered staff guidance and training as part of the implementation.
- Built around existing client tools where appropriate, with monitoring and human-control safeguards.

## High-level architecture

```text
Homeowner enquiry / existing intake channels
                    ↓
       Structured lead workflow
                    ↓
        Staff qualification review
                    ↓
      Project and field coordination
                    ↓
       Document / compliance tracking
                    ↓
       AI-assisted estimate drafting
                    ↓
        Human review and approval
                    ↓
       Homeowner communication
```

This is a conceptual overview, not a reproduction of the client's internal architecture or proprietary workflow configuration.

## Technology used

| Layer | Technology |
| --- | --- |
| Public landing page and intake | WordPress, custom HTML, WPForms, Bluehost |
| Domain/subdomain configuration | Squarespace |
| Staff-facing application | Next.js, Vercel |
| Application data and authentication | Supabase |
| Workflow orchestration | Self-hosted n8n |
| AI-assisted processing | OpenRouter with Claude |
| Existing business-tool integration | Client-authorized communication, field, document and signing systems |

No Zapier or GoHighLevel implementation is claimed.

## Design principles

- **Start with the operating process:** Map ownership and handoffs before automating.
- **Keep people in control:** AI assists with qualification and drafts; staff review consequential outputs.
- **Work with existing systems:** Connect established tools rather than forcing unnecessary replacements.
- **Design for handoff:** Provide clear staff workflows, training, and operational documentation.
- **Respect confidentiality:** Share an illustrative public demonstration without exposing client records or proprietary materials.

## Outcomes and limitations

**Verified project milestone:** The Phase 1 system was delivered and put into production, with staff training completed.

The engagement established a connected operational foundation for homeowner intake, lead handling, compliance visibility, and estimate preparation. No specific time savings, revenue gains, reimbursement improvements, or estimate-accuracy percentages are claimed here because public, independently verified before-and-after results are not available.

The linked BrightPath demo is an illustrative portfolio environment. It may contain features, sample records, or interface elements beyond the actual Phase 1 client scope.

## My role

**AI & Operations Architect:** workflow discovery, system architecture, application and automation implementation, integration design, human-review safeguards, operational documentation, and handoff.

## Explore

- [Illustrative BrightPath demo](https://brightpath-ops-hub-demo.vercel.app)
- [Portfolio overview](../README.md)

*Client identity and identifying details are intentionally withheld pending public-use authorization.*
