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

| Idea | Description | Option & Reason |
|---|---|---|
| **Burnout & Workload Manager** | A system designed to help students understand, manage, and balance their workload across academic, personal, physical, mental, and social commitments. | **Kept** — Directly addresses student burnout and provides strong opportunities for AI integration, workload analysis, prediction, and personalized recommendations. |
| **AI Commitment Analyzer** | Uses AI to analyze a new commitment and identify its hidden time, effort, and workload impact before the user accepts it. | **Kept** — Supports the main problem by helping users understand the actual impact of new commitments before making decisions. |
| **What-If Workload Simulation** | Allows users to see how adding a new commitment could affect their existing workload and whether the overall workload remains manageable. | **Kept** — Adds a predictive element to the system and helps users make informed decisions before accepting new commitments. |
| **Recovery Recommendation System** | Provides recommendations when the user's workload becomes too high, helping them identify suitable ways to recover and manage their commitments. | **Kept** — Complements workload analysis by providing actionable support when the user's workload reaches an unhealthy level. |
| **Mood Check-In** | Allows users to record their current mood so the system can consider their emotional state alongside their workload. | **Kept** — Adds emotional context and allows the system to provide more personalized workload and recovery recommendations. |
| **Travel Planner** | A planning system that helps users organize trips, including schedules, activities, and travel arrangements. | **Dropped** — Although useful and practical, it was less relevant to the team's focus and offered less opportunity to address the issue of student burnout and workload management. |
| **Simple To-Do List** | A basic task-management system for recording and organizing tasks and deadlines. | **Dropped** — Too similar to existing task-management applications and does not address the underlying problem of workload overload or burnout. |
| **Study Planner** | A planner focused mainly on organizing study sessions, academic tasks, and examination preparation. | **Dropped** — Focuses mainly on academic responsibilities and does not account for other sources of workload such as social, physical, mental, and personal commitments. |
| **Flexible Workload Categories** | Allows users to create their own workload categories based on their personal needs. | **Dropped** — Although it increases customization, unrestricted categories may cause inconsistent classification, increase system complexity, and reduce the reliability of workload analysis and AI recommendations. |
| **AI Academic Note Summarizer & Quiz Generator** | Uses AI to summarize academic notes and generate quizzes to support students in their studies. | **Dropped** — Useful for academic support, but it solves a study-assistance problem rather than the central workload and burnout problem. |
| **Habit Tracker** | Helps users track and maintain personal habits and routines over time. | **Dropped** — Useful for personal development, but it does not directly address workload management or the competing commitments that contribute to burnout. |
| **Calendar-Based Planner** | Uses a calendar interface to organize tasks, deadlines, and commitments. | **Dropped as a standalone idea** — A calendar is useful for the final system, but by itself it only organizes commitments and does not analyze workload, hidden effort, or burnout risk. |


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
