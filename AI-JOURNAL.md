# Ultra_AI — AI Journal

> This file is the continuity log for AI assistants (Claude Code, Claude.ai) working on Dylan's Ultra_AI project.
> Each entry documents what happened, what changed, and what the next AI session should know.
> The dashboard also has an "AI Journal" tab where entries are stored in the app state and synced via GitHub Gist.

---

## How This Works

1. **Dashboard AI Journal tab** — Interactive entries stored in app state (synced to Gist)
2. **This MD file** — Long-form context for Claude Code sessions (stored in the GitHub repo)
3. **Both should be kept in sync** — When Claude Code makes changes, it should update both

---

## Project Overview

**Owner:** Dylan, CEO of FortX Web (Quebec-based web dev agency)
**Goal:** Build a fully autonomous AI-powered web agency
**Method:** Ultralearning framework (build-heavy with dedicated learning steps)
**Stack:** Payload CMS + Claude Code (sites), n8n (automation)
**Dashboard:** GitHub Pages site with GitHub Gist cloud sync for state

### The 68-Step Plan (v3 — March 2026)

- **Phase 0 (Steps 1-9):** Metalearning — Git, skill tree, Payload test, prompt engineering foundations, CMS deep dive, Tailwind patterns
- **Phase 1 (Steps 10-16):** Website Building — fake sites with prompt library, refinement sprint, speed run, SOP, agent mental model
- **Phase 1.5 (Steps 17-25):** Automation — n8n fundamentals, real client sites, client-facing automation, Phase 1 checkpoint
- **Phase 2 (Steps 26-39):** Lead Gen — lead sourcing, outreach system prompt design, cold email infrastructure, pipeline, scaling
- **Phase 3 (Steps 40-47):** Voice & AI — conversation design, voice platforms, voice agent builds, Phase 2 checkpoint
- **Phase 4 (Steps 48-68):** Autonomous Ops — blueprint, receptionist, chatbot, multi-agent architecture, 4-hour agency drill, upsell

### Key Principles

- **Tool-agnostic:** Steps describe skills, not specific tools. Dylan picks tools during execution.
- **Progressive stacking:** Each step's output feeds the next
- **Drills (🔁):** Rebuild without notes to prove mastery
- **"Done =":** Every step has a concrete completion definition
- **No filler:** Every step involves AI tools, prompting, or automation

### Tech Stack

- **AI Website Builder:** Payload CMS + Claude Code
- **Automation Platform:** n8n
- **Lead Sourcing:** TBD (testing in Step 28)
- **Cold Email:** TBD (testing in Step 32)
- **AI Voice:** TBD (testing in Step 41)
- **Dashboard:** GitHub Pages + GitHub Gist sync

---

## Entry Log

### 2025-02-27 — Project Setup (AI: Claude.ai)

**What happened:**
- Rewrote the entire 60-step plan based on Ultralearning book principles
- Old plan had tool-locked steps, passive learning, poor progression, no retrieval practice
- New plan: 80% build / 20% learn, drills every 4-5 steps, tool-agnostic, "Done =" on every step
- Added Step X (mini project: AI news digest) to Phase 0
- Built complete dashboard v2 with: Skill Tree tab, AI Journal tab, GitHub Gist cloud sync, step notes, auto-timestamps, search/filter, keyboard shortcuts, celebrations, pipeline tooltips

**What changed from original:**
- 60 steps completely rewritten (was tool-locked, now skill-focused)
- Phase 0 expanded from 3 to 6 steps (proper metalearning)
- Phase 2 reorganized: email first, voice second (was mixed)
- "Train VA on SOPs" removed (not an AI skill)
- 11 learning steps (📚) added explicitly (~18%)
- 4 drills added (speed runs, memory rebuilds, 4-hour agency)
- Skill Tree stored in dashboard (not Notion) per Dylan's request

**What the next AI should know:**
- Dylan is a COMPLETE beginner with GitHub — he's learning it in Step 1
- The dashboard is a single HTML file (no build tools, no dependencies)
- All state is in localStorage + GitHub Gist (JSON)
- The Gist stores: step statuses, pipeline states, notes, timestamps, skill tree, AI journal entries
- Dylan's Notion links are hardcoded in the dashboard — update if they change
- Dylan tends to be obsessive and systematic — lean into that, give him structure
- He's based in Chibougamau, Quebec — timezone considerations for automation schedules

**Pending decisions:**
- Which AI website builder (Step 3)
- Which automation platform (Step 4)
- All other tool choices — don't assume any specific tools

---

### 2026-03-11 — Dashboard v3: Learning Steps + Phase Restructure (AI: Claude Code / Opus 4.6)

**What happened:**
- Added 7 new learning steps to address the build-heavy/learn-light imbalance
- Restructured from 4 phases to 6 phases (0, 1, 1.5, 2, 3, 4)
- Modified 3 existing steps to reflect Payload CMS + Claude Code commitment
- Updated skill tree with 8 new concepts and 5 new procedures
- Total steps: 60 → 68

**New learning steps added:**
1. **Prompt Engineering Foundations** (Phase 0, before any site builds) — Anthropic's guide, 3 reusable system prompts
2. **Payload CMS Deep Dive** (Phase 0) — collections, fields, hooks, access control
3. **Tailwind CSS + Component Patterns** (Phase 0) — 5 section prompt templates
4. **AI Agent Mental Model** (Phase 1, bridge to automation) — agent loop, tool use, context windows
5. **System Prompt Design for Outreach** (Phase 2) — master cold email system prompt
6. **Conversation Design for Voice Agents** (Phase 3) — intents, utterances, flow diagrams
7. **Multi-Agent Architecture** (Phase 4) — orchestration patterns, sequential/parallel/supervisor

**Steps modified:**
- Step 03: "Test 3 AI website builders" → "Build first test site with Payload CMS + Claude Code"
- Step 12 (was 08): "Prompt engineering deep dive" → "Prompt Refinement Sprint — audit 5 weakest prompts"
- Step 13 (was 09): "Speed run, no notes" → "Speed Run — new Payload site, <90 min, using prompt library"

**Phase restructure:**
- Phase 0: Metalearning (steps 1-9) — was 1-5+X
- Phase 1: Website Building (steps 10-16) — was 6-20
- Phase 1.5: Automation (steps 17-25) — NEW, split from old Phase 1
- Phase 2: Lead Gen (steps 26-39) — was 21-40
- Phase 3: Voice & AI (steps 40-47) — NEW, split from old Phase 2
- Phase 4: Autonomous Ops (steps 48-68) — was 41-60

**Technical changes:**
- Data migration from `ultra_v3` to `ultra_v4` localStorage key
- Migration map translates old step numbers to new ones automatically
- Phase grid CSS updated from 4-column to 3-column (2 rows of 3)
- Seed function injects new skill tree items and journal entry on first load
- Brief AI text updated to reference 68 steps and Payload CMS stack

**What the next AI should know:**
- Dylan chose **Payload CMS + Claude Code** as his stack (not SaaS website builders)
- The dashboard now has 68 steps across 6 phases
- localStorage key is now `ultra_v4` (with auto-migration from v3)
- Dylan's coding workflow depends entirely on prompt quality — learning steps reflect this
- New learning steps are 2-4 hours each, not full days — they don't extend the timeline

**Tech stack confirmed:**
- **Website Builder:** Payload CMS + Claude Code (not SaaS builders)
- **Automation Platform:** n8n
- **Dashboard:** GitHub Pages + GitHub Gist sync

---

*Add new entries below this line. Format: date, author, what happened, what changed, what next AI should know.*
