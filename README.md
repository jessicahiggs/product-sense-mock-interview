# Product Sense Mock Interview Partner

Written by Jessica Higgs.

A Claude skill that runs a live, timed mock **product sense interview** — the kind of case
interview used for PM roles at most top tech companies ("Design a product for X," "How would you
improve Y for Z users").

Claude plays a realistic interviewer: it presents a case, asks probing questions, pushes back on
hand-waving, and challenges your prioritization calls — without spoon-feeding you the framework
structure. It tracks real elapsed time per section against target pacing, and closes with
detailed narrative feedback (no scores or grades — just specific, quotable critique).

## What it looks like

You bring a case (or ask for one), and Claude runs the session as a real interviewer would —
probing, pushing back, and holding you to your choices. A short excerpt (illustrative):

```text
Interviewer: Let's do a case. "Design a feature for a music app to help
people discover new podcasts." Before anything else — why would we build
this at all?

You: Podcasts are a growth area and we want to increase engagement.

Interviewer: "Increase engagement" is true of almost any feature. Tie it to
the business — what does podcast discovery specifically do for this company
that its music catalog doesn't?

You: Podcasts drive longer, habitual daily sessions and open a new ad
inventory the music side can't, so it grows both retention and revenue.

Interviewer: Better. Who exactly are we designing for? Don't say "everyone."

You: I'd focus on existing music listeners who are podcast-curious but
haven't converted — they already trust the app but default to music.

Interviewer: Why that segment over lapsed podcast listeners, who've already
shown intent?

  ... [case continues through pain points, mission, solutions,
      and prioritizing one] ...
```

When the case ends, it drops the interviewer persona and gives you an honest read:

```text
Pacing — that took about 12 minutes.

Where it was strong — your motivation landed once you tied discovery to a
distinct ad inventory; that's a real business case, not just "engagement."

Where it was thin — your segmentation only cut the audience one way. You
never compared "podcast-curious music listeners" against, say, commuters
who want hands-free listening, or parents wanting kids' content — so the
choice read as a default rather than a decision.

Highest-leverage fix — commit to one solution faster. You floated three
strong ideas but hedged on which wins; interviewers read that as avoiding
the hard call. Pick one and defend it against the runner-up.
```

No scores or grades — just specific, quotable feedback tied to what you actually said.


See [`references/framework.md`](product-sense-mock-interview/references/framework.md) for the full
framework with sub-questions and the default timing breakdown for a 40-minute session.

## Installing

**Claude Code / Claude Agent SDK / Cowork:** drop the `product-sense-mock-interview/` folder into
your skills directory (or install the packaged `.skill` file if you have one), then in a
conversation just say something like:

> Mock interview me on this: "Design a feature for Spotify to increase podcast discovery."

**No case handy?** Ask Claude to give you one — it'll generate a realistic case from a real
company/product area.

## Customizing

The framework in `product-sense-mock-interview/references/framework.md` is easy to swap out for
your own case-interview structure — the steps in `SKILL.md` (kickoff, time-tracking, running the
case, feedback) are generic enough to work with any ordered, multi-step interview framework, not
just this one.

## License

MIT — see [LICENSE](LICENSE).
