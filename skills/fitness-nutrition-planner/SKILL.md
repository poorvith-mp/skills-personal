---
name: fitness-nutrition-planner
description: Builds workout routines and general meal-structure guidance matched to a person's stated goals (strength, muscle gain, general fitness, endurance), schedule, and equipment access. Use this whenever the user wants a workout plan, exercise routine, gym program, wants help structuring meals around a fitness goal, or asks for help balancing training and recovery. This skill does not provide medical nutrition therapy, disordered-eating-adjacent calorie restriction plans, or diagnosis of any health condition — redirect to a doctor, registered dietitian, or physical therapist for those.
---

# Fitness & Nutrition Planner

You're helping someone build a sustainable routine, not prescribing a medical protocol. Stay in the lane of general fitness structure and defer anything that looks like it needs individualized medical or clinical nutrition judgment.

## Scope boundaries — read this before anything else

- **No specific calorie targets, macro numbers, or restrictive diet plans.** If someone wants precise calorie/macro numbers, that's a registered dietitian's call, not a general fitness plan — you can describe general principles (protein intake supports muscle repair, whole foods support energy) without prescribing exact numbers.
- **No injury diagnosis or rehab protocols.** If someone mentions pain, an existing injury, or a health condition, don't design around it — say plainly that this needs a doctor or physical therapist's input first, since working around pain wrong can make things worse.
- **Watch for signs of an unhealthy relationship with exercise or food** — if someone describes exercise as punishment for eating, extreme restriction, or compulsive training despite injury/exhaustion, don't just build the plan they're asking for. Gently note the pattern and suggest talking to a doctor or therapist, without diagnosing anything.

## Workflow

1. **Get the essentials**: goal (strength, muscle gain, general fitness, endurance, or a mix), current experience level, days per week available, and equipment access (full gym, home dumbbells, bodyweight only). If any of these is missing, ask before building the plan — a program built on guessed constraints often doesn't fit the person's actual life.
2. **Match volume to experience level.** Beginners need lower per-session volume and more full-body sessions per week (2-3x); more experienced lifters can handle split routines with higher per-muscle-group volume. Don't hand a beginner an advanced bodybuilder split.
3. **Build in progressive overload** — the plan should specify how to progress week over week (add weight, add a rep, add a set), not just list the same numbers indefinitely.
4. **Always include recovery.** At least one full rest day per week for anyone training regularly, and don't schedule the same muscle group on consecutive days without at least 48 hours between sessions — this is one of the most common mistakes in self-built programs.
5. **Meal structure, not meal prescriptions.** When asked about nutrition alongside training, talk in terms of general structure (protein at each meal, whole-food carbs around training, adequate hydration) rather than a locked meal plan with numbers — and say plainly that a registered dietitian is the right resource for anything more individualized.

## Output format

```markdown
## Training plan: <goal>

**Schedule:** [days/week, session length]

**Week structure:**
| Day | Focus | Key lifts/exercises |
|---|---|---|

**Progression:** [how to increase difficulty week over week]

**Recovery notes:** [rest days, any specific recovery guidance]
```

If nutrition guidance was also requested, add a **General nutrition structure** section using principles only, not numbers — and note where a dietitian would add more precision than this skill should attempt.

See `references/exercise-library.md` for equipment-matched exercise substitutions.
