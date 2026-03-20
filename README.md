# 🏠 Apex Property Group — HubSpot Expert Portfolio Project

> **Owner:** Rahul Duvedi
> **Goal:** Transition from React Developer → Complete HubSpot Expert
> **Timeline:** 12 Weeks (6–10 hrs/week)
> **Target Roles:** HubSpot Admin, CRM Admin, Marketing Specialist, Marketing Ops, RevOps

---

## 📋 Claude Context Prompt
> Copy everything inside the box below and paste it at the start of any new Claude conversation to instantly restore context.

```
CLAUDE CONTEXT — RAHUL'S HUBSPOT PROJECT

Personal Info:
- Name: Rahul Duvedi
- Current role: React Developer
- Career goal: Become a complete HubSpot expert (all hubs, all roles)
- GitHub: github.com/duvedirahul

Project:
- Building a full HubSpot CRM implementation for a fictional real estate 
  investment company called "Apex Property Group"
- Website: Plain HTML/CSS/JS — 3 pages (Home, About, Contact)
- Hosted on GitHub Pages at: duvedirahul.github.io/[repo-name]
- HubSpot free account connected to the website contact form

12-Week Roadmap:
- Week 1–2:   Phase 1 — CRM Foundation
- Week 3–5:   Phase 2 — Marketing Hub
- Week 6–7:   Phase 3 — Sales Hub
- Week 8:     Phase 4 — Service Hub
- Week 9–10:  Phase 5 — Operations Hub + Integrations
- Week 11–12: Phase 6 — Reporting + Portfolio Polish

HubSpot Certifications Target (all free at academy.hubspot.com):
1. HubSpot CRM
2. HubSpot Marketing Software
3. Email Marketing
4. HubSpot Sales Software
5. HubSpot Service Software
6. HubSpot Operations Software
7. HubSpot Reporting
8. Inbound Marketing

Current Status:
- Current Phase: [UPDATE THIS EVERY WEEK]
- Current Week: [UPDATE THIS EVERY WEEK]
- Certifications completed: [UPDATE THIS]
- Last thing I completed: [UPDATE THIS EVERY SESSION]
- Next step / what I need help with: [UPDATE THIS EVERY SESSION]

Please help me continue from where I left off based on the current status above.
```

---

## 🎯 Project Overview

### The Business Story
Apex Property Group is an Australian real estate investment advisory firm helping everyday Australians build wealth through property investment.

**The master narrative for interviews:**
> *"I did a full HubSpot implementation for a real estate investment company — from connecting their website and capturing leads, all the way to automated nurturing, sales pipeline, customer service, and third-party integrations. I can show you the live website, the HubSpot portal, and walk you through every business problem I solved and why I made each decision."*

### Tech Stack
| Component | Tool |
|---|---|
| Website | Plain HTML / CSS / JS |
| Hosting | GitHub Pages |
| CRM | HubSpot (Free + Marketing Starter) |
| Integrations | Calendly, Gmail, Slack, Zapier, HubSpot API |
| Documentation | This GitHub repo |

---

## 🗺️ 12-Week Roadmap

---

### ✅ Phase 1 — CRM Foundation (Week 1–2)
**⏱ ~8 hrs | Certification: HubSpot CRM**

#### Business Problem
> *"Apex Property Group had no centralised system — leads came in via a website form but went nowhere. No tracking, no follow-up, no visibility."*

#### What to Build
- [ ] Connect GitHub Pages website form to HubSpot
- [ ] Create custom Contact properties:
  - Investment budget range
  - Number of properties currently owned
  - State / territory
  - Investment goal (capital growth vs rental yield)
  - Lead source
- [ ] Set up Company and Deal object properties
- [ ] Define Lifecycle Stages:
  ```
  Subscriber → Lead → MQL → SQL → Opportunity → Client → Evangelist
  ```
- [ ] Import 50 sample contacts to make portal look real
- [ ] Build first Active List — "All leads from website form"

#### Result to Document
- ❌ Before: Leads lost, zero visibility, no assignment
- ✅ After: Every lead tracked, segmented, and assigned automatically

---

### 📧 Phase 2 — Marketing Hub (Week 3–5)
**⏱ ~20 hrs | Certifications: HubSpot Marketing Software + Email Marketing**

#### Business Problem
> *"Leads were going cold within 48 hours because there was no structured nurture process. Sales reps were chasing leads manually with no consistency."*

#### What to Build

**Lead Segmentation — 3 Smart Lists:**
- 🟢 First-time investors (owns 0 properties)
- 🟡 Growing investors (owns 1–3 properties)
- 🔴 High-net-worth investors (owns 4+ properties)

**3 Email Nurture Sequences:**

| Segment | Email 1 | Email 2 | Email 3 |
|---|---|---|---|
| First-time | Welcome + free guide | How to get finance ready | Success story |
| Growing | Scale your portfolio | Tax benefits of property | Market update |
| High-net-worth | Portfolio diversification | Commercial vs residential | Exclusive event invite |

**Lead Scoring System:**
```
Form submitted          → +10 points
Email opened            → +2 points
Email link clicked      → +5 points
Revisited website       → +3 points
Meeting booked          → +20 points
Score reaches 30        → becomes MQL → notify sales rep
No activity for 14 days → score decays -5 points
```

**Workflows to Build:**
- [ ] New lead → welcome email → assign to rep → create deal
- [ ] Lead score hits 30 → move to MQL → internal notification
- [ ] No email open in 14 days → re-engagement → if no response → mark cold
- [ ] Contact birthday / anniversary → personalised email

#### Result to Document
- ❌ Before: 0% of leads nurtured, manual follow-up only
- ✅ After: 100% of leads enter automated sequence within 5 mins of form submission

---

### 💼 Phase 3 — Sales Hub (Week 6–7)
**⏱ ~12 hrs | Certification: HubSpot Sales Software**

#### Business Problem
> *"Sales reps had no pipeline visibility. Deals were tracked in spreadsheets. No one knew which leads were hot, which were dead, or how close they were to monthly targets."*

#### Sales Pipeline
```
New Lead
    ↓
Strategy Call Booked
    ↓
Call Completed
    ↓
Property Shortlisted
    ↓
Under Offer
    ↓
Settlement in Progress
    ↓
Won ✅ / Lost ❌
```

#### Deal Automations to Build
- [ ] Lead score hits 30 → Deal auto-created in "New Lead"
- [ ] Meeting booked → Deal moves to "Strategy Call Booked"
- [ ] Deal sits in same stage 7+ days → manager alert email
- [ ] Deal marked Lost → trigger 30-day win-back workflow
- [ ] Deal Won → trigger client onboarding sequence

**Sales Sequences for Reps:**
```
Day 0  → Auto email after strategy call
Day 2  → Follow-up if no reply
Day 4  → Personal video email prompt (task for rep)
Day 6  → Final follow-up email
Day 8  → Task: call manually
Day 10 → If no response → move to cold
```

**Reporting Dashboard — Sales:**
- [ ] Deals by stage (funnel view)
- [ ] Average days in each stage
- [ ] Conversion rate by lead source
- [ ] Monthly revenue forecast
- [ ] Rep performance leaderboard

#### Result to Document
- ❌ Before: Deals in spreadsheets, no forecast accuracy, reps flying blind
- ✅ After: Full pipeline visibility, automated stage moves, forecast within 10% accuracy

---

### 🎧 Phase 4 — Service Hub (Week 8)
**⏱ ~6 hrs | Certification: HubSpot Service Software**

#### Business Problem
> *"After a client signed up, there was no structured onboarding. Questions went to random email inboxes. Client satisfaction was never measured."*

#### What to Build

**Ticket Pipeline:**
```
New Query → In Progress → Awaiting Client → Resolved → Closed
```

**Knowledge Base — 5 Articles:**
- [ ] How to read your property report
- [ ] How to track your settlement progress
- [ ] Tax FAQ for property investors
- [ ] How to refer a friend
- [ ] How to update your contact preferences

**NPS Survey Workflow:**
- [ ] Triggered 30 days after deal is Won
- [ ] Score below 7 → create ticket → assign to senior rep immediately
- [ ] Score 9–10 → trigger referral request email

**Client Onboarding Workflow:**
```
Day 0  → Welcome email
Day 1  → Intro to your property strategist
Day 3  → Settlement checklist email
Day 14 → Check-in email
Day 30 → NPS survey
```

#### Result to Document
- ❌ Before: No post-sale process, complaints handled ad hoc, NPS unknown
- ✅ After: Structured onboarding, NPS tracked, issues auto-escalated within minutes

---

### ⚙️ Phase 5 — Operations Hub + Integrations (Week 9–10)
**⏱ ~14 hrs | Certification: HubSpot Operations Software**

#### Business Problem
> *"Data was siloed across tools — Calendly for bookings, Gmail for emails, spreadsheets for reporting. Nothing talked to each other. Reps were doing manual data entry every day."*

#### Integrations to Build

| Tool | Integration Type | What it Automates |
|---|---|---|
| Calendly | Native HubSpot | Meeting booked → Deal stage updates → rep notified |
| Gmail | Native HubSpot | All emails logged against contact automatically |
| Slack | HubSpot → Slack | New MQL → Slack message to sales channel |
| Zapier | Zapier → HubSpot | Connect tools HubSpot doesn't natively support |
| HubSpot API | Custom script | Push contacts from external source via REST API |

**Custom Code Workflow (technical differentiator):**
- [ ] Build a workflow with a custom code action (JS or Python)
- [ ] Example: Deal Won → auto-calculate commission based on property value → write back to Deal property
- [ ] This shows you go beyond clicking — you can code inside HubSpot

**Webhook Setup:**
- [ ] HubSpot webhook fires when contact becomes MQL
- [ ] Receive it in a Node.js or Python script
- [ ] Log it to Google Sheet or external database

#### Result to Document
- ❌ Before: 4 disconnected tools, manual data entry, frequent errors
- ✅ After: Single source of truth in HubSpot, all tools synced, zero manual data transfer

---

### 📊 Phase 6 — Reporting + Portfolio Polish (Week 11–12)
**⏱ ~10 hrs**

#### Executive Dashboard to Build
- [ ] Total leads this month
- [ ] MQL → SQL conversion rate
- [ ] Average deal close time
- [ ] Revenue closed vs forecast
- [ ] Top performing lead sources
- [ ] NPS score trend over time
- [ ] Email open rates by segment

#### GitHub Portfolio Structure
```
apex-property/
├── index.html
├── about.html
├── contact.html
├── ROADMAP.md
├── workflows/
│   ├── lead-nurture-workflow.png
│   ├── deal-automation-workflow.png
│   ├── onboarding-workflow.png
│   └── re-engagement-workflow.png
├── email-templates/
│   ├── welcome-email.html
│   ├── nurture-sequence-1.html
│   └── win-back-email.html
├── api-integration/
│   ├── webhook-receiver.js
│   ├── push-contacts.js
│   └── README.md
├── dashboards/
│   ├── sales-dashboard.png
│   ├── marketing-dashboard.png
│   └── executive-dashboard.png
└── docs/
    ├── business-problems.md
    ├── solutions-built.md
    └── results-achieved.md
```

---

## 🏆 Certifications Tracker

| # | Certification | Status | Completed On |
|---|---|---|---|
| 1 | HubSpot CRM | ⬜ Not started | — |
| 2 | HubSpot Marketing Software | ⬜ Not started | — |
| 3 | Email Marketing | ⬜ Not started | — |
| 4 | HubSpot Sales Software | ⬜ Not started | — |
| 5 | HubSpot Service Software | ⬜ Not started | — |
| 6 | HubSpot Operations Software | ⬜ Not started | — |
| 7 | HubSpot Reporting | ⬜ Not started | — |
| 8 | Inbound Marketing | ⬜ Not started | — |

> All free at [academy.hubspot.com](https://academy.hubspot.com)

---

## 📝 Weekly Progress Log

| Week | Phase | What I completed | What's next |
|---|---|---|---|
| 1 | — | — | — |
| 2 | — | — | — |
| 3 | — | — | — |
| 4 | — | — | — |
| 5 | — | — | — |
| 6 | — | — | — |
| 7 | — | — | — |
| 8 | — | — | — |
| 9 | — | — | — |
| 10 | — | — | — |
| 11 | — | — | — |
| 12 | — | — | — |

---

## 💼 Resume Summary (update as you complete phases)

```
HubSpot CRM Implementation — Apex Property Group (Personal Project)

• Built end-to-end HubSpot implementation covering Marketing, Sales,
  Service and Operations Hubs for a real estate investment company
• Designed lead scoring model reducing MQL qualification time by 80%
• Built 6 automated workflows handling lead nurture, deal progression,
  client onboarding and win-back campaigns
• Integrated Calendly, Gmail and Slack via native integrations
  and custom webhooks
• Created executive reporting dashboard tracking pipeline health,
  forecast accuracy and NPS across 200+ contacts
• Certified in 8 HubSpot disciplines
```

---

## 🎤 Key Interview Answers

**"Tell me about a HubSpot project you've worked on"**
> "I built a complete HubSpot implementation for a real estate investment company from scratch. The business had no CRM — leads were falling through the cracks, sales had no pipeline visibility, and there was zero post-sale process. I solved each of those problems across Marketing, Sales, Service and Operations Hub, and connected external tools like Calendly, Gmail and Slack via integrations and webhooks. I can walk you through the live portal and GitHub repo right now if you'd like."

**"What's the most complex workflow you've built?"**
> "A multi-branch lead nurture system that segments contacts into 3 investor profiles, applies lead scoring across 6 behaviours, and automatically hands off to sales when a lead hits 30 points — including a re-engagement branch for cold leads and a win-back sequence for lost deals."

**"How do you approach a new HubSpot implementation?"**
> "I start with the business problem, not the feature. I map out the full customer journey first — from first touch to post-sale — then work backwards to figure out which HubSpot tools solve each gap. I always document the before state, what I built, and the measurable after state."

---

*Last updated: [20/03/2026]*
