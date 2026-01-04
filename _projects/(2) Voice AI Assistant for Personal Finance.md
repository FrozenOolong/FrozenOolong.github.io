---
name: Voice AI Agent for Personal Finance
category: GenAI
weight: 2
tools: [Python, GenAI, Lovable, Vibe Coding, ElevenLabs, Supabase, React, TypeScript]
image: /images/voice_ai_cover.png
description: Built a conversational voice AI personal finance assistant using ElevenLabs Voice AI, Lovable (rapid prototyping), and Supabase. Features voice expense tracking, budget creation, and smart financial habit reminders.

---

# Voice AI Agent for Personal Finance

Hackathon Project | Built in a weekend using [Lovable (Vibe Coding)](https://lovable.dev/), [ElevenLabs Voice AI](https://elevenlabs.io/) and Supabase

This project explores how conversational voice AI can enhance personal finance management. It was developed for a hackathon challenge to prototype a GenAI-driven personal finance assistant leveraging Lovable (for rapid web app generation) and ElevenLabs (for natural voice interaction).

---

### Product Overview

**Goal:** Build a friendly, voice-powered personal finance web app that helps users:

* Create and manage budgets
* Track spending through natural voice input
* Receive personalized financial insights and reminders

**Example Voice Interaction:**

> “I bought a T-shirt yesterday for $21”
> → Automatically logs an expense under *Clothing*, dated *2025-01-01*, amount *$21*.

---

### Target Users

* **Age:** 18–35 (Millennials & Gen Z)
* **Profile:** Tech-savvy individuals who feel anxious or uncertain about their personal finances and want an easier way to track and improve spending habits.

---

### Pain Points Addressed

1. **Lack of personalized guidance** — Finance feels “personal,” but users want trusted, AI-based feedback.
2. **Manual data entry fatigue** — Tracking expenses is tedious; users prefer natural, voice-based input.
3. **Financial anxiety** — Users want structure, reminders, and a sense of control over spending.

---

### Key Features

* **Conversational Budgeting:** An AI advisor that guides users step-by-step to create budgets and identify improvement areas.
* **Voice Expense Tracking:** Log transactions through natural conversation using ElevenLabs speech recognition.
* **Smart Financial Habits Calendar:** Calendar reminders for credit card payments, planned shopping, and recurring expenses—reducing impulsive spending.

---

### UI & Design Language

* **Visual Theme:** Light green, yellow, and white for a positive, calming financial experience.
* **Branding:** Frog avatar to convey friendliness and approachability.
* **Design Focus:** Simple layouts, accessible color palette, and intuitive data visualization.

---

### Technical Architecture

**Frontend:**

* Built with **React + TypeScript**
* Responsive, modern, and clean UI focused on simplicity

**Backend:**

* **Supabase** for authentication and data storage
* Data schema includes:

  * `users` (profile & preferences)
  * `budgets` (overall plans)
  * `budget_items` (categories and targets)
  * `expenses` (individual records)
  * `reminders` (financial calendar events)
  * Others: `user_budget`, `budget_category` for table linking

**Voice AI Agent:**

* Powered by **ElevenLabs Voice AI** with a **custom system prompt**
* Character role: *Personal Financial Advisor*
* Responsibilities:

  * Create and update budgets
  * Record expenses
  * Suggest budgeting improvements
  * Manage reminders and habit tracking

---

### 🚀 Learnings from Vibe Coding with Lovable

1. **Design-first approach:**
   Shifted from spending 80% of time coding → 80% clarifying product value, user flow, and feature communication.
2. **Architecture & organization:**
   Plan data schema and folder structure upfront for easier maintenance and debugging.
3. **Collaborative debugging:**
   Lovable’s integration with GitHub and automatic deployment feedback loop is powerful, but manual intervention is often needed to resolve complex bugs.
4. **UI evolution challenges:**
   Small visual tweaks (fonts, colors) can ripple unexpectedly—precise prompting and version control are essential.
5. **Data clarity matters:**
   Providing explicit schema examples helps Lovable’s AI understand and generate more reliable database code.

---

### Demo

**🔗 Live Project:** [View on Lovable](https://lovable.dev/projects/105315c6-daf4-4b8d-a04c-fe4b2beab3bb) --> require user sign up

#### Dashboard Page for Month-to-Date Spending
![Dashboard Page for Month-to-Date Spending](/images/voice_ai_demo_1_dashboard.png)

#### Voice AI Agent - to start the call with AI Agent
![agent](/images/voice_ai_demo_2_voice_ai.png)

#### Budget Review
![image](/images/voice_ai_demo_3_budget.png)

#### Create Budget
![Create Budget](/images/voice_ai_demo_4_create_budget.png)

#### Personal Profile
![Profile](/images/voice_ai_demo_5_profile.png)
