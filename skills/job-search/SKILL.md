---
name: job-search
last_reviewed: 2026-09-06
group: Career
description: >-
  Run the application pipeline: target list, stage tracking, follow-up cadence and a weekly read
  on where applications die. Use when planning job search pipelines, target companies, or warm
  outreach.
---

# job-search

## Core Philosophy
Submitting 400 blind applications through LinkedIn "Easy Apply" is a statistical dead end that yields a $< 1\%$ interview rate and massive emotional burnout. A professional technical job search must be managed like an enterprise B2B sales pipeline: strict target account qualification, reverse-engineering company engineering stacks, activating warm 2nd-degree referrals, and demonstrating proof-of-work through custom technical artifacts before the first interview.

---

## 4-Step Technical Job Search Pipeline

### Step 1: Target Account Curation & Tiering (30 Accounts)
1. **Tiered Account Architecture**:
   - *Tier 1 (Top 5 - Dream Accounts)*: Uncompromising fit, high compensation, exceptional culture. Every application gets customized work samples and multi-threaded warm outreach.
   - *Tier 2 (15 Accounts - Strong Fits)*: High alignment with current skills, growing engineering organizations, Series B through Pre-IPO. Standard tailored resume + warm intro.
   - *Tier 3 (10 Accounts - Benchmark/Safety)*: Solid roles for pipeline velocity, interview practice, and establishing market compensation baselines.
2. **Qualification Filters**:
   - Tech stack match ($\ge 75\%$ overlap with your strengths).
   - Financial runway (profitable or raised within last 12 months).
   - Engineering leadership pedigree and low Glassdoor/Levels.fyi red flags.

### Step 2: Proof-of-Work Artifact Engineering
1. **The Pre-Interview Work Sample**:
   - For Tier 1 accounts, never submit just a PDF resume. Provide a tangible technical artifact:
     - Audit their public GitHub repositories and open a well-crafted PR or detailed issue.
     - Build a 1-page technical memo analyzing their API architecture or performance bottlenecks.
     - Record a 2-minute Loom demonstrating a solution to a problem their job description mentions.

### Step 3: Warm Referral & Multi-Threading Playbook
1. **Network Triangulation**:
   - Never apply cold on the careers page if a 2nd-degree connection exists.
   - Map connections: Search LinkedIn for engineering alumni from your previous companies or universities working at the target account.
2. **The 3-Touch Referral Outreach (Under 100 Words)**:
   - *Message to Peer Engineer*:
     - "Hey [Name], saw your team at [Company] is scaling the distributed data team. Loved your recent post on [Topic]. I've spent the last 3 years optimizing ClickHouse clusters at [Previous Org]. Would love to ask 2 quick questions about how your team handles schema migrations before I apply formally. No pressure at all!"
3. **Direct Hiring Manager Outreach**:
   - Identify the Director/VP of Engineering or Engineering Manager owning the headcount. Send a concise email highlighting your 3 core relevant wins and attaching your custom technical artifact.

### Step 4: Pipeline CRM Tracking & Conversion Diagnostics
1. **Pipeline Stage Metrics**:
   - *Prospecting*: Target identified, contact mapped.
   - *Outreach Active*: Message sent, awaiting referral response.
   - *Applied / Referred*: Formal application submitted with internal tag.
   - *Recruiter Screen*: 30-minute culture and background alignment.
   - *Technical Screen / Take-Home*: Coding or system design round.
   - *Onsite Loop*: Multi-round executive and peer panel.
   - *Offer Stage*: Negotiation and closing.
2. **Funnel Health Diagnostics**:
   - If Recruiter Screen conversion $< 40\%$: Resume bullets lack quantified impact or tech keywords.
   - If Technical Screen conversion $< 50\%$: Brush up on DSA or distributed systems fundamentals.
   - If Onsite-to-Offer conversion $< 33\%$: Behavioral answers (STAR method) or culture fit signals need calibration.

---

## Deliverable Format: Job Search Pipeline Spec (`JOB-SEARCH-PIPELINE.md`)

```markdown
# Technical Job Search Pipeline & CRM

## 1. Target Criteria & Constraints
- **Target Role**: [e.g. Senior Staff Backend Engineer]
- **Target Comp Band**: [$X - $Y base / total package]
- **Location / Mode**: [Remote / Hybrid / City]
- **Core Tech Stack**: [Go, Rust, PostgreSQL, Kubernetes]

## 2. Tier 1 Target Account Matrix
| Company | Team / Division | Engineering Manager / Recruiter | Warm Angle / Connection | Proof-of-Work Artifact | Status |
|---|---|---|---|---|---|
| [Target A] | Core Infra | [Name/Profile] | Ex-colleague at company | Audited open source CLI | Referral requested |
| [Target B] | Platform | [Name/Profile] | Met at GopherCon | 1-page migration memo | Recruiter screen scheduled |

## 3. Funnel Velocity Dashboard
- **Total Accounts Mapped**: [Count]
- **Active Referrals / Conversations**: [Count]
- **Technical Screens Active**: [Count]
- **Onsite Loops Scheduled**: [Count]
- **Offers In Hand**: [Count]
```

---

## Worked Example: Senior Infrastructure Engineer Transition

- **Strategy**: Bypassed cold job boards. Built a target list of 25 companies using Kubernetes in production.
- **Proof-of-Work**: Contributed a bug fix to the target company's open-source Terraform provider before reaching out.
- **Outreach**: Messaged the author of the pull request on LinkedIn with a 3-sentence note referencing the fix.
- **Outcome**: Secured direct VP of Engineering interview within 48 hours; received offer with 25% compensation increase in 3 weeks.

---

## Verification Checklist

- [ ] Target account list is capped at 30 high-conviction companies categorized into Tiers 1–3.
- [ ] Cold applications are prohibited for Tier 1 targets; warm intro or custom artifact is mandatory.
- [ ] Outreach messages are strictly $< 100$ words with zero generic flattery.
- [ ] Weekly funnel stage conversion rates are calculated to diagnose drop-offs.
- [ ] Salary expectations and minimum walk-away numbers are documented prior to initial screens.

---

## Anti-Patterns

- **Volume Spam**: Spraying 50 resumes a day to random job posts without customizing a single bullet point.
- **Passive Waiting**: Waiting for recruiters to discover an unoptimized LinkedIn profile.
- **Skipping the Hiring Manager**: Relying solely on automated portal submissions rather than finding the engineering leader owning the role.
