---
name: script-writer
description: Write high-converting ad scripts, hooks, headlines, webinar openers, VSLs, carousels, emails, and video copy — always three labeled variations across different hook types and frameworks so you're testing, not guessing. Use this skill any time the user needs copy for an ad, a reel, a short, a YouTube video, a webinar, a VSL, a carousel, an email, or any promotional content. Also triggers for "write me hooks," "I need a script," "help me with copy," "what should I say in my ad," or anything referencing marketing copy, ad creative, video scripts, or promotional writing. Platform-aware (Meta, TikTok, Reels, YouTube, email). Brand-voice-trained. Pairs with offer-builder (feed it an offer spec), ad-director (receives the script brief and returns the words), offer-auditor, and funnel-builder. Ethical by default — no manufactured urgency, no false scarcity, no manipulation patterns.
---

# Script Writer

Write three labeled script variations every time — different hook type + framework combinations, so the user is testing, not guessing. Every output is platform-aware, voice-checked, and ready to use.

## Part of a five-skill system

```
offer-auditor → offer-builder → script-writer → ad-director → funnel-builder
   (audit)         (build)        (write copy)    (direct+shoot)  (map journey)
```

Script Writer receives its brief from the user directly OR from Ad Director (Phase 5). It returns three labeled scripts. Ad Director then directs against the chosen variation (wardrobe, blocking, video prompts). Each skill works standalone.

## The non-negotiable rules

These apply to every format, every time, no exceptions:

1. **Always three variations.** Three different hook type + framework combinations, labeled (e.g., "Variation A: Pain hook + PAS," "Variation B: Contrarian hook + BAB," "Variation C: Desire hook + AIDA"). The user picks the winner by testing, not by guessing.
2. **Always labeled.** Every variation carries its hook type and framework name so the user knows exactly what they tested when one wins.
3. **Always pass the voice checklist** (from `voice.md`) before delivering. No exceptions. If a check fails, rewrite before showing the user. The checklist:
   - No "Hey/So/Today/In this video" openers — start mid-thought
   - "You" appears 2x more than "I/we" (unless origin story)
   - At least one specific number, name, or time reference
   - No banned hype words (leverage, unlock, synergy, game-changing, transformative, revolutionary, next-level, etc.)
   - No banned hedges (might, perhaps, could possibly)
   - No adverbs that can be deleted without losing meaning
   - Active voice, present tense
   - No sentence longer than 25 words
   - Reads naturally aloud
   - No apology for the pitch
4. **Always ethical.** No fabricated stats, no fake testimonials, no manufactured urgency, no false scarcity, no manipulation patterns. See `anti_patterns.md` for the full banned-tactics list.
5. **Always platform-aware.** A Meta ad ≠ a YouTube script ≠ an email. Use the right format file for the platform. See `formats.md` for specs.

## How this skill activates (the flow)

### Step 1 — Determine the format

Based on what the user asks for, load the right format file:

| User wants… | Load this file |
|---|---|
| Short video ad (TikTok, Reels, Shorts, Meta video, paid short) | `short_video_ad.md` |
| YouTube long-form (5-15 min) | `youtube_longform.md` |
| Webinar or workshop (45-90 min) | `webinar.md` |
| Video sales letter | `vsl.md` |
| Carousel / static slides | `carousel.md` |
| Email (subject + body) | `email.md` |
| "Just hooks" / headlines only | `hooks.md` (use hook library directly) |
| "Diagnose my existing script" | `diagnose.md` |
| "Adapt / iterate a previous script" | `adapt.md` |

If the request doesn't clearly map, ask one question: "What format do you need — short video, long-form, webinar, email, or something else?" Don't guess the format.

### Step 2 — Load brand voice

Check if the user has provided a brand voice document (filled `brand_voice_template.md`). If yes, load it. Brand voice supersedes the default voice where they conflict (e.g., a luxury brand may use formal register). If no brand voice is provided, default to: direct, specific, conversational, lightly opinionated, no hype.

### Step 3 — Gather the brief

For a new script, collect (ask only what's missing — pull from context first):

- **What are we writing for?** (the offer, product, topic, or idea)
- **Who is the audience?** (one specific person, not a demographic)
- **What platform?** (determines format, length, aspect, pacing)
- **What's the ONE action?** (the CTA — click, comment, register, buy, follow)
- **What awareness stage?** (unaware / problem / solution / product / most aware — drives the hook type)

If an **Offer Builder spec** exists, use it — it has the promise, mechanism, price, proof, and audience already locked. If an **Ad Director brief** arrives (Phase 5 handoff), it carries all of the above plus a beat structure with timecodes — use it directly.

### Step 4 — Write three variations

Load the format file from Step 1. Load the hook library (`hooks.md`) and frameworks (`formats.md`). Select three hook type + framework combinations that fit the awareness stage and platform.

Good combinations for common scenarios:

- **Cold / unaware audience:** Pain + PAS, Contrarian + BAB, Curiosity + 4Ps
- **Problem-aware:** Problem-agitate + AIDA, Specific-result + PAS, Story + BAB
- **Warm / product-aware:** Desire + AIDA, Social-proof + PAS, Direct-offer + 4Ps

Write all three. Label each clearly:
```
VARIATION A — Pain hook + PAS framework
[the script]

VARIATION B — Contrarian hook + BAB framework
[the script]

VARIATION C — Curiosity hook + AIDA framework
[the script]
```

### Step 5 — Run the voice checklist

Before showing the user, run every variation through the voice checklist (Step 3 of the non-negotiable rules above, drawn from `voice.md`). Fix any failures. Don't deliver a script that fails the checklist.

### Step 6 — Deliver with testing notes

Present all three variations with:
- Labels (hook type + framework)
- A one-line note on each: what it's testing and why it might win
- A recommendation for which to test first (and why)
- The voice checklist confirmation: "All three pass the voice checklist."

If the user is working with Ad Director, the output is consumed by Ad Director Phase 5 — it'll pick one (or all three) and direct against them.

## File map — what each file does and when to load it

### Format files (one per script type — load the one that matches the task)
- **`short_video_ad.md`** — Template + structure for short-form video (15-60s). TikTok, Reels, Shorts, Meta video ads, paid shorts. The most common format for Ad Director handoffs.
- **`youtube_longform.md`** — Template + structure for YouTube 5-15 min. 7-part structure, MrBeast principle (first sentence matches title, first shot matches thumbnail), pattern interrupts every 60-90s.
- **`webinar.md`** — Template + structure for 45-90 min webinars/workshops. Perfect Webinar 3-section flow (origin story → three secrets → stack & close + Q&A). Highest-converting format for $200-$5000 offers.
- **`vsl.md`** — Video sales letter template. Long-form persuasion for high-ticket offers.
- **`carousel.md`** — Carousel / static slide format. Each slide is a micro-statement.
- **`email.md`** — Email: subject line, preview text, body. Personal voice, like writing to one friend.

### Reference files (shared knowledge — load as needed alongside the format file)
- **`hooks.md`** — 12 hook types with examples, when to use each, and which awareness stages they match. The hook library. Load this when writing any script.
- **`formats.md`** — Frameworks: PAS, AIDA, BAB, 4Ps, and more, with fill-in templates. The structural spine. Load this when writing any script.
- **`voice.md`** — The 10 voice patterns, the banned-words lists (hype words, hedges, fillers, cliché openers), credibility signals (specificity, vulnerability, reframe, open loops), and the voice-across-formats tuning table. Load this for the pre-delivery voice checklist. **Mandatory for every delivery.**
- **`psychology.md`** — Persuasion psychology: why hooks work, cognitive triggers, trial closes, micro-yeses. Background understanding. Load when the user wants to understand *why* something converts, not just get the script.
- **`anti_patterns.md`** — Manipulation tactics and dark patterns to avoid. The ethics layer. Reference when building scripts for sensitive offers or when the user's ask is heading toward a gray area.

### Workflow files
- **`new_script.md`** — The "write a new script from scratch" workflow. The default path. Walks intake → format selection → brief → 3 variations → voice check → deliver. (This SKILL.md covers the same flow; `new_script.md` has deeper detail.)
- **`adapt.md`** — Adapting / iterating a script that already exists. Use when the user says "take this script and make it better" or "give me a new angle on this."
- **`diagnose.md`** — Diagnosing why an existing script isn't converting. Use when the user says "this ad isn't working, what's wrong?"

### Template files
- **`brand_voice_template.md`** — Fill in once. Captures the user's actual voice (vocabulary they use, vocabulary they'd never use, sentence rhythm, level of formality, humor/no humor, signature phrases). Applies to every script from then on.
- **`good_examples.md`** — Worked examples of completed scripts across formats. Reference for tone and structure.

## Receiving a brief from Ad Director

When called by Ad Director (Phase 5), the brief arrives pre-filled:

```
FORMAT:            [usually short video ad]
TOPIC / OFFER:     [what's being promoted]
PLATFORM:          [TikTok / Reels / Shorts / etc.]
TARGET LENGTH:     [e.g., 25-30 seconds]
AWARENESS STAGE:   [drives the hook selection]
HOOK ANGLE(S):     [the angle(s) to explore]
BEAT STRUCTURE:    [timecoded beats from Ad Director's format playbook]
THE ONE ACTION:    [CTA]
BRAND VOICE:       [pointer to brand_voice_template or inline notes]
MUST INCLUDE:      [required phrases, dates, disclaimers]
MUST AVOID:        [brand-specific bans beyond the standard list]
```

Use it directly — don't re-ask what's already provided. Write three variations, pass the voice checklist, return. Ad Director handles direction from there.

## When the content is mislabeled (maintenance note)

If a format file's H1 heading doesn't match its filename (e.g., `short_video_ad.md` opens with "Voice & Language Patterns" instead of a short-video template), the file contents were saved into the wrong filename. Check the H1 of each file, find where the matching content actually lives, and swap. The filenames in the router table above are the *intended* names — match content to names, not names to content.

## Common pitfalls

1. **Writing one variation and calling it done.** The whole point is three. Force the discipline.
2. **Forgetting the label.** An unlabeled variation is untestable — the user won't know what won when one wins.
3. **Skipping the voice checklist.** A script that opens with "Hey guys!" or uses "leverage" or "game-changing" fails before the viewer reads it. Run the checklist.
4. **Same hook three times in different words.** Three variations of a pain hook isn't testing — it's rewording. Vary the *hook type* (pain vs. contrarian vs. desire), not just the phrasing.
5. **Ignoring platform.** A YouTube script pasted into a TikTok ad is wrong in length, pacing, aspect, and opening physics. Use the right format file.
6. **Fabricating proof.** Never invent a stat, a testimonial, or a result. If a claim isn't real, cut it or soften it.