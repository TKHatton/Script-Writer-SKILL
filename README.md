# script-writer SKILL

> Write high-converting scripts for ads, hooks, headlines, video sales letters, webinars, workshops, carousels, and YouTube videos — with built-in testing discipline and platform-specific formatting.

---

## What this skill does

Most AI tools write one script and call it done. This skill writes three — always — across three different hook types and frameworks, labeled so you know exactly what you tested when one wins.

Every output is grounded in research on what actually converts: pain hooks, desire hooks, contrarian hooks, pattern interrupts, PAS, AIDA, and more. The skill knows the difference between a Meta ad, a YouTube pre-roll, a webinar opener, and an email subject line — and formats accordingly.

Hand it your offer and audience. It handles the rest.

---

## What's inside

```
script-writer/
├── SKILL.md                         ← Load this to activate the skill
├── README.md                        ← This file
├── references/
│   ├── anti_patterns.md             ← What to avoid in script writing
│   ├── formats.md                   ← Format specifications and guidelines
│   ├── good_examples.md             ← Examples of effective scripts
│   ├── hooks.md                     ← Hook types with examples and when to use each
│   ├── psychology.md                ← Psychological principles for persuasive copy
│   └── voice.md                     ← Voice and tone guidance
├── workflows/
│   ├── adapt.md                     ← Workflow for adapting existing scripts
│   ├── diagnose.md                  ← Workflow for diagnosing script issues
│   └── new_script.md                ← Workflow for creating new scripts
├── formats/
│   ├── carousel.md                  ← Carousel post format specs
│   ├── email.md                     ← Email script format specs
│   ├── short_video_ad.md            ← Short-form video ad specs
│   ├── vsl.md                       ← Video sales letter format specs
│   ├── webinar.md                   ← Webinar script format specs
│   └── youtube_longform.md          ← Long-form YouTube video specs
└── templates/
    └── brand_voice_template.md      ← Fill this in once — applies to every script
```

---

## How to use it

**In Claude (any conversation):**
Paste the raw URL to `SKILL.md` at the start of your message, or add it to your project instructions. Then ask for what you need:

> "Write me three Meta ad scripts for my AI workshop targeting small business owners who are overwhelmed by tech."

**In other AI tools (Gemini, Codex, etc.):**
Fetch the raw content of `SKILL.md` and paste it into your system prompt or context window. Works in any tool that accepts a system prompt.

**Fill in the templates first.** `brand_voice_template.md` and `audience_profile_template.md` are what make every output sound like *you* instead of generic AI copy. Takes 20-30 minutes once. Applies forever.

---

## What makes this different

- **Always three variations** — forces testing discipline, not guesswork
- **Every output is labeled** — "Pain hook + PAS framework" so you know what you ran when one wins
- **Platform-aware** — knows Meta ≠ YouTube ≠ email, formats accordingly
- **Pairs with offer-builder** — feed it an offer spec and it knows exactly what to write
- **Ethical by default** — no manufactured urgency, no false scarcity, no manipulation patterns

---

## Part of a four-skill system

```
offer-auditor  →  offer-builder  →  script-writer  →  funnel-builder
(audit)            (build)            (write copy)       (map the journey)
```

Each skill works standalone. Together they cover the full marketing workflow from offer design to customer journey.

---

## Repo structure for GitHub

Each folder maps directly to a folder in the repo. Keep `SKILL.md` at the root. Reference files load only when needed — the skill pulls what it needs per task, keeping responses fast and focused.

---

*Built for creators, coaches, consultants, and service providers who want to market without feeling like a marketer.*
