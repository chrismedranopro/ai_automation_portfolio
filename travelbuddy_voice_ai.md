# TravelBuddy — AI-Powered Travel Companion

🌐 **Live Application:** https://gotravelbuddy.app

---

## Overview

TravelBuddy is an AI-powered travel companion designed to help Filipino travelers plan more personalized and stress-free trips through conversational and AI-assisted experiences.

Instead of switching between flight websites, accommodation platforms, weather apps, maps, blogs, and booking tools, travelers can simply describe what they want and receive personalized recommendations through a natural conversation.

TravelBuddy combines AI, workflow automation, memory systems, travel intelligence, and CRM infrastructure into a unified travel planning experience.

---

# Why I Built TravelBuddy

TravelBuddy was born from a simple frustration:

> Planning a trip always felt more exhausting than the trip itself.

Every time I wanted to travel, I found myself repeating the same process over and over again—comparing accommodations, checking flights, researching destinations, monitoring weather conditions, looking for activities, and trying to balance everything against my budget.

Even after spending hours researching, I often wondered whether I had actually found the best option for me.

The information was available, but it was scattered across too many websites, apps, booking platforms, maps, and travel resources. Every trip felt like starting from scratch.

I didn't want another booking website.

I wanted a travel companion.

Something that could understand my preferences, remember what I liked, help me discover destinations, and guide me toward better travel decisions without spending hours jumping between different platforms.

TravelBuddy is my attempt to solve that problem.

The long-term vision is simple:

> To make travel planning feel less like research and more like having a knowledgeable travel companion by your side.

---

# The Problem

Modern travel planning is fragmented.

Travelers often switch between multiple platforms to complete a single trip:

- Flight search websites
- Hotel booking platforms
- Maps and navigation apps
- Weather services
- Travel blogs
- Activity and tour websites
- Social media recommendations

This process creates unnecessary friction and often leads to decision fatigue.

Most travel platforms help users make bookings but rarely understand who the traveler is, what they prefer, or how their preferences evolve over time.

As a result:

- Travel planning becomes time-consuming
- Recommendations remain generic
- User preferences are forgotten
- Travelers repeatedly perform the same research

---

# The Solution

TravelBuddy was designed as a conversational travel companion that helps travelers:

- Discover destinations
- Find accommodations
- Explore activities and attractions
- Compare travel options
- Navigate unfamiliar places
- Receive personalized recommendations
- Maintain travel context across conversations

Rather than functioning as a traditional search engine, TravelBuddy acts as an intelligent travel assistant capable of understanding user preferences and providing contextual guidance.

---

# Product Screenshots

## Landing Page

<img width="796" height="2444" alt="preview--gotravelbuddy lovable app_" src="https://github.com/user-attachments/assets/50f0fb05-4d06-48e2-a116-650ea7415e9c" />

## Conversational Travel Experience

_Add screenshot_

## My Trips Dashboard

<img width="811" height="913" alt="preview--gotravelbuddy lovable app_trips" src="https://github.com/user-attachments/assets/5213b4b5-09c8-465f-9e9a-b45e253bbd9f" />

## User Profile & Personalization

_Add screenshot_

---

# Core Capabilities

## Personalized Travel Recommendations

TravelBuddy analyzes:

- Budget
- Travel style
- Accommodation preferences
- Weather preferences
- Food interests
- Travel companions
- Previous travel behavior

to generate highly personalized travel recommendations.

---

## Memory-Aware AI Experience

Implemented semantic memory systems capable of remembering:

- Previous trips
- Favorite destinations
- Accommodation preferences
- Travel habits
- Food preferences
- Past conversations

This enables more context-aware and personalized recommendations over time.

Example:

> "You previously enjoyed quiet mountain stays in Sagada, so you may also enjoy this cabin stay in Bukidnon."

---

## Travel Intelligence System

TravelBuddy utilizes multiple specialized intelligence engines including:

- Accommodation Intelligence
- Flight Intelligence
- Activities Intelligence
- Weather Intelligence
- Navigation Intelligence
- Map Intelligence
- Destination Discovery

Each module is designed as an independent workflow connected through a central AI orchestrator.

---

## Active Booking Awareness

TravelBuddy maintains awareness of:

- Active bookings
- Upcoming trips
- Reservation details
- Travel schedules

allowing conversations to remain contextually relevant across sessions.

---

# My Role

As the founder and sole builder of TravelBuddy, I was responsible for:

- Product Strategy
- User Experience Design
- AI Workflow Architecture
- Backend Automation Development
- CRM Integration
- Database Design
- API Integrations
- Workflow Orchestration
- Infrastructure Management
- Testing & Iteration

---

# Technical Architecture

TravelBuddy uses a modular AI orchestration architecture where specialized intelligence systems handle specific travel tasks.

## Core Stack

### Frontend

- React
- TypeScript
- Tailwind CSS
- Vercel

### AI & Automation

- OpenAI
- n8n
- Structured Output Pipelines
- AI Workflow Orchestration
- Semantic Retrieval Systems

### Database & Memory

- Supabase
- PostgreSQL
- OpenAI Embeddings
- Vector Search

### CRM & Communication

- GoHighLevel (GHL)
- Resend

### External Services

- SerpAPI
- Google Hotels
- Google Flights
- Google Maps
- Mapbox APIs
- Weather APIs

---

# Workflow Architecture

## Main Orchestrator

<img width="1262" height="519" alt="Main Orchestrator" src="https://github.com/user-attachments/assets/ca860efd-8747-47b0-91b0-80f4f61bcde9" />

<img width="1318" height="561" alt="image" src="https://github.com/user-attachments/assets/de7d08fd-8572-4b12-9260-2f3904f9b4ae" />

The orchestrator routes requests to specialized travel intelligence engines based on user intent and context.

---

## Travel Intelligence Workflows

### Accommodation Intelligence

<img width="1280" height="500" alt="image" src="https://github.com/user-attachments/assets/e0531e58-6887-41cc-809b-a4babf250825" />

**Purpose:** Generate personalized accommodation recommendations based on destination, budget, and traveler preferences.

📄 Detailed Workflow Documentation:
`docs/workflows/accommodation-intelligence.md`

---

### Flight Intelligence

<img width="1292" height="514" alt="image" src="https://github.com/user-attachments/assets/2e7f5a76-31b0-43e0-91cc-6f4bf9314e27" />

**Purpose:** Provide personalized flight recommendations and route analysis.

📄 Detailed Workflow Documentation:
`docs/workflows/flight-intelligence.md`

---

### Activities Intelligence

<img width="1329" height="543" alt="image" src="https://github.com/user-attachments/assets/b8fb085e-2eee-468c-93cc-30b690547358" />

**Purpose:** Discover activities, attractions, and experiences based on traveler preferences.

📄 Detailed Workflow Documentation:
`docs/workflows/activities-intelligence.md`

---

### Weather Intelligence

<img width="1330" height="487" alt="image" src="https://github.com/user-attachments/assets/cff64f42-e5e5-4154-a31e-c9643a257976" />

**Purpose:** Incorporate weather context into travel recommendations and trip planning.

📄 Detailed Workflow Documentation:
`docs/workflows/weather-intelligence.md`

---

### Navigation Intelligence

<img width="1329" height="518" alt="image" src="https://github.com/user-attachments/assets/2d82e83d-47f6-4268-b651-0f8f0f3318b8" />

**Purpose:** Assist users with route guidance, nearby discovery, and destination navigation.

📄 Detailed Workflow Documentation:
`docs/workflows/navigation-intelligence.md`

## Frontend Workflows
### Signup Workflow

<img width="1322" height="441" alt="image" src="https://github.com/user-attachments/assets/b55feb58-d59b-4518-a957-cb3074e98dd0" />

---

### Onboarding Workflow

<img width="1320" height="449" alt="image" src="https://github.com/user-attachments/assets/f9e3a85c-b230-49c9-b4db-d6cd20a1ee7f" />

---

## Error Handling Workflow

<img width="1327" height="519" alt="image" src="https://github.com/user-attachments/assets/d6c1f416-0d07-47a0-add4-3f296feedbac" />

---

# Challenges & Lessons Learned

### Context Management

One of the biggest challenges was maintaining context across multiple systems, including user preferences, travel history, booking information, and recommendation engines.

### Balancing Flexibility & Structure

Travel conversations can quickly move between destinations, accommodations, weather, budgets, and activities. Designing workflows that remained flexible while producing reliable outputs was a key architectural challenge.

### Designing for Scale

The platform was built with future expansion in mind, allowing new intelligence engines and booking integrations to be added without major architectural changes.

---

# What This Project Demonstrates

This project showcases my ability to:

- Design AI-powered products
- Build workflow automation systems
- Architect multi-agent workflows
- Implement conversational AI
- Create CRM and automation ecosystems
- Build memory-aware AI experiences
- Integrate multiple APIs and services
- Develop scalable SaaS products

---

# Project Links

🌐 Live Application  
https://gotravelbuddy.app

📚 Full Case Study  
`/docs/case-study.md`

⚙️ Workflow Documentation  
`/docs/workflows/`

---

## Project Classification

**Type:** AI-Powered SaaS Product

**Industry:** Travel & Hospitality

**Focus Areas:**
Conversational AI · Workflow Automation · CRM Systems · AI Orchestration · Personalization Engines · Travel Technology · Product Design
---

# Author
CHRISTINA MEDRANO
Voice AI Specialist • AI Automation Specialist
