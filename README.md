# [Zenoxium] by [Puroxiom]

**Team:** 
- Muhammad Firdaus 
- Siti Nur Syazwani Khong

- **Problem Statement:** Stress & Workload Manager
- **Video Presentation:** [Unlisted YouTube Link]
- **Presentation Slides:** [Public Link]

---

## 1. Project Overview

### The Problem

University students don't usually become overwhelmed by a single large responsibility; it's the accumulation of many smaller commitments (classes, assignments, club activities, errands) that gradually builds up. Individually, each commitment seems manageable, but when combined, students often don't realize how much they're carrying until they're already exhausted.

**Causes:**
- Responsibilities are scattered across different tools — a calendar for classes, a to-do list for assignments, a notes app for personal tasks, group chats for social commitments — leaving no single, clear picture of overall workload.
- New commitments are typically evaluated only against time availability ("Is Saturday free?"), not against actual capacity, so hidden costs like travel, preparation, and recovery time go unaccounted for.
- Existing tools tell students *what* they have to do and *when*, but not *whether they can realistically take on more*.

**Stakeholders:**

| Stakeholder | Role | Unmet Need |
|---|---|---|
| Students (primary) | End users | A clearer picture of their workload before committing to more |
| Academic advisors & wellness centers (secondary) | Support system | No early-warning tools to identify at-risk students before burnout occurs |

**Existing solutions:**

| App | Type | What It Does | Where It Falls Short |
|---|---|---|---|
| Notion | Productivity | All-in-one workspace for notes, tasks, and databases | General-purpose; not built around workload or capacity |
| Todoist | Productivity | Natural-language task input, recurring tasks | Tracks *what* is due, not whether the user can realistically take on more |
| Trello | Productivity | Visual board-based project management | No concept of personal capacity or burnout risk |
| Microsoft To Do | Productivity | Lightweight task manager, Outlook sync | Reminders and sync only; no workload awareness |
| Calm / Headspace | Wellness | Guided meditation, sleep content | Addresses stress symptoms after the fact, disconnected from actual task load |
| Balance | Wellness | Adaptive meditation coach | Personalizes relaxation content, not workload |
| Sanvello | Wellness | CBT-based exercises, mood tracking | Treats stress as a standalone metric, not something driven by an overloaded schedule |

**The gap:** Productivity tools optimize task execution but ignore burnout; wellness apps address stress but are blind to its cause — the workload itself. None connect *what a student is carrying* across mental, physical, social, and errand commitments to *how they're actually feeling*, or help them act on that link before burnout hits. Many advanced features are also paywalled, and general-purpose tools like Notion or Trello can overwhelm new users with unnecessary complexity.

Zenoxium's differentiation is this direct link: workload across categories → mood-adjusted capacity ceilings → rebalancing suggestions, in one lightweight PWA rather than five disconnected apps.

### Our Solution

Zenoxium is a lightweight Progressive Web App that gives students one clear picture of what they're carrying — instead of scattering it across a calendar, a to-do list, and a wellness app — and actively helps them do something about it before burnout hits.

**Core mechanics:**

| Mechanic | What It Does |
|---|---|
| Workload across four categories | Mental, Physical, Social, and Errands. Every commitment gets tagged (auto-suggested via keyword matching, AI as fallback) so load is visible by area, not one undifferentiated task list |
| Capacity, not just time | Each category has a usable-capacity ceiling that adjusts based on a daily mood check-in (Good, Tired, Too Tired, Overwhelmed), with fatigue accumulating the longer a bad mood streak continues |
| Rebalancing, not just reporting | On breach, an AI-assisted step looks at category load, breach severity, mood state, and task priority to suggest what to defer, drop, or protect |
| Recovery nudges | Soft, non-blocking push notifications pointing toward rest or a specific recovery action when thresholds are breached — never a hard stop |

This directly closes the gap named above: productivity tools track tasks but ignore capacity; wellness apps address stress symptoms but are blind to what's causing them. Zenoxium connects the two in one place a student would actually keep open on their phone.

---

## 2. Ideation & Process

### 2.1 Ideas We Considered

Table of every distinct idea generated, with why each was kept or dropped. Order it so that chosen ideas are listed first.

## 2.1 Ideas We Considered

| Idea | Why it was dropped / kept |
|---|---|
| **Burnout & Workload Manager** — A system that helps students understand and manage their workload by analyzing commitments, hidden time/effort, priorities, and workload impact. | **Kept — Chosen as our final problem statement.** It addresses a relevant student problem, has strong potential for AI integration, and allows us to provide more than simple task management through workload prediction, what-if analysis, and recovery recommendations. |
| **AI Commitment Analyzer** — An AI feature that analyzes a new commitment and estimates its hidden time, effort, and impact on the user's existing workload. | **Kept.** It directly supports the main workload-management problem and provides a meaningful use case for AI. |
| **What-If Workload Simulation** — Allows users to see how adding a new commitment would affect their existing workload before accepting it. | **Kept.** It helps users make informed decisions before taking on additional commitments and makes the workload impact easier to understand. |
| **Recovery Recommendation System** — Provides recommendations when the user's workload reaches a high level. | **Kept.** It extends the solution beyond task management by helping users respond to excessive workload. |
| **Mood Check-In** — Allows users to record their current mood before viewing their workload. | **Kept.** It provides additional context about the user's current state and complements the workload analysis. |
| **Travel Planner** — A planner that helps users organize trips, including schedules, activities, and travel commitments. | **Dropped.** Although useful and feasible, it was less aligned with our chosen direction and offered less opportunity to address the student burnout and workload problem. |
| **Simple To-Do List** — A basic system for recording and checking off tasks. | **Dropped.** It was too similar to existing task-management applications and did not sufficiently address the underlying problem of workload overload. |
| **Study Planner** — A system that creates study schedules based on subjects, deadlines, and available time. | **Dropped.** It focused mainly on academic scheduling and did not account for other types of commitments such as social, physical, mental, and personal responsibilities. |
| **Flexible Workload Categories** — Allows users to create completely custom workload categories. | **Dropped.** Although flexible categories would allow greater customization, they could introduce inconsistent categorization and increase system complexity, making workload analysis and AI recommendations less reliable. |
| **AI Academic Note Summarizer & Quiz Generator** — Uses AI to summarize academic notes and generate quizzes for students. | **Dropped.** Although useful for students, it focused more on study assistance than workload and burnout management, making it less relevant to our chosen problem statement. |
| **Habit Tracker** — A system for tracking daily habits and routines. | **Dropped.** It was useful for personal development but did not directly address the problem of managing multiple competing commitments and workload. |
| **Calendar-Based Planner** — A planner that organizes tasks and commitments using a calendar interface. | **Dropped as a standalone concept.** A calendar is useful for organizing commitments, but by itself it does not analyze workload or identify the hidden time and effort required by commitments. |
### 2.2 Ideation Boards

#### Problem Tree
![Zenoxium Problem Tree](phase_1/assets/zenoxium_problem_tree.webp)

#### User Flow
![Zenoxium User Flow](phase_1/assets/zenoxium_user_flow.webp)


#### SCAMPER Model
<img width="1920" height="1080" alt="SCAMPER ZENOXIUM" src="https://github.com/user-attachments/assets/825711b7-8694-4a06-9a3e-10e94f8e827e" />

#### Mindmap Features
<img width="8192" height="3873" alt="XZENOXIUM App Workload-2026-09-09-135813" src="https://github.com/user-attachments/assets/a4263b7f-6d2b-42d9-8026-cf11f2b6a357" />






### 2.3 Mentor Consultation

<img width="555" height="497" alt="Screenshot 2026-09-09 202544" src="https://github.com/user-attachments/assets/2aace542-fbfa-4158-bab2-01f0df1e901e" />
<img width="555" height="658" alt="Screenshot 2026-09-09 202826" src="https://github.com/user-attachments/assets/8ff78313-46e3-4da3-94b5-e81872af7ba3" />
<img width="555" height="225" alt="Screenshot 2026-09-09 202833" src="https://github.com/user-attachments/assets/20c44b60-136c-45cc-b0e9-ea57d585ace5" />


---

## 3. Design & Prototype

**UI Prototype:** [Public Link]

Check that it opens in an incognito window. This can be a link to Figma, Canva, Netlify, Vercel, or any other board where you showcase your UI. It can be clickable with hyperlinks or simply ordered screenshots.

We recommend you embed or link 4–8 key screens as images, with a caption on each explaining the interaction.

---

## 4. What Makes It Different

List out novel features and explain briefly which each is original or what the twist is.

You can have a comparison table to compare with existing solutions named in section 1, but this is completely optional.

---

## 5. Technical Architecture & Feasibility

### Tech Stack

#### Frontend

| Tool | Why We Chose It | Constraint |
|---|---|---|
| **React + Vite** | Fast dev-server startup and hot reload, which matters given our build window. | — |
| **Tailwind CSS** | Lets us pull design tokens directly from Figma (our source of truth) into `tailwind.config.js`, keeping styling consistent without a separate design system. | Token sync between Figma and Tailwind is currently manual — a design change requires us to re-extract and update the config by hand. No automated pipeline for this yet. |
| **vite-plugin-pwa** | Packages the app as an installable Progressive Web App (service worker, manifest, offline cache) without needing a native app store submission — directly addresses the problem statement's requirement that the app be "something students would actually keep open on their phone." | Offline support only covers cached UI/static assets; any feature that depends on a live Supabase connection (workload data, AI suggestions) still requires network access. |
| **Zustand** | Lightweight state management for client-side app state (mood, commitments, UI state) without Redux's boilerplate. | No built-in devtools/persistence middleware configured yet — state resets on full page reload unless we wire this up. |

#### Backend / Database

| Tool | Why We Chose It | Constraint |
|---|---|---|
| **Supabase (Postgres + Auth + Realtime)** | Gives us a managed Postgres database, authentication, and realtime subscriptions in one free-tier service, avoiding separate infrastructure for each. | Free tier pauses inactive projects and has row/bandwidth limits — not a production guarantee. Also can't run arbitrary server-side logic directly against the DB, which is why we use Edge Functions for anything beyond CRUD. |
| **Supabase Edge Functions** | Used for two things: (1) proxying AI calls so the Gemini API key stays server-side and never reaches the browser, (2) a scheduled `pg_cron` job that checks workload against each user's capacity and triggers push notifications. | Edge Functions run on Deno, not Node — some npm packages aren't directly compatible, so we check compatibility before depending on any library there. |

#### AI / APIs

| Tool | Why We Chose It | Constraint |
|---|---|---|
| **Gemini 2.5 Flash-Lite** (Google AI Studio) | Scoped to three functions where judgment/NLG genuinely adds value: Workload Rebalancing suggestions, personalized advice (from mood + schedule + workload together), and hidden-cost detection (flags time/energy costs in a commitment's notes that the user likely underestimated). Everything else (category tagging, capacity math, breach detection) runs on deterministic logic. Free-tier and fast enough for this use case. | Free-tier requests are rate-limited. Multi-turn coherence across a conversation (e.g. a rebalancing chat) is a known risk — mitigated by progressively summarizing confirmed slots into the system prompt rather than replaying full history. |
| **Web Push (VAPID)** | Used for workload-breach nudges, sent from the `pg_cron` Edge Function independent of whether the app is open. | Requires explicit browser permission and doesn't work identically across all browsers/OSes (notably iOS Safari has partial/late support). |

#### Hosting / Deployment

| Tool | Why We Chose It | Constraint |
|---|---|---|
| **Vercel** | Connected to our GitHub repo (`MaybeDaus/Puroxiom_Zenoxium`) with auto-deploy on push. | Frontend only — Supabase and its Edge Functions are hosted and deployed separately, so a full deploy involves two systems rather than one. |

#### Design

| Tool | Why We Chose It | Constraint |
|---|---|---|
| **Figma** | Source of truth for all screens and design tokens, referenced during frontend implementation. | — |

### System Architecture Diagram

![Zenoxium Tech Stack](phase_1/assets/zenoxium_tech_stack_v3.webp)

### Build Plan & Scope

| Phase | Scope |
|---|---|
| **Phase 1 — Core data & logic** (deterministic, no AI) | Supabase schema (users, commitments, mood check-ins, category tags) · Commitment CRUD wired to Dashboard · Daily workload check (19h/day ceiling) + weekly workload check (133h/week), both mood-adjusted per the streak-decay model · Category auto-tagging via keyword matching (Gemini fallback only on no-match) |
| **Phase 2 — Notifications & AI-backed features** | `pg_cron` Edge Function for breach detection + Web Push delivery · Gemini-backed functions via proxy Edge Function: Workload Rebalancing suggestions, general advice, hidden-cost detection |
| **Phase 3 — Polish** | Monthly calendar view · Insights screen · Simulation screen (client-side only) |

**Explicitly out of scope for this build window:**

- Multi-device sync beyond what Supabase Realtime gives us by default
- Native mobile apps (PWA only)
- Any AI feature beyond Rebalancing suggestions, general advice, and hidden-cost detection
- Automated Figma → Tailwind token sync
