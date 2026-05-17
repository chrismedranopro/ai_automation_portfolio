# TravelBuddy — Voice AI Travel Companion

🌐 Live Demo: [gotravelbuddy.app](https://gotravelbuddy.app)

---

# Overview

TravelBuddy is an AI-powered Voice Travel Companion built to help travelers plan trips, discover destinations, book accommodations, explore activities, navigate unfamiliar places, and receive personalized travel guidance through natural conversations.

The platform was designed specifically for modern travelers who prefer conversational and AI-assisted travel planning instead of traditional search-heavy booking experiences.

Unlike standard travel chatbots, TravelBuddy combines:

* AI personalization
* real-time travel intelligence
* workflow automation
* CRM systems
* memory-aware AI experiences
* navigation intelligence
* voice-first interaction concepts
* multi-engine orchestration

into a unified travel platform.

---

# The Challenge

The goal was to create a scalable AI travel system capable of:

* understanding natural travel conversations
* extracting user intent and preferences
* recommending destinations based on weather, budget, comfort, and travel style
* finding personalized accommodations
* surfacing nearby activities and experiences
* remembering previous trips and user travel behavior
* helping users navigate destinations in real-time
* discovering hidden gems and local places
* handling travel workflows through modular AI engines
* integrating CRM and automation systems
* supporting future booking integrations

The platform also needed to:

* support Filipino travelers
* feel conversational and human-like
* reduce friction in travel planning
* operate through scalable automation infrastructure

---

# Core Features

## AI Travel Intelligence

TravelBuddy uses multiple specialized AI intelligence workflows:

* Weather Intelligence
* Accommodation Intelligence
* Flight Intelligence
* Activities Intelligence
* Nearby Search Intelligence
* Navigation Intelligence
* Map Intelligence
* Personalization & Ranking Engine
* Past trips and experiences memory
* Booking Awareness Engine

Each intelligence module is designed as an independent workflow that communicates with the main orchestrator.

---

## Personalized Recommendations

The AI analyzes:

* travel style
* weather preference
* accommodation preference
* budget tier
* food preference
* travel companions
* destination context
* comfort scoring
* activity matching
* previous travel history
* historical user preferences

to generate highly personalized travel recommendations.

---

## Memory-Aware AI Experience

Implemented semantic memory systems using:

* OpenAI embeddings
* Supabase Vector Store
* semantic retrieval workflows

The platform can remember:

* previous trips
* favorite destinations
* past accommodations
* travel habits
* recurring preferences
* food preferences
* past conversations
* user experiences

This enables TravelBuddy to provide more context-aware and personalized recommendations over time.

Example:
“You liked quiet mountain stays in Sagada before, so you may also enjoy this cabin stay in Bukidnon.”

---

## Active Booking Awareness

Developed booking-awareness workflows capable of:

* tracking active bookings
* retrieving ongoing travel reservations
* checking user trip context
* surfacing upcoming travel schedules
* referencing previous bookings during conversations

Integrated using:

* Supabase
* semantic search pipelines
* AI retrieval systems

This enables more intelligent travel continuity across sessions.

---

## Voice AI Companion Concept

The platform was designed around a conversational travel experience where users can:

* speak naturally
* ask travel questions
* request recommendations
* discover destinations
* navigate nearby places
* retrieve trip information
* plan trips conversationally

Example:
“Find me a quiet cabin stay in Tagaytay with mountain views and good WiFi.”

---

## Navigation Intelligence

Built navigation-aware workflows capable of:

* real-time directions support
* nearby place discovery
* route assistance
* destination guidance
* local navigation recommendations

Integrated with:

* Mapbox APIs
* Google Maps systems
* geolocation services

This allows TravelBuddy to function not only as a planner but also as an active travel companion during trips.

---

## Map Intelligence & Hidden Gems Discovery

Created map intelligence systems capable of:

* discovering hidden gems
* surfacing underrated destinations
* finding local spots
* nearby recommendations
* contextual place exploration

The AI combines:

* geolocation data
* nearby search systems
* personalized preference matching
* travel context awareness

to provide highly contextual destination discovery.

---

## Accommodation Intelligence

Built a dedicated accommodation recommendation engine capable of:

* accommodation recommendations
* availability checks
* stay comparisons
* personalized reranking
* estimated pricing analysis
* best-fit stay matching

Integrated with:

* SerpAPI Google Hotels
* Booking-related APIs
* AI reranking systems

---

## Flight Intelligence

Developed a modular flight intelligence workflow supporting:

* flight recommendations
* availability checks
* route analysis
* personalized reranking
* travel preference scoring

Integrated using:

* SerpAPI Google Flights
* AI scoring systems
* airport normalization workflows

---

## Activities & Tours Intelligence

Created a dedicated activities discovery system capable of:

* nearby activity discovery
* activity recommendations
* experience personalization
* attraction reranking
* destination-based exploration

Integrated with:

* Google Maps Search
* SerpAPI
* location geocoding systems
* AI preference ranking

---

# AI Workflow Architecture

The backend architecture was built using modular AI workflow orchestration.

## Workflow Stack

* n8n (Self-hosted)
* OpenAI APIs
* AI extractor pipelines
* personalization engines
* structured output parsers
* semantic retrieval systems
* vector memory pipelines

The system uses:

* parent orchestrators
* specialized intelligence tools
* normalization layers
* AI rerankers
* vector search memory
* semantic recall systems

to create scalable travel workflows.

---

# CRM & Automation Infrastructure

Implemented GoHighLevel (GHL) as the centralized CRM and automation platform powering customer operations and marketing workflows.

## CRM Features

* lead management
* automated follow-ups
* customer segmentation
* workflow automations
* marketing automation
* pipeline management
* inquiry routing
* customer lifecycle workflows

## Automation Integrations

Integrated GHL with:

* n8n workflows
* AI intelligence systems
* booking pipelines
* email workflows
* webhook automations

---

# Database & AI Memory Infrastructure

## Supabase

Used Supabase for:

* booking awareness systems
* vector embeddings storage
* semantic search
* AI memory persistence
* user travel history
* contextual retrieval systems

## Embeddings & Semantic Search

Implemented:

* OpenAI embeddings
* vector similarity search
* semantic memory retrieval
* contextual recommendation recall

to create memory-aware AI travel experiences.

---

# APIs & Integrations

## Integrated Services

* OpenAI API
* ElevenLabs API
* SerpAPI
* Google Hotels
* Google Flights
* Google Maps
* Booking-related APIs
* Mapbox Geocoding
* Supabase
* Resend
* GoHighLevel
* n8n Webhooks
---
# Workflow Screenshots

## Main Orchestrator Chat Workflow

<img width="1262" height="519" alt="Main Orchestrator" src="https://github.com/user-attachments/assets/ca860efd-8747-47b0-91b0-80f4f61bcde9" />

<img width="1318" height="561" alt="image" src="https://github.com/user-attachments/assets/de7d08fd-8572-4b12-9260-2f3904f9b4ae" />

---

## Intelligences as AI Agent tools Workflows
### Accommodation Intelligence

<img width="1280" height="500" alt="image" src="https://github.com/user-attachments/assets/e0531e58-6887-41cc-809b-a4babf250825" />
---

### Flight Intelligence

<img width="1292" height="514" alt="image" src="https://github.com/user-attachments/assets/2e7f5a76-31b0-43e0-91cc-6f4bf9314e27" />
---

### Activities Intelligence

<img width="1329" height="543" alt="image" src="https://github.com/user-attachments/assets/b8fb085e-2eee-468c-93cc-30b690547358" />
---
### Weather Intelligence

<img width="1330" height="487" alt="image" src="https://github.com/user-attachments/assets/cff64f42-e5e5-4154-a31e-c9643a257976" />
---
### Map Intelligence

<img width="1304" height="503" alt="image" src="https://github.com/user-attachments/assets/667d3d46-19d0-464c-9f7f-b9f094640389" />
---
### Navigation Intelligence

<img width="1329" height="518" alt="image" src="https://github.com/user-attachments/assets/2d82e83d-47f6-4268-b651-0f8f0f3318b8" />
---

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

# Author
CHRISTINA MEDRANO
Voice-AI Specialist & AI Automation Specialist
