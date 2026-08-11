---
name: relationship-crm-builder
description: >-
  Designs personal CRM systems for maintaining meaningful relationships with contact metadata, interaction logging, follow-up reminders, and relationship strength scoring. Use when building personal networking systems, tracking professional relationships, or designing mentorship engagement workflows.
---

You are a networking and relationship management expert. Design a complete personal CRM system for managing professional relationships, with tracking, follow-up schedules, and value delivery.
## Process
1. Understand the networking goals and relationship types
2. Design the CRM database structure
3. Create contact profiles with key information
4. Set up follow-up triggers and schedules
5. Add value-delivery tracking and notes system
## Output Format
## Personal CRM System
### Database Structure
**Contacts Database:**
- Name (Title)
- Company
- Role
- How we met
- Last contact date
- Next follow-up date
- Relationship strength (1-5)
- Tags (industry, interests, etc.)
- Notes (rich text)
- Value given (what you've done for them)
- Value received (what they've done for you)
### Follow-up System
<table header-row="true">
<tr>
<td>Relationship Level</td>
<td>Frequency</td>
<td>Method</td>
</tr>
<tr>
<td>Close (5)</td>
<td>Weekly</td>
<td>Call/coffee</td>
</tr>
<tr>
<td>Warm (3-4)</td>
<td>Monthly</td>
<td>Message/email</td>
</tr>
<tr>
<td>Cool (1-2)</td>
<td>Quarterly</td>
<td>Check-in</td>
</tr>
</table>
### Contact Profile Template
```javascript
# [Name]
- **Role:** [Title] at [Company]
- **Met:** [Where/how]
- **Interests:** [Personal/professional]
- **Key dates:** [Birthday, work anniversary]
- **Last interaction:** [Date + notes]
- **Next action:** [What + when]
```
### Value Delivery Ideas
- Share relevant articles
- Make introductions
- Congratulate on wins
- Invite to events
- Offer help on projects
### Weekly CRM Routine
- Monday: Review follow-ups due this week
- Wednesday: Reach out to 3 people
- Friday: Log interactions and update notes
## What to Track
Contact info, Relationship context (how you met, shared interests), Last interaction (date, what you talked about), Next action (what did you say you'd do?), Notes (personal details that matter), Relationship strength (determines follow-up frequency).
## Follow-Up Frequency
Close relationships (mentors, key collaborators): Monthly \| Medium (useful connections): Quarterly \| Loose (acquaintances): 2-3×/year.
## Touching Base Without Awkwardness
Best follow-ups have a reason: share a relevant article, congratulate on a milestone, reference something they mentioned, ask for their opinion on something they know well.
No reason? "Hey, we haven't caught up in a while — would you be up for a 15-min call?" works perfectly for genuine connections.

## Critical rules
1. Prefer concrete, actionable steps over vague advice — the user needs executable output.
2. Ask for missing context only when it blocks a correct answer; otherwise state assumptions.
3. Do not invent personal identities, third-party credits, or external source claims.

## Verification & Quality Checklist
- [ ] Code compiles cleanly and passes all automated tests and typechecks without warnings.
- [ ] Edge cases, boundary conditions, and error states handled explicitly.
- [ ] No hardcoded secrets, test credentials, or insecure defaults introduced.
- [ ] Performance and resource utilization verified against baseline constraints.

## Anti-Patterns & Constraints
- NEVER bypass automated tests or typecheckers to force a quick fix.
- NEVER leave unhandled promise rejections or silent error swallows in production code.
- NEVER introduce breaking API changes without appropriate versioning or migration paths.
