# Format Specifications

Each format has its own physics — aspect ratios, length constraints, captioning rules, hook windows. Use this reference before writing for any specific platform.

## Quick reference table

| Format | Length | Aspect | Captions | Hook window |
|---|---|---|---|---|
| Short video ad (Meta/IG/TikTok) | 15-30 sec | 9:16 vertical | Required | 3 sec |
| Mid-form video ad | 30-60 sec | 9:16 vertical | Required | 3 sec |
| Static image ad | n/a | 1:1 or 4:5 | Text-on-image | Headline = hook |
| Carousel ad | 3-10 slides | 1:1 square | Per-slide text | Slide 1 = hook |
| YouTube long-form | 5-15 min | 16:9 horizontal | Optional | 10 sec |
| YouTube Shorts | <60 sec | 9:16 vertical | Required | 3 sec |
| VSL (short) | 3-6 min | 16:9 or 9:16 | Optional | 10 sec |
| VSL (long) | 8-15 min | 16:9 | Optional | 30 sec |
| Webinar / workshop | 45-90 min | 16:9 | Live captions | First 5 min |
| Email | 50-300 words | n/a | n/a | Subject line |

---

## Short-form video ad (Meta, Instagram, TikTok)

The workhorse format. 15-30 seconds, vertical, UGC style outperforms polished production in 2026 across most categories.

**Specs:**
- **Aspect ratio:** 9:16 vertical (Meta is moving to ~90% vertical inventory)
- **Length:** 15-30 sec optimal; sub-15 for awareness, 30 for direct response
- **Captions:** Required (85% of users watch with sound off)
- **Hook window:** First 3 seconds — 65% of viewers who pass 3 sec watch 10+ sec
- **Cut frequency:** Visual cut every 3-5 seconds for retention
- **Music:** Quiet or off (UGC feel). Avoid stock music swells.
- **CTA placement:** Verbal mid-script + on-screen text at end

**Structure (use Hook-Body-CTA from frameworks.md):**

```
0-3 sec:    HOOK (one of the 7 hook types)
3-8 sec:    PROBLEM or PROMISE (extend the hook)
8-20 sec:   PROOF or DEMONSTRATION (show, don't tell)
20-28 sec:  OUTCOME or RESULT
28-30 sec:  CTA
```

**Production rules:**
- Start mid-thought, never "Hey guys" or "So today..."
- Talking head + screen recording is the dominant high-converter
- Native phone-quality video outperforms studio-quality for cold traffic
- Brand logo only at the very end if at all

**See template:** `templates/short_video_ad.md`

---

## Static image ad

Static drives 60-70% of Meta conversions despite the hype around video. Cheaper to produce, easier to iterate. The "script" for a static is the visual hierarchy — the order the eye moves through the ad.

**Specs:**
- **Aspect ratio:** 1:1 (square) for feed; 4:5 portrait for mobile feed; 9:16 for Stories/Reels placements
- **Image resolution:** Minimum 1080x1080 for square
- **Text-on-image limit:** Meta removed the 20% text rule, but heavy text still underperforms — keep critical text concise
- **Hook = headline:** Top of image, largest text, 5-10 words max

**Visual hierarchy (read order):**

Most viewers read in a Z-pattern: top-left → top-right → bottom-left → bottom-right. Place hook top-left, image in center, CTA bottom-right.

**Text size hierarchy:**
- Headline: 36-48px, bold, high contrast
- Subhead: 24-30px, medium weight
- Body: 18-24px, regular weight
- CTA: 20-28px, bold, button format

**Three high-performing static formats:**

1. **Meme card / pure text** — bold text on solid color background, minimal else
2. **Annotated screenshot** — actual screenshot with arrows and text overlays
3. **Before/After split** — side-by-side comparison

**Production rules:**
- One clear focal point (no clutter)
- Native, unbranded look outperforms polished branded look
- High contrast between text and background
- One CTA only

**See template:** `templates/static_ad.md`

---

## Carousel ad

Top-performing format for many course/product offers in 2026. Multi-slide story format. The swipe motion increases dwell time, which Meta's algorithm rewards.

**Specs:**
- **Aspect ratio:** 1:1 square (universal); some platforms support 4:5
- **Slide count:** 5 is the sweet spot; minimum 3, maximum 10
- **Each slide:** Readable in 1 second; standalone meaning
- **Caption text:** Each slide can have its own headline/subhead

**Structure (each slide is one beat):**

```
Slide 1: HOOK (text-heavy, fast read)
Slide 2: PROBLEM expanded
Slide 3: MECHANISM or step
Slide 4: OUTCOME / proof
Slide 5: CTA (with visual arrow or "→")
```

**Production rules:**
- Each slide stands alone — viewer might not swipe past slide 1
- Slide 1 hook decides everything; treat it as a static ad on its own
- Consistent visual style across slides (color, typography)
- Final slide must include the CTA — don't bury it

**See template:** `templates/carousel.md`

---

## YouTube long-form (5-15 minutes)

Different physics from feed ads. The viewer clicked deliberately — they're not scrolling past. The job of the hook is *retention*, not capture.

**Specs:**
- **Aspect ratio:** 16:9 horizontal (mobile and desktop)
- **Length:** 8-12 min hits the YouTube algorithm sweet spot for most niches
- **Hook window:** First 10 seconds (MrBeast principle: match the thumbnail and title in the first sentence and first shot)
- **Pattern interrupts:** Every 60-90 seconds (visual change, audio change, location change, or verbal "but here's where it gets interesting")

**Structure (7-part):**

```
0:00-0:10  HOOK + PROMISE (deliver on thumbnail/title instantly)
0:10-0:30  WHY THIS MATTERS (raise the stakes)
0:30-1:00  CREDIBILITY (briefly — why you)
1:00-3:00  CONTENT BLOCK 1 (with pattern interrupt at end)
3:00-5:00  CONTENT BLOCK 2 (with tease for what's coming)
5:00-8:00  CONTENT BLOCK 3 (the payoff / biggest insight)
8:00-end   RECAP + CTA + NEXT VIDEO
```

**The MrBeast principle:** Meet expectations + exceed them within first 20 seconds. First sentence matches the title. First shot matches the thumbnail.

**Production rules:**
- Cut tightly — pacing matters more than production value
- Pattern interrupts every 60-90 sec or retention curves crash
- Single clear topic per video (multiple topics = lower retention)
- End with a teaser for the next watch, not a generic "subscribe!"

**See template:** `templates/youtube_longform.md`

---

## VSL (Video Sales Letter)

Long-form persuasive video that does the work of a sales page. Two flavors.

### Short VSL (3-6 minutes)

**Use for:** Warm traffic, $17-$297 offers

**Structure:**
```
0:00-0:15  Pattern interrupt
0:15-0:45  Promise
0:45-1:30  Problem (vivid)
1:30-2:30  Solution introduction
2:30-3:30  Proof
3:30-4:30  Offer + risk reversal
4:30-5:00  CTA
```

### Long VSL (8-15 minutes)

**Use for:** Cold traffic, $497+ offers

**Structure:** Full 10-part VSL from frameworks.md (Pattern Interrupt → Promise → Problem → Agitate → Solution → Proof → Offer → Risk Reversal → CTA → FAQ)

**Specs:**
- **Aspect ratio:** 16:9 (or 9:16 for mobile-only audiences)
- **Format:** Talking head + slides, or full slides with voiceover
- **Pacing:** Brisk — modern VSLs are tighter than 2015-era VSLs
- **Captions:** Recommended (some viewers will skim)

**See template:** `templates/vsl.md`

---

## Webinar / Workshop (45-90 minutes)

Live or pre-recorded long-form sales presentation. Highest-converting format for $200-$5000 offers.

**Specs:**
- **Length:** 45-90 minutes (45 min sweet spot for B2B, 60-90 for course/coaching)
- **Format:** Slides + presenter on camera (small or PIP)
- **Captions:** Live captions recommended for accessibility + engagement
- **Engagement:** Polls, questions in chat, reactions every 10-15 minutes

**The 69% number:** Webinars where attendees average 5-10 reactions each convert at ~69%. Low-engagement webinars convert at <20%. Engagement is the single highest variable.

**Structure (Perfect Webinar adapted):**

```
0:00-0:15  Welcome + Origin Story (build trust)
0:15-0:45  Three Secrets (break false beliefs, teach tactics)
0:45-1:00  Stack & Close (reveal offer)
1:00-1:30  Q&A (where conversion happens)
```

**Production rules:**
- 20-25 min teaching + 30-40 min Q&A often outperforms 60 min teaching + 15 min Q&A
- Same content every week (refine, don't rebuild)
- Trial closes every 10 minutes ("type 'yes' if this is you")
- Don't apologize for the pitch
- Stay past the scheduled end — buyers are the last ones to leave

**See template:** `templates/webinar.md`

---

## Email sequences

Email is the highest-converting channel by ROI for most digital products. Lists convert at 10%+ when warm; channel benchmark for paid social is 0.9%.

**Specs:**
- **Subject line:** 30-50 characters (mobile cutoff), front-load the hook
- **Preview text:** 35-90 characters — treat as second headline
- **Body length:** 50-300 words for promotional; longer for nurture/story
- **Single CTA:** One link, repeated 2-3 times for longer emails

**Structures:**

1. **Welcome sequence (5-7 emails over 7-10 days):**
   - Day 0: Deliver lead magnet + intro
   - Day 1: Story (yours or a customer's)
   - Day 3: Tactical value email (no pitch)
   - Day 5: Soft offer
   - Day 7: Direct offer with social proof
   - Day 10: Last call (if deadline) or transition to weekly nurture

2. **Launch sequence (3-5 emails over 3-7 days):**
   - Email 1: Open cart announcement + story
   - Email 2: Mid-launch (objection handling)
   - Email 3: Final 24 hours
   - Email 4: Last 4 hours (often the highest-converting)

3. **Weekly nurture (1 email/week, indefinite):**
   - Pure value, occasional soft offers
   - Build the relationship; pitch when relevant

**See template:** `templates/email.md`

---

## Platform-specific notes

### Meta (Facebook + Instagram)

- Andromeda algorithm (rolled out 2024-2025) rewards creative diversity over targeting precision
- Advantage+ campaigns now outperform manual targeting in most accounts
- Test 5-20 creative variations per campaign, not 1-2 with multiple ad sets
- Refresh ads every 2-4 weeks (when frequency exceeds 3.0 or CTR drops 20%)
- Static still drives 60-70% of conversions

### TikTok

- Pattern interrupt is required, not optional
- Trending sounds can boost reach but the half-life is days
- UGC-style is the only style that consistently works
- Captions on every video
- Hooks must be in the first 1.5 seconds (faster than Meta)

### YouTube

- Thumbnail + title + first 10 seconds work as a system
- Mid-roll ads disrupt retention — front-load value
- Long-form (8-12 min) outperforms shorts for monetization but shorts win for top-of-funnel reach

### LinkedIn

- Text-first platform; visual hooks matter less
- "See more" fold after first two lines is the hook boundary
- Credibility-led hooks outperform curiosity-led
- Comments and reposts > likes

### Landing pages

- Above-fold = hook (headline + subhead + CTA visible without scrolling)
- One CTA, repeated down the page
- Video on landing page can boost conversions ~80% (Unbounce)
- Mobile-optimized or 35%+ conversion loss

## When you don't know which format

If the user hasn't specified a format, ask:

> "What format — short video ad, static image, carousel, webinar, email, or something else?"

If they say "I just need an ad," default to short-form video ad (most versatile, highest-volume format). Make that explicit: "I'll start with a 30-second video ad. Tell me if you want a different format."
