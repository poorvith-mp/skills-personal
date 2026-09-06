---
name: personal-crm
group: Life admin
description: >-
  Design a personal CRM: contact metadata, interaction logs, follow-up reminders and relationship
  strength. Use when maintaining professional relationships, staying in touch, or contact logs.
---

# personal-crm

## Core Philosophy
Professional networking feels dirty and transactional when it is treated as an opportunistic harvest—reaching out only when you need a job, an introduction, or an angel investment. A personal CRM is a long-term relationship infrastructure built on genuine curiosity, mutual respect, and value-first connection. By tracking interaction context, personal details, and periodic check-in rhythms, you nurture authentic professional friendships with zero awkwardness.

---

## 4-Step Personal CRM Architecture

### Step 1: Dunbar's Circles & Tiered Segmentation
1. **The Concentric Circle Model**:
   - *Tier 1: Core Circle (5–15 People)*: Close mentors, inner circle confidants, primary co-founders.
     - Check-in Cadence: Every 2–4 weeks.
   - *Tier 2: Key Network (50 People)*: Active collaborators, trusted industry peers, frequent sounding boards.
     - Check-in Cadence: Every 60–90 days.
   - *Tier 3: Broad Ecosystem (100–150 People)*: Former colleagues, investors, domain experts, acquaintance builders.
     - Check-in Cadence: Every 6 months or situational.

### Step 2: Contact Metadata & Information Architecture
1. **Essential Dossier Fields**:
   - *Basic*: Name, Current Company, Role, Location, Timezone.
   - *Context*: How you met (event, mutual intro, year).
   - *Personal Anchors*: Partner/spouse name, children, hobbies, sports teams, favorite books, non-tech passions.
   - *Professional Priorities*: What they are currently building, hiring for, or struggling with.
   - *Interaction Log*: Date, format (coffee, call, DM), and concise bullet points of what was discussed.
   - *Next Touchpoint*: Scheduled date and prompt topic.

### Step 3: The "Give-First" Low-Friction Touchpoint Playbook
1. **The 3 Legitimate Reasons to Reach Out**:
   - *The Relevant Artifact*: Sending a high-signal article, paper, or tool directly relevant to a problem they mentioned:
     - *"Saw this benchmark on ClickHouse query optimization and immediately thought of the scaling challenge you mentioned in June. Hope the sprint is going well!"*
   - *The Unsolicited Celebration*: Congratulating them on a shipped product, funding milestone, or talk with specific commentary (not generic "Congrats!").
   - *The High-Value Mutual Intro*: Connecting two people in your CRM who share complementary needs, with double-opt-in consent.
2. **The "No Reply Needed" Pressure Release**:
   - End low-friction check-ins with: *"No need to reply—just wanted to share this and hope you're crushing it!"* This removes cognitive burden and builds immense goodwill.

### Step 4: Maintenance Hygiene & Tooling
1. **Tooling Simplicity**:
   - Store in a plain Markdown folder, Notion database, or lightweight SQLite file. Avoid heavyweight corporate sales CRMs with automated marketing drip sequences.
2. **Weekly 15-Minute Relationship Sweep**:
   - Schedule 15 minutes during the Friday weekly review to review contacts due for check-ins and send 2–3 authentic messages.

---

## Deliverable Format: Personal CRM Dossier Template (`CONTACTS.md`)

```markdown
# Personal CRM & Relationship Dossier

## 1. Circle Cadence Overview
- **Tier 1 (Bi-weekly)**: [Names]
- **Tier 2 (Quarterly)**: [Names]
- **Tier 3 (Bi-annually)**: [Names]

## 2. Contact Record Template

### [Full Name] — Tier [1 / 2 / 3]
- **Role & Company**: [e.g. VP Engineering @ PlatformCorp]
- **Location**: [City, Timezone]
- **How We Met**: [e.g. Spoke at RustConf 2024; mutual friend of Dave]
- **Personal Anchors**: [Marathon runner, 2 dogs (Golden Retrievers), likes specialty coffee]
- **Current Focus**: [Migrating infra to bare metal; hiring Staff SRE]
- **Cadence**: [60 days] | **Last Contact**: [YYYY-MM-DD] | **Next Due**: [YYYY-MM-DD]

#### Interaction History
- **2026-06-12 (Coffee in SF)**:
  - Discussed their move away from AWS EKS. Recommended checking out Talos Linux.
  - Promised to send our internal benchmark on container boot times.
- **2026-01-15 (X DM)**:
  - Congratulated on their Series A announcement.

#### Action Item / Prompt for Next Touch
- Send article on bare-metal Kubernetes networking when published.
```

---

## Worked Example: High-Leverage Peer Check-In

- **Contact**: Senior Staff Engineer at target partner company.
- **Metadata Context**: Mentioned in March that they were struggling to hire a senior compiler engineer.
- **Action**: In May, spotted an exceptional compiler dev posting on Twitter/X that their startup shut down. Sent a quick intro with double opt-in.
- **Result**: Contact hired the engineer; relationship deepened into a strong technical partnership without ever making an awkward "sales" pitch.

---

## Verification Checklist

- [ ] Network is partitioned into realistic Dunbar tiers ($\le 15$ Tier 1, $\le 50$ Tier 2, $\le 150$ Tier 3).
- [ ] Every contact entry includes personal anchors and how you met.
- [ ] Outreach messages are value-first (sharing an artifact, congratulating, or intro) with zero immediate asks.
- [ ] "No reply needed" clause is used on casual check-ins to eliminate recipient guilt.
- [ ] CRM is stored in an open, portable format (Markdown / CSV / Notion) without spam automation.

---

## Anti-Patterns

- **The Desperation Ping**: Disappearing for 3 years and suddenly messaging: "Hey, can you refer me for a job at your company?"
- **Automated Drip Emails**: Treating personal relationships like automated marketing prospects with canned birthday emails.
- **Hoarding Contacts**: Storing 2,000 LinkedIn connections in a CRM whom you have zero intention of ever helping.
