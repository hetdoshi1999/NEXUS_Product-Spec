# MERIDIAN — Executive Product Specification
### AI-Powered Decision Intelligence Platform

> *"The quality of your life is the sum of the quality of your decisions. Meridian exists to raise that sum."*

**Version:** 1.0 — Internal Strategy Document  
**Status:** Pre-Seed / Founding Team Alignment  
**Audience:** Business, Design, Engineering, Investors, PM Leadership

---

# TABLE OF CONTENTS

1. [Executive Summary](#1-executive-summary)
2. [The Core Problem](#2-the-core-problem)
3. [Product Vision](#3-product-vision)
4. [User Personas](#4-user-personas)
5. [Product Experience & UX Flows](#5-product-experience--ux-flows)
6. [System Architecture](#6-system-architecture)
7. [The Decision Engine](#7-the-decision-engine)
8. [Design System Philosophy](#8-design-system-philosophy)
9. [Feature Breakdown](#9-feature-breakdown)
10. [Monetization Strategy](#10-monetization-strategy)
11. [Go-To-Market Strategy](#11-go-to-market-strategy)
12. [Competitive Analysis](#12-competitive-analysis)
13. [Risk Analysis](#13-risk-analysis)
14. [Success Metrics](#14-success-metrics)
15. [Implementation Roadmap](#15-implementation-roadmap)
16. [Final Product Thesis](#16-final-product-thesis)

---

# 1. EXECUTIVE SUMMARY

## What Is Meridian?

Meridian is an AI-powered **decision intelligence platform** — a structured reasoning engine that models who you are, understands the decision in front of you, surfaces trade-offs you didn't know existed, and explains its recommendations with the transparency of a trusted expert friend.

It is not a search engine. Not a chatbot. Not a comparison table. It is the first product built specifically around the act of **deciding** — an experience most people navigate with anxiety, incomplete information, and cognitive bias, every single day.

## The Market Gap

The current landscape offers two inadequate extremes:

- **Information tools** (Google, Reddit, comparison sites) — give you more data without helping you reason through it
- **Human advisors** (therapists, financial planners, coaches) — expensive, inaccessible, and unavailable in the moment you need them

No product sits in the middle: a system that **knows you**, **understands your specific decision**, and **reasons with you** — not at you.

## Why Now

Three forces converge to make this possible today and only today:

1. **LLM reasoning quality** has crossed the threshold where nuanced, multi-factor inference is reliable enough to trust
2. **Long-context memory** enables the kind of user modeling that makes personalization meaningful, not superficial
3. **Behavioral economics research** has matured enough to encode the actual failure modes of human decision-making into a software product

## Core Innovation

Meridian's core innovation is not AI. It's **structured reasoning applied to personal decisions at scale** — a system that treats every incoming decision as a classification problem, a value extraction problem, a weighting problem, and a scenario modeling problem, all simultaneously, for a specific human with a specific history and a specific life context.

## Vision Statement

> **To become the trusted thinking partner that helps every person navigate the decisions that shape their life — with clarity, confidence, and genuine understanding of who they are.**

## Strategic Moat

| Moat Layer | Description |
|---|---|
| **User Memory** | Each interaction enriches a Decision Profile that compounds in value over time — switching cost grows with use |
| **Domain Depth** | Specialized reasoning frameworks per decision type (financial, career, housing, health) — not a generic chatbot |
| **Outcome Feedback Loop** | Post-decision follow-ups create a closed training loop competitors cannot replicate without user history |
| **Trust Architecture** | Transparent reasoning builds a trust relationship that generic AI assistants structurally cannot achieve |

## Long-Term Platform Potential

Meridian begins as a consumer decision tool and evolves into:
- A **family decision OS** — shared reasoning for couples, households, co-founders
- A **professional reasoning layer** — embedded in financial advisory, HR platforms, healthcare portals
- A **decision data network** — anonymized, opt-in outcome data that improves recommendations for all users
- An **API-first intelligence layer** — powering decision support in third-party applications

---

# 2. THE CORE PROBLEM

## Why Modern Decision-Making Is Broken

Every day, the average person makes hundreds of decisions. Most are trivial. But the ones that matter — career moves, financial commitments, where to live, how to invest, whether to leave — are made with the same cognitive tools as the trivial ones: gut feel, partial information, social pressure, and hope.

This is not a character flaw. It is a **system design failure**. Humans were not built for the complexity, information density, and option volume of modern life.

## The Eight Failure Modes

┌─────────────────────────────────────────────────────────────────┐
│                  WHY DECISIONS FAIL                             │
├──────────────────────────┬──────────────────────────────────────┤
│ FAILURE MODE             │ WHAT ACTUALLY HAPPENS                │
├──────────────────────────┼──────────────────────────────────────┤
│ Information Asymmetry    │ You don't know what you don't know   │
│ Value Ambiguity          │ You don't know what you actually want│
│ Cognitive Overload       │ Too many attributes → tab closed     │
│ Temporal Confusion       │ Optimize now, regret later           │
│ Social Interference      │ Others' preferences override yours   │
│ False Framing            │ A & B presented; C is the real answer│
│ Emotional Static         │ Fear and loss aversion distort signal│
│ Consequence Blindness    │ Can't see second-order effects       │
└──────────────────────────┴──────────────────────────────────────┘

## Why Existing Tools Fail

**Search engines** surface information but provide no reasoning layer. You still have to do all the synthesis work — which is exactly where humans fail.

**Comparison sites** (NerdWallet, Wirecutter, Consumer Reports) are category-specific, can carry commercial bias, and still require you to map their analysis onto your specific situation and values.

**Generic AI assistants** (ChatGPT, Gemini) can converse about decisions but have no model of *you*, no memory of *your history*, and no structured methodology for *this type of decision*.

**Human advisors** — the gold standard — are expensive ($150–$500/hr), hard to access in the moment, and limited in scope to their specialty. Your financial advisor cannot help you decide whether to move cities. Your therapist cannot run a mortgage TCO analysis.

## Why AI Changes This Category Now

The missing ingredient was always **structured personalization at scale**. You need a system that:

1. Remembers who you are across every interaction
2. Applies domain-specific reasoning frameworks, not generic chat
3. Can hold multi-factor trade-off models in working memory
4. Surfaces what's missing, not just what's present
5. Explains its reasoning well enough to be trusted and challenged

All five are now achievable. The category has been waiting for the infrastructure to catch up to the need.

---

# 3. PRODUCT VISION

## What Meridian Becomes in 10 Years

**Year 1–2:** Consumer decision tool. People bring their hardest choices — job offers, apartments, insurance plans, big purchases — and leave with clarity.

**Year 3–4:** Platform with memory. Meridian knows your financial profile, your career arc, your values, your past decisions and their outcomes. The recommendations are as personalized as advice from someone who has known you for years.

**Year 5–6:** Collaborative decision layer. Couples, co-founders, and families use Meridian as a shared reasoning space. It doesn't take sides — it surfaces where you agree, where you diverge, and what you each actually need.

**Year 7–10:** The decision OS. Embedded across financial platforms, HR tools, healthcare portals, and real estate services. Every consequential decision point in a person's digital life has a Meridian layer.

## Why This Is Bigger Than a Chatbot

A chatbot answers questions. Meridian solves a different problem entirely: it **models a person**, **classifies decisions**, **extracts values**, **weights criteria**, **simulates scenarios**, **quantifies risk**, and **generates transparent recommendations** — with a closed feedback loop that improves over time.

The difference is the difference between a search engine and a doctor. One gives you information. The other synthesizes it against your specific situation and tells you what to do about it.

## The "Operating System for Decisions" Concept

USER OPENS APP
│
▼
"What are you trying to decide?"
│
▼
User types freely (freeform dump mode)
│
▼
System parses: decision type, options, concerns, missing info
│
▼
First structured output: "Here's how I understand your decision..."
│
▼
One clarifying question (never two)
│
▼
Preliminary analysis delivered
│
▼
Profile building happens silently in the background

The user is never aware of being onboarded. Onboarding IS the first decision.

---

## Decision Intake Modes

### Mode 1 — Freeform Dump
User writes or speaks naturally. System structures it.

INPUT:  "I'm trying to decide whether to take this job offer.
It pays more but it's a startup and I'm not sure if
I should leave my current place..."
SYSTEM PARSES:
├── Decision Type: Career / Job Change
├── Options: [Take Offer] [Stay Current]
├── Stated Concerns: Stability, Compensation
├── Unstated Concerns: Identity, Risk Tolerance
├── External Influences: Partner preference mentioned
└── Missing Info: Equity package, startup stage, current comp


### Mode 2 — Structured Template
Optional fast-lane for users who want precision. Category-specific templates surface the right questions for that domain.

### Mode 3 — Document Upload
Upload offer letters, insurance PDFs, product spec sheets. System extracts structured data and feeds it into the analysis engine.

### Mode 4 — URL / Reference Input
Paste links to apartments, products, or funds. System fetches, parses, and structures.

### Mode 5 — Voice
Natural speech, same underlying engine. For in-store, in-call, or in-moment decisions.

### Mode 6 — Recurring Templates
For repeat decision types (weekly dinner plans, quarterly contractor hiring), templates pre-load context and skip to the specific options.

---

## Core Recommendation Flow

DECISION RECEIVED
│
▼
┌─────────────────────────────────────────┐
│  CLASSIFICATION LAYER                   │
│  Domain / Reversibility / Stakes /      │
│  Time Horizon / Social Complexity       │
└─────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────┐
│  VALUE EXTRACTION                       │
│  Stated + Domain-standard + Profile     │
│  derived + Downstream + Social criteria │
└─────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────┐
│  WEIGHTING ENGINE                       │
│  User input + Inferred from history +   │
│  Trade-off calibration exercises        │
└─────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────┐
│  TRADE-OFF MATRIX + SCENARIO SIMULATION │
│  Best / Most Likely / Worst case        │
│  Sensitivity analysis on key weights    │
└─────────────────────────────────────────┘
│
▼
┌─────────────────────────────────────────┐
│  RECOMMENDATION GENERATION              │
│  One-sentence answer                    │
│  Reasoning narrative                    │
│  Key trade-offs acknowledged            │
│  Decisive factor named                  │
│  What would change my mind              │
│  Confidence level + explanation         │
└─────────────────────────────────────────┘
│
▼
POST-DECISION FOLLOW-UP (30 days)

---

## Trust-Building Mechanisms

| Mechanism | What It Does |
|---|---|
| **Reasoning Trace** | Every recommendation shows its inference chain — not hidden behind a toggle |
| **Assumption Disclosure** | "In making this, I assumed X, Y, Z. If those are wrong, here's the impact." |
| **Sensitivity Indicators** | Flags when a small preference shift would flip the recommendation |
| **Confidence Calibration** | Qualitative labels (Low / Moderate / High) with explicit uncertainty explanation |
| **What Would Change My Mind** | Teaches users to interrogate the recommendation, not just accept it |
| **Source Quality Labels** | Manufacturer spec vs. independent review vs. system estimate — always distinguished |

---

# 6. SYSTEM ARCHITECTURE

## High-Level Architecture

┌──────────────────────────────────────────────────────────────────────┐
│                        CLIENT LAYER                                  │
│        Web App │ Mobile App │ Voice Interface │ API Consumers        │
└────────────────────────────┬─────────────────────────────────────────┘
│
┌────────────────────────────▼─────────────────────────────────────────┐
│                      ORCHESTRATION LAYER                             │
│   Session Manager │ Intent Router │ Context Assembler │ Output Former │
└────────────────────────────┬─────────────────────────────────────────┘
│
┌──────────────────┼──────────────────┐
│                  │                  │
┌─────────▼──────┐  ┌────────▼───────┐  ┌──────▼────────────┐
│  DECISION      │  │  MEMORY &      │  │  KNOWLEDGE        │
│  ENGINE        │  │  PROFILE LAYER │  │  RETRIEVAL LAYER  │
│                │  │                │  │                   │
│ Classifier     │  │ User Profile   │  │ Domain KB         │
│ Value Extractor│  │ Decision Hist. │  │ Real-time Data    │
│ Weighting Sys  │  │ Preference     │  │ Market Data APIs  │
│ Scenario Sim   │  │ Model          │  │ Document Parser   │
│ Risk Modeler   │  │ Outcome Log    │  │ Web Fetcher       │
│ Rec Generator  │  │ Vector Store   │  │ RAG Pipeline      │
└────────────────┘  └────────────────┘  └───────────────────┘
│                  │                  │
┌─────────▼──────────────────▼──────────────────▼──────────────────────┐
│                         FOUNDATION LAYER                             │
│         LLM (Primary Reasoning) │ Embeddings │ Fine-tuned Classifiers│
└──────────────────────────────────────────────────────────────────────┘

---

## Memory Architecture

The **Decision Profile** is the core data asset of the product. It is not a form — it is a living model built through inference from conversation.

DECISION PROFILE
├── Life Context Layer
│   ├── Financial snapshot (bucketed, not exact)
│   ├── Life stage signals
│   ├── Geographic context
│   ├── Career and skills profile
│   └── Health context (volunteered only)
│
├── Preference Layer
│   ├── Stated preferences (explicit)
│   ├── Inferred preferences (behavioral)
│   └── Stated vs. revealed preference delta
│
└── History Layer
├── Past decisions log
├── Decision category models
└── Outcome feedback

**Storage Architecture:**

| Data Type | Storage | Notes |
|---|---|---|
| User Profile | PostgreSQL (structured) | Bucketed financial data, preferences |
| Conversation History | Vector DB (pgvector / Pinecone) | Semantic retrieval for context assembly |
| Decision Records | PostgreSQL + JSONB | Full reasoning trace stored per decision |
| Outcome Feedback | PostgreSQL | Links decisions to follow-up data |
| Domain Knowledge | Vector DB + fine-tuned retrievers | Category-specific fact bases |

---

## AI Stack

| Component | Technology Options | Notes |
|---|---|---|
| **Primary Reasoning** | GPT-4o / Claude 3.5 / Gemini 1.5 Pro | Multi-provider for redundancy |
| **Classification** | Fine-tuned small model (Mistral 7B) | Speed, cost efficiency |
| **Embeddings** | text-embedding-3-large / Cohere | Profile and history retrieval |
| **Vector Store** | Pinecone / pgvector | Similarity search for past decisions |
| **Document Parsing** | LlamaParse / Unstructured.io | For uploads (PDFs, screenshots) |
| **Web Retrieval** | Firecrawl / custom fetcher | URL-based option intake |
| **Orchestration** | LangGraph / custom agent framework | Multi-step reasoning coordination |

---

## Privacy & Security Architecture

DATA PRINCIPLES
├── Financial data: bucketed ranges only, never exact figures
├── Health data: volunteered only, stored encrypted, never used for ads
├── Conversation data: encrypted at rest and in transit
├── Profile data: user-owned, exportable, deletable on demand
└── Outcome data: opt-in only, anonymized for aggregate modeling

**> Engineering Note:** Profile inference must be transparent to users — they can view, correct, and delete any inferred attribute. The system never uses profile data as opaque weights — every personalization must be explainable on request.

**> Business Note:** Privacy architecture is not just ethical compliance — it is a core competitive differentiator. Users share deeply personal information with Meridian. The trust built by transparent data handling is directly correlated with depth of engagement and willingness to pay.

---

# 7. THE DECISION ENGINE

## How the System Thinks — Step by Step

### Step 1 — Decision Classification

Every incoming decision is classified across six dimensions before any reasoning begins:

CLASSIFICATION DIMENSIONS

DOMAIN
Financial │ Career │ Relational │ Health │ Logistics
Consumer  │ Travel │ Educational│ Legal  │ Housing
REVERSIBILITY
◆ Two-way door  → Low caution, faster reasoning
◆ One-way door  → High caution, deeper probing
◆ Irreversible  → Maximum depth, explicit regret modeling
STAKES
Low ($0–$200, easily undone)
Medium ($200–$5k or moderate life impact)
High ($5k+ or significant life impact)
Critical (health, major financial, irreversible)
TIME HORIZON
Immediate (< 24 hours) → compressed mode
Short (< 2 weeks)      → standard mode
Open                   → full depth mode
SOCIAL COMPLEXITY
Solo decision
One stakeholder
Multiple stakeholders with divergent interests
INFORMATION COMPLETENESS
What % of decision-relevant data does the system have?
Surfaced to user: "I can give you a strong recommendation,
but I'm missing X and Y — here's how that affects confidence."

---

### Step 2 — Value Extraction

Before comparing options, the engine establishes the full criterion set:

| Criterion Type | Source | Example |
|---|---|---|
| **Stated** | User explicitly mentions | "I want it under $1,000" |
| **Domain-standard** | Expert knowledge base | Battery life, repairability for phones |
| **Profile-derived** | User history + preferences | Privacy sensitivity → data practices matter |
| **Downstream** | Second-order consequence modeling | Cheaper apartment → longer commute → fewer hours for health |
| **Social** | Stakeholder context | Partner needs to be comfortable with this too |

---

### Step 3 — Weighting Engine

WEIGHT ASSIGNMENT HIERARCHY

Explicit user input  ──────────────────────► Highest weight
"Price is most important to me"
Trade-off calibration exercises  ──────────► High weight
"Would you rather have 20% more storage
or 20% longer battery?"
Revealed preferences from history  ────────► Medium weight
Always chooses extended warranty
→ Risk aversion flag set
Stated-vs-revealed delta  ─────────────────► Adjusted weight
Says price matters most, but history shows
quality choices → quality weighted up,
user informed of the gap
Domain-standard defaults  ─────────────────► Baseline weight
Used when profile is sparse


---

### Step 4 — Trade-Off Matrix Analysis

The engine evaluates every option against every weighted criterion, then interprets the matrix:

**What the engine looks for:**

| Pattern | Response |
|---|---|
| **Dominant option** | One option wins on most criteria with no significant losses → state this clearly and directly |
| **Sensitive trade-off** | Small preference shift flips the recommendation → flag explicitly |
| **False trade-off** | Options aren't actually comparable (e.g. monthly vs. annual pricing confusion) → surface the equivalence |
| **Missing option** | Neither option is optimal → propose alternative |
| **Hidden costs** | Costs not in sticker price → surface installation, cancellation, time, cognitive load |

---

### Step 5 — Risk & Scenario Modeling
FOR EACH OPTION:
BEST CASE
│   What has to go right?
│   How likely is it?
│   How good is it?
MOST LIKELY CASE
│   What actually happens most of the time?
│   For this specific user's context?
WORST CASE
│   What could go wrong?
│   How bad would it be for this user specifically?
│   How does this user's financial/emotional profile
│   affect the severity?
KNOWN UNKNOWNS
│   What information is missing that would change this?
│   E.g. "If the startup doesn't raise Series B,
│   the equity is worth much less"
REGRET MODEL
│   Which choice would this user regret more if wrong?
│   Calibrated to their regret aversion profile.

---

### Step 6 — Recommendation Generation

Every recommendation is delivered in a structured six-part format:
┌─────────────────────────────────────────────────────────┐
│  THE RECOMMENDATION                                     │
├─────────────────────────────────────────────────────────┤
│  1. ONE-SENTENCE ANSWER                                 │
│     "Take the job offer."                               │
│     No hedging. No waffling. A clear position.         │
│                                                         │
│  2. THE REASONING                                       │
│     Narrative, not bullet list. Walks through the      │
│     key inference chain from their values to this      │
│     conclusion.                                         │
│                                                         │
│  3. KEY TRADE-OFFS                                      │
│     2–3 things you give up. Acknowledged fully,        │
│     not minimized.                                      │
│                                                         │
│  4. THE DECISIVE FACTOR                                 │
│     "The thing that tips this is your stated           │
│     preference for growth over stability."              │
│                                                         │
│  5. WHAT WOULD CHANGE MY MIND                          │
│     Explicit list of conditions that flip the call.    │
│     Gives user agency and teaches reasoning.           │
│                                                         │
│  6. CONFIDENCE LEVEL                                    │
│     LOW / MODERATE / HIGH / VERY HIGH                  │
│     With specific explanation of uncertainty source.   │
└─────────────────────────────────────────────────────────┘

---

# 8. DESIGN SYSTEM PHILOSOPHY

## Core Interface Philosophy: Calm Intelligence

Meridian's visual and interaction design is built around a single concept: **cognitive offloading without cognitive dependency**. The interface should feel like a well-lit workspace, not an exciting application.

> Design goal: When the user leaves a Meridian session, they feel **clearer**, not more stimulated.

## Design Principles

| Principle | Implementation |
|---|---|
| **Transparency first** | Reasoning is the primary content, not a secondary toggle |
| **Controlled density** | Complex analysis delivered progressively, not all at once |
| **Emotional safety** | No judgment signals in copy, color, or iconography |
| **Confidence visualization** | Uncertainty is visualized, not hidden |
| **Actionability** | Every screen ends with a clear next step |

---

## Layout Concepts

### Desktop — Three-Panel Layout
┌─────────────┬─────────────────────────────┬───────────────┐
│  DECISION   │    MAIN ANALYSIS AREA        │  CONTEXT      │
│  HISTORY    │                             │  PANEL        │
│             │  ┌─────────────────────┐    │               │
│  Past       │  │  THE RECOMMENDATION │    │  Your Profile │
│  decisions  │  │  ─────────────────  │    │  ─────────── │
│  browsable  │  │  One-sentence answer│    │  Financial    │
│             │  │                     │    │  snapshot     │
│  Grouped    │  │  REASONING          │    │               │
│  by domain  │  │  ─────────────────  │    │  Past similar │
│             │  │  Narrative trace    │    │  decisions    │
│             │  │                     │    │               │
│             │  │  TRADE-OFFS         │    │  Assumptions  │
│             │  │  ─────────────────  │    │  being made   │
│             │  │  ◆ What you gain    │    │               │
│             │  │  ◆ What you give up │    │  Confidence   │
│             │  │                     │    │  breakdown    │
│             │  │  CONFIDENCE  ████░░ │    │               │
│             │  └─────────────────────┘    │               │
└─────────────┴─────────────────────────────┴───────────────┘

### Mobile — Conversational-First, Reveal on Scroll
┌─────────────────────────┐
│  MERIDIAN               │
│  ─────────────────────  │
│                         │
│  "Here's how I see your │
│  decision..."           │
│                         │
│  ┌─────────────────┐    │
│  │ RECOMMENDATION  │    │
│  │ Take the offer  │    │
│  └─────────────────┘    │
│                         │
│  WHY ▼                  │
│  ─────────────────────  │
│  [Expanded reasoning]   │
│                         │
│  TRADE-OFFS ▼           │
│  ─────────────────────  │
│                         │
│  WHAT WOULD CHANGE      │
│  THIS? ▼                │
│                         │
│  [ Ask a follow-up ]    │
└─────────────────────────┘

---

## Trade-Off Visualization

For decisions with multiple weighted criteria, the system renders a visual trade-off summary:
YOUR PRIORITIES vs. HOW OPTIONS SCORE
                Option A    Option B
Price         ██░░░    ★★★★★      ★★☆☆☆
Battery Life  ████░    ★★★☆☆      ★★★★★
Camera        ███░░    ★★★★☆      ★★★☆☆
Repairability █░░░░    ★★★★★      ★★★☆☆
Software Upd  ██░░░    ★★★☆☆      ★★★★★
Bar = your weight for that criterion
Stars = how each option scores
VERDICT: Option A dominates on your weighted priorities.
The camera gap is real but your weight there is low.

---

## Confidence Visualization
CONFIDENCE IN THIS RECOMMENDATION
Very High ████████████
High  █████████░░░ ◄ Current
Moderate  ██████░░░░░░
Low  ███░░░░░░░░░
What's driving uncertainty:
◆ I don't have your current comp to compare against
◆ Equity value depends on a future funding event
What would raise confidence to Very High:
→ Tell me your current total comp
→ Share the startup's last funding round details

---

# 9. FEATURE BREAKDOWN

## MVP — What You Ship to Validate the Core

| Feature | User Value | Business Value | Complexity |
|---|---|---|---|
| Freeform decision intake | Zero friction entry | Broad top-of-funnel | Low |
| Decision classification | Structured analysis from messy input | Enables domain-specific reasoning | Medium |
| Criterion extraction (stated + domain) | Surfaces what actually matters | Core value delivery | High |
| Trade-off matrix | Visual clarity on complex comparisons | Primary engagement hook | High |
| Six-part recommendation output | Clear answer with reasoning | Trust and retention driver | High |
| Basic user profile (session-level) | Personalized within session | Foundation for long-term moat | Medium |
| Post-decision follow-up prompt | Closes feedback loop | Outcome data collection | Low |

**MVP Success Criterion:** A first-time user with no profile history gets a recommendation they find genuinely more useful than a Google search or ChatGPT conversation.

---

## V1 — Building the Moat

| Feature | User Value | Business Value | Complexity |
|---|---|---|---|
| Persistent Decision Profile | Personalization that improves over time | Core retention and switching cost | High |
| Decision History + Journal | "Regret archive" — look back on past reasoning | Long-term engagement; unique data asset | Medium |
| Domain-specific frameworks (Financial, Career, Housing, Consumer) | Expert-level analysis per category | Category expansion; PR positioning | Very High |
| Document / URL intake | Analyze real offer letters, specs, pages | Differentiates from pure chatbots | High |
| Confidence + sensitivity visualization | Transparent uncertainty communication | Trust building; premium signal | Medium |
| 30-day follow-up system | Outcome data + habit formation | Data flywheel; re-engagement | Medium |
| "What would change my mind" output | Teaches reasoning; builds agency | Reduces churn from bad outcomes | Low |

---

## V2 — Platform Expansion

| Feature | User Value | Complexity |
|---|---|---|
| Collaborative decision mode (couples, partners) | Shared reasoning space | Very High |
| Debate mode | Steelman the opposite of your current lean | Medium |
| Pre-mortem generation | "Imagine it went wrong — what happened?" | Medium |
| Proactive decision alerts | "Your lease renews in 60 days..." | High |
| Downstream consequence visualization | Second-order effects surfaced visually | High |
| Commitment device creation | Follow-through support post-decision | Medium |
| Salary negotiation scripts | From decision to implementation | Medium |
| Regret processing (post-bad-outcome support) | Good process vs. good outcome distinction | Medium |

---

## Future Moonshots

| Feature | Vision |
|---|---|
| **Multi-agent domain specialists** | Separate AI agents per domain (financial, legal, medical) coordinated by Meridian's orchestration layer |
| **Outcome prediction calibration** | Track actual vs. predicted outcomes to publicly report recommendation accuracy by category |
| **Life simulation mode** | "If you make this choice, here's what your financial profile looks like in 5 years" |
| **Family decision OS** | Shared household profile with individual private layers; surfaces family-level alignment |
| **Expert marketplace** | Connect to verified human advisors for decisions beyond AI confidence threshold |
| **Anonymized community benchmarks** | Opt-in: "Here's how people with similar profiles resolved this type of decision" |
| **API layer** | Meridian's reasoning engine embedded in financial platforms, HR tools, real estate portals |

---

# 10. MONETIZATION STRATEGY

## Pricing Architecture
FREE TIER
├── Up to 5 decisions/month
├── Session-level profile only (no persistence)
├── Standard recommendation format
└── Purpose: acquisition, habit formation, viral distribution
PRO — $12/month or $99/year
├── Unlimited decisions
├── Persistent Decision Profile
├── Full domain frameworks (financial, career, housing, health)
├── Decision History & Journal
├── Document and URL intake
├── 30-day follow-up system
└── Purpose: primary revenue driver; high LTV for engaged users
PREMIUM — $29/month or $249/year
├── Everything in Pro
├── Collaborative decision mode (up to 4 people)
├── Debate mode & Pre-mortem generation
├── Priority processing
├── Export to PDF/shareable format
└── Purpose: power users, couples, small teams
TEAM / STARTUP — $79/month (up to 10 seats)
├── Shared workspace with individual profiles
├── Team decision tracking
├── Founder-specific frameworks
└── Purpose: B2B expansion, higher ACV
ENTERPRISE — Custom
├── API access to decision engine
├── White-label options
├── Custom domain frameworks
├── SSO, compliance, audit logs
└── Purpose: embedded in HR, financial, healthcare platforms

---

## Monetization Risks and Mitigations

| Risk | Mitigation |
|---|---|
| Users trust free tier and never upgrade | Gate the most valuable features (persistence, document intake) firmly behind Pro |
| Recommendation failures erode willingness to pay | Confidence calibration transparency; explicit "what I don't know" disclosures |
| Enterprise clients want to own the AI layer | Partner model rather than compete; provide reasoning API they embed |
| Users feel manipulated if they sense commercial bias | Zero advertising model; no affiliate recommendations; explicit policy |

**> Business Note:** Meridian's ethical constraint is also its business constraint: the moment a user suspects a recommendation is influenced by commercial considerations, trust collapses. No affiliate model. No sponsored placements. Revenue comes from users, not from the options they're evaluating.

---

# 11. GO-TO-MARKET STRATEGY

## Positioning

> **Meridian is not an AI assistant. It's a thinking partner.**

The positioning deliberately avoids "AI" as the lead message — because the category is crowded and the differentiator is not the AI, it's the **methodology** and the **memory**.

Messaging hierarchy:
1. **For skeptics:** "Finally clear on a decision you've been stuck on for weeks."
2. **For aspirational users:** "Think like the most rational version of yourself."
3. **For trust-builders:** "Not just an answer. A reason you can actually trust."

---

## Launch Strategy

**Phase 1 — Waitlist + Content**
- Publish the decision framework publicly (blog, newsletter, Twitter/X threads)
- "The 8 reasons your decisions fail" — organic content that establishes intellectual authority
- Build waitlist through content; target 10k signups before launch

**Phase 2 — Closed Beta**
- 500 users across 3 core personas: Ambitious Professionals, First-Generation Wealth Builders, Founders
- Optimize for decision quality and trust metrics before opening up
- NPS target: >60 before public launch

**Phase 3 — Public Launch**
- Product Hunt as amplification, not acquisition
- Partnership with newsletters in the personal finance, career, and productivity spaces
- Referral loop: "Share this analysis" generates branded content that brings in new users

---

## Growth Loops
CORE VIRAL LOOP
User gets a great recommendation
│
▼
User shares the analysis with someone involved in the decision
│
▼
That person sees the reasoning quality
│
▼
That person signs up to analyze their own decision
│
▼
Loop repeats

CONTENT LOOP
Meridian publishes category-specific decision guides
(How to evaluate a job offer / How to compare health insurance)
│
▼
Ranks on search for high-intent queries
│
▼
Readers convert to free tier to apply the framework to their situation
│
▼
Free tier experience converts to Pro

---

## Retention Loops

| Loop | Mechanism |
|---|---|
| **Decision History** | The longer you use it, the richer your profile — leaving means losing your history |
| **Follow-up Loops** | 30-day check-ins bring users back to close the feedback loop |
| **Proactive Alerts** | Upcoming lease renewals, subscription anniversaries — Meridian initiates re-engagement |
| **Journal Value** | "Your decision archive" becomes a genuinely meaningful personal record |

---

# 12. COMPETITIVE ANALYSIS

## The Landscape

| Competitor | What They Do | Why Meridian Is Different |
|---|---|---|
| **ChatGPT / Claude** | General-purpose conversation | No user model, no methodology, no memory, no structured output format |
| **Perplexity** | Search with AI synthesis | Information retrieval, not decision reasoning; no personalization |
| **Notion AI** | Writing and organization assistant | No decision-specific framework; no profile; no trade-off modeling |
| **NerdWallet / Wirecutter** | Category-specific comparison | Commercial bias risk; no personalization; no reasoning; category-locked |
| **Spreadsheets** | DIY decision modeling | Requires expertise to build; no intelligence; no profile; high friction |
| **Therapists / Coaches** | Human reasoning support | Expensive; limited to specialty; unavailable in-moment; not scalable |
| **Rewind / Memory tools** | Personal data capture | No reasoning layer; retrieval without analysis |

## Meridian's Defensible Differences
WHAT NO ONE ELSE HAS — ALL AT ONCE

A structured methodology purpose-built for decisions
A persistent user model that improves with every interaction
Domain-specific reasoning frameworks (not generic conversation)
Transparent reasoning traces (not black-box answers)
A closed feedback loop through outcome tracking
The ability to model trade-offs across weighted user-specific criteria


The critical insight: **Meridian's competitors are tools that can be used for decisions. Meridian is a tool built for decisions.** That specificity is the moat.

---

# 13. RISK ANALYSIS

## Risk Register

### Hallucination and Factual Errors

| Risk | Severity | Likelihood |
|---|---|---|
| System states incorrect facts (wrong APR, wrong product spec) | Critical | Medium |

**Mitigation:**
- Source quality labels on all factual claims
- Retrieval-augmented generation (RAG) for factual claims — never rely on model memory alone
- Explicit confidence distinction between facts, estimates, and inferences
- User correction mechanism for stated facts; corrections fed back to profile

---

### Liability Risk

| Risk | Severity | Likelihood |
|---|---|---|
| User makes a bad financial/health decision and attributes it to Meridian | High | Low-Medium |

**Mitigation:**
- Clear "not financial advice / not medical advice" framing — not in fine print, but structurally integrated into the recommendation format
- Recommend professional consultation for high-stakes, irreversible decisions
- Explicit "I don't know" outputs when confidence is low — never confabulate certainty
- Document the recommendation process, not just the output, so users understand the basis

---

### Emotional Dependency

| Risk | Severity | Likelihood |
|---|---|---|
| Users become unable to make any decision without consulting Meridian | Medium | Medium |

**Mitigation:**
- Product design explicitly builds user decision-making skills, not just decisions
- "What would change my mind" feature teaches independent reasoning
- The system occasionally notes when a decision is low-stakes enough to just make
- Avoid AI-companion language patterns that encourage emotional attachment

---

### Privacy Breach

| Risk | Severity | Likelihood |
|---|---|---|
| Sensitive user data (financial, health, relational) is exposed | Critical | Low |

**Mitigation:**
- Data minimization: store bucketed ranges, not exact figures
- End-to-end encryption; data segmented by user
- No third-party data sharing (commercial policy, not just technical policy)
- Full data export and deletion on user request
- Regular third-party security audits

---

### Manipulation via Framing

| Risk | Severity | Likelihood |
|---|---|---|
| System systematically frames recommendations in ways that serve commercial interests | High | Low (if designed correctly) |

**Mitigation:**
- Zero affiliate or sponsored placement model — revenue from users only
- Reasoning traces make the basis for any recommendation inspectable
- Regular third-party audits of recommendation patterns for systematic bias

---

### Over-Reliance on AI for High-Stakes Decisions

| Risk | Severity | Likelihood |
|---|---|---|
| User follows a recommendation on a medical or legal matter without appropriate expert consultation | High | Medium |

**Mitigation:**
- Health and legal domains clearly scoped: frameworks and question preparation, not recommendations
- Automatic referral to professional consultation above a defined stakes threshold
- System detects crisis states and shifts to resource provision, not analysis

---

# 14. SUCCESS METRICS

## North Star Metric

> **Weekly Active Deciders** — Users who complete at least one meaningful decision session per week

This captures both engagement (active use) and product success (decisions being made, not just conversations being had).

---

## Metric Framework

### Acquisition
| Metric | Target (Month 6) |
|---|---|
| Waitlist signups | 10,000 |
| Free tier users | 5,000 |
| Week-1 activation rate | >60% |

### Retention
| Metric | Target |
|---|---|
| Day-7 retention | >40% |
| Day-30 retention | >25% |
| Month-3 retention (Pro) | >70% |
| Profile depth score (avg # of inferred attributes) | >12 by week 4 |

### Trust
| Metric | Target |
|---|---|
| Recommendation acceptance rate | >65% |
| "Reasoning was helpful" rating | >4.2/5 |
| NPS | >60 at Pro tier |
| User-initiated corrections to profile | Tracked; high number = good (engagement), high error rate = bad (accuracy issue) |

### Decision Quality
| Metric | Target |
|---|---|
| 30-day follow-up completion rate | >40% |
| Positive outcome rate (user-reported) | >70% |
| Recommendation confidence calibration accuracy | >80% (confidence level matches outcome rate) |

### Business
| Metric | Target |
|---|---|
| Free to Pro conversion | >8% within 60 days |
| Monthly churn (Pro) | <4% |
| ARR per Pro user | $99–$120 |

---

# 15. IMPLEMENTATION ROADMAP

## Phase 0 — Foundation (Months 1–2)

**Goal:** Core reasoning engine works reliably for 3 decision types.

| Workstream | Milestones |
|---|---|
| **Engineering** | LLM orchestration layer; basic decision classifier; 3 domain frameworks (career, financial, consumer); session-level profile |
| **Design** | Core recommendation output format; freeform intake UX; mobile + desktop layouts |
| **Product** | Decision framework documented; quality rubric defined; test suite of 50 annotated decisions |
| **Hiring** | ML Engineer, Full-Stack Engineer, Product Designer |

---

## Phase 1 — Alpha (Months 3–4)

**Goal:** 100 internal users; profile persistence; recommendation quality validated.

| Workstream | Milestones |
|---|---|
| **Engineering** | Persistent Decision Profile; vector store for history; document upload parsing; confidence scoring |
| **Design** | Trade-off visualization; confidence visualization; decision history UI |
| **Product** | NPS baseline established; qualitative interview program (10 users/week); recommendation accuracy tracking |
| **Hiring** | Data Engineer, UX Researcher |

---

## Phase 2 — Beta (Months 5–7)

**Goal:** 500 external beta users; Pro tier validated; retention loops proven.

| Workstream | Milestones |
|---|---|
| **Engineering** | 6+ domain frameworks; 30-day follow-up system; URL/web intake; profile inference engine |
| **Design** | Collaborative mode UX; proactive alert design; mobile app v1 |
| **Product** | Day-30 retention >25%; recommendation acceptance >65%; NPS >50 |
| **Business** | Pricing model validated; Pro conversion rate established |

---

## Phase 3 — Public Launch (Months 8–10)

**Goal:** Public launch; 5,000 Pro users; press and content distribution.

| Workstream | Milestones |
|---|---|
| **Engineering** | Performance hardening; API rate limiting; security audit; v2 domain frameworks |
| **Marketing** | Content program live; partnership with 3 newsletters; Product Hunt launch |
| **Product** | Full domain coverage (8 categories); collaborative mode live; debate mode live |
| **Business** | Team plan launched; first enterprise conversation initiated |

---

## Phase 4 — Scale (Months 11–18)

**Goal:** 50,000 Pro users; API partnerships; international expansion.

| Workstream | Milestones |
|---|---|
| **Engineering** | Multi-agent architecture for domain specialists; API layer; enterprise SSO; multi-language support |
| **Product** | Expert marketplace v1; community benchmarking (opt-in); life simulation mode scoped |
| **Business** | First enterprise contract signed; Series A preparation |
| **Hiring** | Head of Growth, Enterprise Sales Lead, 3× Engineering |

---

# 16. FINAL PRODUCT THESIS

## Why This Matters

Every life is, at its core, a sequence of decisions. What to study. Where to live. Who to commit to. What risk to take. When to leave. When to stay.

And yet — despite the fact that decisions are the fundamental unit of a life — we have built almost no infrastructure to help people make them better. We have encyclopedias of information. We have tools to execute on choices. We have therapists for the aftermath.

But in the moment of decision — standing at the fork in the road, holding two futures in uncertain hands — we are mostly alone. We Google. We ask Reddit. We call a friend who knows less than we do. We make a spreadsheet we don't quite trust. We sleep on it. We decide.

And then we live with it.

## Why Now

This has always been true. What has changed is that the tools to fix it now exist.

A system that genuinely knows you — your financial reality, your values, your history of choices and their outcomes — and can apply structured reasoning to the specific decision in front of you is no longer science fiction. It is an engineering and product challenge. A hard one. But a solvable one.

## Why Meridian

The difference between Meridian and everything that has come before is not the AI. It is the **specificity of purpose**. Every design decision, every technical choice, every product constraint in this document exists in service of one thing: helping real humans make better decisions.

Not faster information retrieval. Not a smarter chatbot. Not another productivity tool.

A thinking partner. One that knows you well enough to know what questions to ask. Rigorous enough to surface what you missed. Transparent enough to be challenged. And humble enough to tell you when it doesn't know.

## The Long Bet

In ten years, the decisions that define a life will not be made alone. They will be made with a system that has walked every significant choice with you — that has earned trust through accuracy, transparency, and genuine understanding of who you are.

That system will know that you tend to underweight long-term financial consequences. That you overweight social opinion. That you perform better in decisions when you've had 48 hours, not 4. That the last time you took the high-risk path, it worked — and the time before that, it didn't.

It will use all of that — not to decide for you, but to help you decide as the most rational, most self-aware, most well-informed version of yourself.

That is Meridian.

And the decision to build it — we believe — is one of the clearest we could make.

---

*Built for those who believe that better reasoning leads to better lives.*  
*Meridian — Decision Intelligence for Every Fork in the Road.*

---

> **Document Status:** Living specification. Updated as product evolves.  
> **Owner:** Het Doshi
