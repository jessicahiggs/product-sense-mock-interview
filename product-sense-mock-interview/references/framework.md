# The Sense Framework

This is a product sense framework for interview cases ("build a product for X",
"how would you improve Y", "design a product for Z"). It has 8 steps. Run candidates through
them in order — the order matters, because each step's output feeds the next one (the segment
picked in step 2 shapes the pain points in step 3, the pain point picked in step 3 shapes the
solutions in step 6, etc.).

Each step below lists the sub-questions a strong candidate should hit and what a good answer
sounds like, so you can probe and grade accordingly. Target time allocations for a 40-minute
session are given in `## Timing` at the bottom — adjust proportionally for shorter/longer sessions.

## 1. WHY? (motivation)

The candidate should establish why the company would build this before jumping to who/what.

- Is it compatible with the company's mission statement?
- How would this benefit the business? Strong answers name a concrete mechanism (revenue,
  retention, new TAM) and reference real industry verticals the company could leverage.
- Who are the competitors, and what's the competitive landscape?
- What's the competitive advantage — and does it connect back to the company's actual business
  model (not just "it would be cool")?
- Are there notable risks in pursuing this (regulatory, brand, cannibalization, execution)?

A weak answer skips straight to features. A strong answer sounds like a mini business case.

**As interviewer, keep this step light.** The main thing to check is that the candidate anchors
motivation to the company's actual mission — don't interrogate the details of every risk or
competitor they name, or turn it into a debate. Deep adversarial follow-ups belong to the steps
where the candidate has to defend a specific choice (segment, pain point, solution) — see
`SKILL.md` for which steps those are. If mission alignment is there, move on.

## 2. WHO?

- Identify both sides of the ecosystem if the product is a marketplace/platform (e.g.
  supply + demand, creators + viewers, drivers + riders). Only sub-segment ONE side —
  segmenting both sides at once is a common candidate mistake and worth flagging.
- Consumers/demand-side users are usually the right side to sub-segment: they typically drive
  demand, represent the larger TAM, and have the most underserved needs.
- The candidate should pick ONE sub-segment to prioritize, and justify it using:
  - Engagement level
  - Motivation
  - Impact (size/value of the opportunity this segment represents)

Push back if they pick a segment without comparing it to at least one alternative.

**Watch for thin segmentation** — a candidate who only cuts the population one way (e.g. just by
motivation, or just by demographics) or names a segment without any real detail behind it (no
sense of size, behavior, or need) hasn't given you much to evaluate. In the wrap-up feedback,
if this happened, explicitly suggest they practice segmenting the same population along multiple
different dimensions, and back each segment with concrete detail — that range is what makes the
eventual prioritization choice convincing rather than arbitrary. Don't just name the dimensions
abstractly — make it concrete by sketching 1-2 alternative segmentations *for this specific case*
they just did, so they can see what they missed. E.g. for a shopper on a case like this: they cut
by motivation (functional / inspiration / life-event) — you could also point out they could have
cut by behavior (planners who research ahead vs. walk-in browsers), by trip frequency (regulars
vs. rare visitors), or by household type (furnishing solo vs. furnishing for a family). Generate
examples like this fresh for whatever case is actually in front of you — don't reuse a canned
list across different cases.

## 3. User Journey & Pain Points

- Map 3-5 pain points that cover the *entire* journey of the chosen segment (not just one
  moment) — awareness/entry, core usage, retention/exit are a good sanity check for coverage.
- Watch for candidates who narrate the journey as a sequence of steps ("they walk in, browse the
  showroom, grab items from the warehouse, checkout") without ever naming what's actually
  frustrating, slow, or unmet at each step. That's a journey map, not pain points — push them:
  "okay, so what's actually hard about that step?" A journey walkthrough on its own doesn't
  satisfy this section.
- Pain points should be phrased as: **"I want to do X, but I can't because of Y."** If a
  candidate states a pain point as a solution in disguise ("users need a recommendation
  engine"), redirect them to restate it as a pain point first.
- The candidate picks ONE pain point to prioritize — or exceptionally two, if they can make the
  case that a single solution would credibly solve both at once. Two picks without that link is
  a sign they're avoiding the hard call; push them to actually choose. The choice (whether one
  or a justified two) should be backed by:
  - Impact — how big a difference solving it would make
  - Potential for engagement — engagement is a leading indicator of whether the solution would
    actually add value, so a pain point with high engagement upside is worth more than one that's
    merely "important"

**If the candidate's pain points don't cover the whole journey** (e.g. they only cover the
in-store part and miss pre-trip planning or post-purchase/delivery, or they cluster several
points around one moment and skip others), name the gap in the wrap-up feedback and give 1-2
concrete examples of pain points they missed — specific to this case and this segment, phrased in
the same "I want X but can't because of Y" format, not generic advice like "cover more of the
journey." Generate these fresh from the actual case; don't reuse examples across different cases.

## 4. Set Product Mission

- A one-line mission statement for the product being designed, tying together the segment (step
  2) and the pain point (step 3). This should be crisp — one sentence, not a paragraph — and
  should make the rest of the case feel goal-directed rather than a grab-bag of ideas.
- Once the candidate gives the mission, don't stop to interrogate it — move straight to asking
  for solutions. The mission gets checked for coherence at the end (does the mission reflect the
  segment/pain point picked earlier, does the eventual solution tie back to it), not mid-session.

## 5. Prioritize Criteria for Solutions

Before brainstorming, a strong candidate will have articulated what will make a solution *good*,
using these criteria (they may pick 1 or 2 of these to lead with — using all 4 with equal weight
is a sign they haven't actually prioritized):

1. Severity of the pain
2. Alignment with the company's strengths
3. Whether solutions already exist that solve this problem (whitespace vs. crowded)
4. Risk of execution

**Don't prompt for this as its own separate question** — after the mission, go straight to
asking for solutions. Listen for whether these criteria show up in how the candidate presents
and justifies their solutions; if none of them surface, that's something to name in the
wrap-up feedback rather than something to stop and ask about mid-session.

## 6. Solutions

- Generate 3 solutions that address the chosen pain point.
- Good sets mix a moonshot with practical ideas — all-safe or all-crazy is a flag.
- Encourage creative range: what if an existing solution changed *format* (text → video/
  immersive), changed *audience* (expand age groups targeted), became a *marketplace*, added
  an *AI* layer, went *immersive/VR*, or became an *ambient/companion AI* (Meta Ray-Bans-style)?
  These are prompts to spark range, not a checklist the candidate needs to hit.

**If the solution set is narrow** (all practical and safe, all moonshot with nothing shippable,
or three variations on the same idea), name that in the wrap-up feedback and sketch 1-2 concrete
alternative solutions they could have proposed instead — specific to the pain point and mission
from *this* case, not generic categories. E.g. don't just say "you could have gone more moonshot"
— actually describe what that solution would look like for their case. Generate these fresh each
time; don't reuse examples across different cases.

## 7. Prioritize 1 Solution

- Pick one of the three solutions, justified by fit with the product mission (step 4), impact,
  and scalability. The justification should reference the mission stated in step 4 — if it
  doesn't, ask "how does this tie back to the mission you set?"
- **The required live Q&A ends here.** Once the candidate has prioritized a solution and defended
  it, the case is essentially done. See step 8 for the one optional thing you can still ask.

## 8. Measure Success

- Define the metric: % of people who enter the product and take a critical action. This is the
  bar to clear to be considered "engaged."
- A strong candidate defines what the "critical action" actually is for this specific solution
  (not just "engagement" in the abstract), and explains why that action is the right proxy for
  value delivered.
- This is optional, not required. After step 7, you may ask one light question — e.g. "how would
  you know this actually worked?" — but don't push if the candidate would rather wrap up or
  doesn't want to go there; that's a fine place to end the case. If they do answer, evaluate it
  against the criteria above in the wrap-up feedback. If they don't (whether because you didn't
  ask, or they passed), don't treat it as a gap they were tested on and missed — at most, note in
  feedback that defining a success metric is a good habit to build in.

## Timing (40-minute session default)

Live Q&A runs through step 7 (prioritize the solution) — step 8 (measure success) isn't a live
question, see the note under step 8 above, so it isn't given its own timing slot below.

| # | Section | Target |
|---|---------|--------|
| — | Intro + case framing | 2 min |
| 1 | Why (motivation) | 3 min |
| 2 | Who (segmentation) | 5 min |
| 3 | User journey & pain points | 7 min |
| 4 | Set product mission | 2 min |
| 5 | Prioritize criteria for solutions | 3 min |
| 6 | Solutions (brainstorm 3) | 8 min |
| 7 | Prioritize 1 solution | 3 min |
| — | Wrap-up feedback / candidate questions | 7 min |

Scale proportionally if the candidate requests a different total length (e.g. a 25-minute
express round, or a 60-minute deep round) — keep the relative weights, don't just chop sections.
