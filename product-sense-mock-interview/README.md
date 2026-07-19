# Product Sense Mock Interview Partner

A Claude skill that runs a live, timed mock **product sense interview** — the kind of case
interview used for PM roles at most top tech companies ("Design a product for X," "How would you
improve Y for Z users").

Claude plays a realistic interviewer: it presents a case, asks probing questions, pushes back on
hand-waving, and challenges your prioritization calls — without spoon-feeding you the framework
structure. It tracks real elapsed time per section against target pacing, and closes with
detailed narrative feedback (no scores or grades — just specific, quotable critique).

It's built around an 8-step **Sense Framework**:

1. **Why?** — motivation, business case, competitive landscape, risk
2. **Who?** — segment the ecosystem, pick one sub-segment to prioritize
3. **User journey & pain points** — map 3-5 pain points, pick one to prioritize
4. **Set product mission** — a one-line mission tying segment + pain point together
5. **Prioritize criteria for solutions** — what will make a solution good
6. **Solutions** — generate 3, mixing moonshot and practical
7. **Prioritize 1 solution** — justified by the mission, impact, and scalability
8. **Measure success** — define the critical action that counts as "engaged"

See [`references/framework.md`](references/framework.md) for the full framework with sub-questions
and the default timing breakdown for a 40-minute session.

## Installing

**Claude Code / Claude Agent SDK / Cowork:** drop the `product-sense-mock-interview/` folder into
your skills directory (or install the packaged `.skill` file if you have one), then in a
conversation just say something like:

> Mock interview me on this: "Design a feature for Spotify to increase podcast discovery."

**No case handy?** Ask Claude to give you one — it'll generate a realistic case from a real
company/product area.

## Customizing

The framework in `references/framework.md` is easy to swap out for your own case-interview
structure — the steps in `SKILL.md` (kickoff, time-tracking, running the case, feedback) are
generic enough to work with any ordered, multi-step interview framework, not just this one.

## License

MIT — see [LICENSE](LICENSE).
