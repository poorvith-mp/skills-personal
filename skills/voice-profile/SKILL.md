---
name: voice-profile
group: Identity
description: >-
  Capture how you actually write: rhythm, vocabulary, structural habits, phrases you never use,
  and real samples. Use when analyzing writing voice, tone rules, rhythm, or anti-AI style.
---

# voice-profile

## Core Philosophy
Most AI-generated writing reads like generic corporate sludge—saturated with symmetrical sentence structures, timid hedging, and exhausted transitional tropes ("delve", "testament to", "unlocking the power"). A genuine human voice profile is not an abstract personality test; it is an exact, measurable linguistic fingerprint. Capturing your authentic voice requires mapping sentence cadence variance, signature rhetorical structures, explicit banned phrase registries, and opinionated stances.

---

## 4-Step Voice Profile Engineering Protocol

### Step 1: Cadence & Rhythm Metrics (Sentence Variance)
1. **Sentence Length Distribution**:
   - Real human writing features high variance in sentence length: short punchy fragments juxtaposed against complex, rhythmic clauses.
   - Target Distribution:
     - Short ($\le 8$ words): 30% (Impact, conclusions, transitions).
     - Medium (9–20 words): 50% (Core explanations, evidence).
     - Long (21–35 words): 20% (Nuance, detailed lists, conditional logic).
2. **Avoid Symmetrical Monotony**:
   - If 3 consecutive sentences are between 14 and 18 words, the prose instantly feels generated. Break the rhythm with a 3-word sentence.

### Step 2: Lexicon Calibration & The Banned Trope Registry
1. **The Mandatory AI Cliché Kill-List**:
   - *Banned Verbs*: Delve, Unlock, Unleash, Elevate, Harness, Revolutionize, Supercharge, Foster, Demystify.
   - *Banned Nouns*: Tapestry, Beacon, Testament, Game-changer, Paradigm, Synergy, Journey.
   - *Banned Adjectives*: Crucial, Pivotal, Vibrant, Robust, Paramount, Seamless, Holistic.
   - *Banned Transitions*: Furthermore, Moreover, In conclusion, It's important to remember, At the end of the day.
2. **Signature Lexicon Injection**:
   - Document your organic technical vocabulary, preferred metaphors, and colloquial developer phrasing (e.g. "under the hood", "footgun", "table stakes", "sharp edges").

### Step 3: Stance, Hedging & Rhetorical Habits
1. **Hedging Suppression**:
   - Eliminate weak qualifiers: "It could be argued that...", "Perhaps...", "In some ways...", "Generally speaking...".
   - Make declarative, falsifiable technical assertions. If nuance is required, state the specific trade-off explicitly:
     - *Hedged*: "Serverless can sometimes be expensive for certain workloads."
     - *Direct*: "Serverless compute bills explode when sustained baseline traffic exceeds 1,000 requests per second."
2. **Rhetorical Devices**:
   - Document preferred structural patterns: rhetorical questions, parenthetical asides, em-dashes for dramatic pauses, or numbered concrete takeaways.

### Step 4: Baseline Reference Corpus & Validation Pass
1. **Corpus Extraction**:
   - Gather 3–5 unedited samples of your best writing (published blog posts, technical post-mortems, authentic emails).
2. **The "Voice Turing Test" Validation**:
   - Read generated copy aloud. If a sentence makes you feel like an HR corporate spokesperson, delete and rewrite it.

---

## Deliverable Format: Voice Profile Specification (`VOICE-PROFILE.md`)

```markdown
# Personal Writing Voice Profile & Style Guide

## 1. Tone & Core Posture
- **Primary Stance**: Direct, pragmatic, technically rigorous, anti-hype.
- **Perspective**: Senior builder who has seen architectures fail and values simplicity over trends.
- **Humor / Irony**: Dry, understated, occasionally cynical about industry buzzwords.

## 2. Rhythm & Sentence Cadence Rules
- **Sentence Length**: High variance. Mix 4-word punchlines with 25-word explanatory clauses.
- **Paragraph Length**: Maximum 3 sentences per paragraph for digital reading.
- **Punctuation Preferences**: Frequent em-dashes (—) for parenthetical thoughts; semicolons prohibited.

## 3. Lexicon Guidelines
- **Forbidden Words (Instant Rewrite)**:
  - *delve*, *unlock*, *testament*, *tapestry*, *pivotal*, *crucial*, *harness*, *furthermore*
- **Preferred Idioms & Terms**:
  - *footgun*, *table stakes*, *under the hood*, *operational overhead*, *sharp edges*

## 4. Before & After Benchmark
- **Generic AI Draft**:
  *"In today's fast-paced digital landscape, it is crucial to harness the power of modern database architectures to unlock unprecedented scalability."*
- **Personal Voice Transformation**:
  *"If your database locks tables during schema migrations, your modern architecture is a liability. Here is how to fix Postgres DDL bottlenecks without dropping production queries."*
```

---

## Worked Example: Technical Founder Voice Profile

- **Stance**: Speaks as an experienced systems engineer writing for other engineers.
- **Rule**: Never use marketing superlatives ("best-in-class", "revolutionary"). Always replace adjectives with specific benchmark numbers (e.g. "runs in 4ms with 12MB RAM").
- **Impact**: Blog posts read as authoritative engineering field reports rather than SEO link-bait, doubling newsletter subscriber conversion.

---

## Verification Checklist

- [ ] All words on the AI Cliché Kill-List are strictly prohibited.
- [ ] Sentence length varies visibly between short punchy statements and descriptive clauses.
- [ ] Hedging phrases ("arguably", "somewhat") are removed in favor of direct assertions.
- [ ] Paragraphs are capped at 3–4 sentences for online readability.
- [ ] Style includes real before/after reference samples demonstrating the voice.

---

## Anti-Patterns

- **The Corporate Press Release**: Writing in a passive, risk-averse tone designed to offend nobody while saying nothing.
- **The Thesaurus Trap**: Using elevated vocabulary ("plethora", "myriad", "elucidate") where simple Anglo-Saxon words work better.
- **Performative Hype**: Using exclamation marks and emojis to artificially simulate excitement.
