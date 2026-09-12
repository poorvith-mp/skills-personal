---
name: resume
last_reviewed: 2026-09-06
group: Career
description: >-
  Tailor a resume to a named job description with ATS-safe formatting and quantified achievement
  bullets. Use when crafting resumes, CVs, impact bullets, or ATS optimization.
---

# resume

## Core Philosophy
A technical resume is not an autobiographical chronicle of every duty you have ever performed. It is a 1-page high-conversion marketing document engineered to satisfy Applicant Tracking System (ATS) algorithmic parsing and capture an engineering hiring manager’s attention within 6 seconds. Bullet points must never state passive job responsibilities; they must present undeniable evidence of business and engineering impact using Google’s X-Y-Z formula.

---

## 4-Step Technical Resume Engineering Framework

### Step 1: ATS Formatting & Architectural Hygiene
1. **Single-Column Structural Mandate**:
   - Use a strictly single-column layout. Multi-column tables, text boxes, and sidebars scramble ATS parsers.
   - Typography: Standard clean fonts (Inter, Roboto, Calibri, Arial) in 10–11pt body and 14–16pt bold headings.
   - File Export: Clean PDF with selectable text (verify by copying and pasting text into raw Notepad).
   - Page Constraint: Strictly 1 page for professionals with $< 10$ years experience; maximum 2 pages for Principal/Director/Staff with 10+ years.
2. **Standard Section Headers**:
   - Use standard header naming: `Work Experience`, `Technical Skills`, `Education`, `Selected Open Source Projects`. Avoid clever labels like "Where I've Been" or "Proficiencies".

### Step 2: The Google X-Y-Z Impact Bullet Formula
1. **The Formula**:
   $$text{"Accomplished [X], as measured by [Y], by doing [Z]"}$$
2. **Before vs After Transformation**:
   - *Bad (Passive Responsibility)*: "Responsible for writing Go microservices and maintaining database queries."
   - *Good (Technical Output)*: "Built a Go microservice that handled 15,000 RPS with PostgreSQL."
   - *Exceptional (Google X-Y-Z Impact)*: "Reduced API p99 latency from 420ms to 45ms (X), slashing AWS compute costs by $65k/year (Y), by rewriting the ingestion pipeline in Go and implementing a Redis caching layer (Z)."
3. **Power Action Verbs**:
   - Architected, Spearheaded, Engineered, Overhauled, Slashed, Streamlined, Automated, Scaled, Eliminated. Banish passive verbs like "Helped", "Worked on", or "Assisted with".

### Step 3: Targeted Keyword Optimization & Tailoring
1. **Job Description Keyword Extraction**:
   - Scan target job description for explicit hard skills: languages (Go, Rust, TypeScript), databases (Postgres, ClickHouse), infra (Kubernetes, AWS, Terraform), and methodologies (SOC 2, CI/CD).
   - Ensure these exact tokens appear in the `Technical Skills` section and within context in at least 2 experience bullets.
2. **Skills Section Categorization**:
   - Group logically: Languages, Frameworks, Infrastructure & Cloud, Databases & Storage, Developer Tooling. Do not include subjective soft skills ("hard worker", "team player").

### Step 4: The 6-Second Hiring Manager Scan Test
1. **Visual Hierarchy Alignment**:
   - Most prominent visual weight: Name, Title, and Top 3 achievement bullets of the most recent role.
   - Quantify everything: Every single bullet point must contain at least one number, percentage, dollar figure, or time savings metric.

---

## Deliverable Format: ATS-Optimized Resume Markdown (`RESUME.md`)

```markdown
# [First Name] [Last Name]
[City, State / Remote] • [email@domain.com] • [Phone] • [linkedin.com/in/handle] • [github.com/handle] • [portfolio.com]

## Professional Summary
Senior Systems Engineer with 7+ years of experience architecting distributed cloud infrastructure and high-throughput microservices. Proven track record of reducing infrastructure operating costs by 40%+ while scaling systems from 50k to 5M daily active users.

## Technical Skills
- **Languages**: Go, Rust, Python, TypeScript, SQL, Bash
- **Infrastructure & Cloud**: AWS (EKS, RDS, S3), Docker, Kubernetes, Terraform, GitHub Actions
- **Databases & Storage**: PostgreSQL, Redis, ClickHouse, DynamoDB, Kafka
- **Monitoring & Security**: Prometheus, Grafana, OpenTelemetry, Datadog, SOC 2 compliance

## Professional Experience

### [Company Name] — [City, State / Remote]
**Senior Software Engineer** | *[Month, Year] – Present*
- Reduced p99 API response latency from 380ms to 32ms across 20M daily requests by re-architecting legacy Node.js monolith into concurrent Go microservices.
- Slashed monthly AWS infrastructure expenses by $48,000 (34%) by implementing Kubernetes cluster auto-scaling and spot-instance node pools with zero downtime.
- Engineered automated CI/CD deployment pipeline using GitHub Actions and ArgoCD, reducing mean time to production from 3 days to 14 minutes.
- Mentored 6 mid-level engineers through weekly architecture reviews, leading to zero critical production incidents over 4 consecutive quarters.

### [Previous Company] — [City, State / Remote]
**Software Engineer** | *[Month, Year] – [Month, Year]*
- Architected real-time telemetry analytics engine in Rust and ClickHouse, ingesting 80,000 events/sec with sub-second dashboard query latencies.
- Automated database schema migrations and zero-downtime rollouts across 12 production PostgreSQL clusters, eliminating an average of 4 hours of monthly maintenance downtime.

## Education & Certifications
- **B.S. in Computer Science** — [University Name], [Graduation Year]
- **AWS Certified Solutions Architect – Professional** (2025)
```

---

## Worked Example: Infrastructure Engineer Bullet Transformation

- **Original Draft**: "Configured monitoring dashboards using Prometheus and Grafana for our cloud servers."
- **Rewritten Bullet**: "Engineered unified observability framework across 140 Kubernetes microservices using Prometheus, Grafana, and OpenTelemetry, reducing Mean Time to Detection (MTTD) of production outages from 45 minutes to 3 minutes."
- **Result**: Candidate went from 0 recruiter callbacks across 30 applications to 5 onsite interviews in 2 weeks.

---

## Verification Checklist

- [ ] Layout is strictly single-column with standard header titles and selectable text.
- [ ] Every bullet point follows the Google X-Y-Z formula (Action -> Metric -> Technical Method).
- [ ] Document is strictly 1 page (or 2 pages for 10+ years experience).
- [ ] Technical Skills section includes hard technologies matching target job description.
- [ ] Resume contains zero subjective fluff ("detail-oriented", "hard worker").

---

## Anti-Patterns

- **Two-Column Graphic Templates**: Using Canva templates with progress bars for skill levels (e.g. "Python: 80%"). ATS systems reject these.
- **Responsibility Dumping**: Writing "Tasks included managing Jira tickets and writing unit tests."
- **Zero Metrics**: Submitting a resume where not a single number, percentage, or currency figure appears.
