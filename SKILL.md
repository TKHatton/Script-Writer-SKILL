# Template: YouTube Long-Form Script (5-15 minutes)

YouTube is different physics from feed ads. The viewer chose to click — they're not scrolling. The job of the hook is *retention*, not capture.

## Format specs

- **Aspect:** 16:9 horizontal
- **Length:** 8-12 min hits the algorithm sweet spot for most niches
- **Hook window:** First 10 seconds (MrBeast principle: match thumbnail + title in first sentence + first shot)
- **Pattern interrupts:** Every 60-90 seconds (visual change, audio change, location change, or "but here's where it gets interesting")

## The 7-part structure

```
0:00-0:10  HOOK + PROMISE (deliver on thumbnail/title)
0:10-0:30  WHY THIS MATTERS (raise stakes)
0:30-1:00  CREDIBILITY (briefly — why you)
1:00-3:00  CONTENT BLOCK 1 (with pattern interrupt at end)
3:00-5:00  CONTENT BLOCK 2 (with tease for what's coming)
5:00-8:00  CONTENT BLOCK 3 (the payoff / biggest insight)
8:00-end   RECAP + CTA + NEXT VIDEO
```

## The MrBeast principle

Two rules that drive YouTube retention:

1. **First sentence matches the title.** If your title says "I built an AI agent in 90 minutes," your first sentence should reference that exact thing immediately. Don't make the viewer wait.

2. **First shot matches the thumbnail.** Same. If the thumbnail shows a specific dashboard, the first shot should be that dashboard. Mismatch causes immediate drop-off.

Then: **exceed expectations within the first 20 seconds.** "I built an AI agent in 90 minutes. Including the part where I broke it twice and almost gave up." The "broke it twice" is the exceed.

## Fill-in template

```
SCRIPT: [name]
VIDEO TITLE: "[the title — also informs the thumbnail]"
THUMBNAIL CONCEPT: [what the thumbnail shows]
HOOK TYPE: [Pain | Curiosity | Specific-Result | Contrarian | Story]
AUDIENCE: [one specific person]
OFFER (if any): [what you're driving to — workshop, product, etc.]

---

[0:00-0:10] HOOK + PROMISE
First sentence: "[matches the title, specific]"
First shot: [matches the thumbnail]
Promise: "[by the end of this video, you'll know X]"
Pattern interrupt baked in: [the surprise that exceeds the title's promise]

[0:10-0:30] WHY THIS MATTERS
Verbal: "[why this matters now — the stakes if they don't learn this]"
Visual: [supporting B-roll or screen visual]
Hook reinforcement: [tease what's coming — "in 7 minutes I'll show you the exact step that flipped this"]

[0:30-1:00] CREDIBILITY
Verbal: "[2-3 sentences on why you can teach this — specific result, specific experience]"
Visual: [proof shot — screenshot, your work, your environment]
Note: keep this short. Long credibility intros kill retention.

[1:00-3:00] CONTENT BLOCK 1
Topic: [first main idea]
Verbal: "[the teaching]"
Demonstrate: [show, don't just tell]
Pattern interrupt at end (around 2:50): [location change, B-roll cut, or "but wait, that's not the interesting part — what I'm about to show you is" tease]

[3:00-5:00] CONTENT BLOCK 2
Topic: [second main idea, builds on block 1]
Verbal: "[the teaching]"
Demonstrate: [more screen recording, more proof]
Pattern interrupt around 4:50: [tease block 3]

[5:00-8:00] CONTENT BLOCK 3
Topic: [the biggest insight — saved for last]
Verbal: "[this is the payoff]"
Demonstrate: [most detailed walk-through]
This is the section the viewer paid attention for. Make it worth their time.

[8:00-end] RECAP + CTA + NEXT VIDEO
Recap: "[1-2 sentence summary of the 3 blocks]"
CTA: "[the action — subscribe, opt-in, buy, comment]"
Next video tease: "[specific reference to the next video the viewer should watch — not generic 'subscribe!']"
```

## Filled example (your context: AI workflow tutorial)

```
SCRIPT: How I Built My Client Reporting Automation
VIDEO TITLE: "I Built a $0 Client Reporting System in 90 Minutes (Full Tutorial)"
THUMBNAIL CONCEPT: Split image — left side: chaotic spreadsheets and email drafts. Right side: clean automated dashboard with "90 MIN" overlay.
HOOK TYPE: Specific-Result
AUDIENCE: Solo consultants spending Sundays building client reports

---

[0:00-0:10] HOOK + PROMISE
First sentence: "I just built a client reporting system in 90 minutes. It runs every Friday at 5pm, drafts the reports, and emails them to me Sunday morning. Total cost: $0."
First shot: The actual dashboard from the thumbnail — exactly the same image
Promise: "In the next 10 minutes I'll show you the whole build, including the part where I broke it twice."
Pattern interrupt baked in: "broke it twice" — viewer expects clean tutorial, gets honest one

[0:10-0:30] WHY THIS MATTERS
Verbal: "If you're a consultant or freelancer, client reports probably eat 4-8 hours of your week. Multiplied by 50 weeks, that's 200-400 hours a year — a full month of work, every year, doing the same thing manually. This video shows the fix."
Visual: Quick montage of someone manually building reports — drag, click, drag, click
Hook reinforcement: "Stick around because the trick that saved me 6 hours per client is in the last section."

[0:30-1:00] CREDIBILITY
Verbal: "Quick background — I've run a 4-person consulting practice for 6 years. Built systems for 31 clients. This is the one I use myself every Friday."
Visual: Quick shots of working environment, monitor with the system running
Note: 30 seconds max. Don't overstay.

[1:00-3:00] CONTENT BLOCK 1: The Trigger (when the system runs)
Topic: How to set up the recurring trigger
Verbal: "First thing: the trigger. The system has to start itself — if you're manually starting it, you didn't automate anything. I use a free Cron schedule that fires every Friday at 5pm."
Demonstrate: Screen recording of setting up the Cron trigger
Pattern interrupt at 2:50: Cut to coffee shop, hold up phone showing Friday 5pm notification — "The first time this fired, I genuinely teared up. Felt like a real business."

[3:00-5:00] CONTENT BLOCK 2: The Data Pull (where the info comes from)
Topic: Connecting to your client data sources
Verbal: "Block 2: the data pull. This is where most people overcomplicate it. You don't need to pull from 14 sources. You need 3-4 max."
Demonstrate: Screen recording of building the data pull from Stripe + Notion + Google Sheets
Pattern interrupt at 4:50: "But the real magic is the next step — and this is the one that saved me 6 hours per client."

[5:00-8:00] CONTENT BLOCK 3: The Draft Generation (the AI part)
Topic: Using ChatGPT to draft the client report
Verbal: "This is the payoff. Once you have the data, you need a prompt that turns it into a report. Here's mine."
Demonstrate: Full prompt shown on screen, then the actual generated output side-by-side with the data, then the email it sends
This is the section the viewer paid attention for. 3 minutes of walking through the prompt exactly.

[8:00-end] RECAP + CTA + NEXT VIDEO
Recap: "Three blocks: trigger, data pull, draft. 90 minutes to set up. Saves me 4-6 hours a week, every week."
CTA: "If you want my prompt template — the exact one I use — link in description. It's free."
Next video tease: "And if you want to see me build the next automation (this one handles client onboarding — saves 3 hours per new client), I'll drop that link too."
```

## Why this structure works

1. **First 10 seconds deliver on the title.** No bait, no waiting.
2. **30-second credibility cap.** Viewers don't care about your story until they trust the content.
3. **Three content blocks** matches the brain's "rule of three" — easy to remember.
4. **Pattern interrupts every 60-90 sec** keep the retention curve from crashing.
5. **Tease forward** keeps viewers watching for the "best part" you've promised.
6. **Recap + next video** maximizes session time (YouTube algorithm reward).

## YouTube-specific rules

1. **Cut tightly.** Pacing matters more than production. Get rid of "uhm" and dead air.
2. **Front-load value.** The "best part" should come at the 60% mark, not the end. Viewers reward you for delivering early.
3. **One clear topic.** Multiple topics = lower retention. Pick one and go deep.
4. **No long branded intros.** "Welcome to [channel name] where we [generic]" kills retention. Skip it. The thumbnail is your branding.
5. **End on a high note.** The last shot is what they remember. Make it memorable.

## YouTube shorts (separate template)

For YouTube Shorts (<60 seconds, vertical), use the short video ad template (`templates/short_video_ad.md`) instead. Same physics as Reels/TikTok.

## Pre-delivery check

- [ ] First sentence matches the title
- [ ] First shot matches the thumbnail
- [ ] First 20 seconds exceed expectations (not just meet them)
- [ ] Three distinct content blocks (not one big block)
- [ ] Pattern interrupt every 60-90 seconds
- [ ] Credibility section under 30 seconds
- [ ] CTA is specific (not "subscribe!")
- [ ] Next video teased explicitly
- [ ] Total length 8-12 minutes (unless niche calls for longer)
