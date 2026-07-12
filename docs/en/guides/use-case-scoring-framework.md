---
layout: page
title: "The Use Case Scoring Framework: Ten Dimensions Explained"
description: "How UseCaseify scores use case opportunities: what each of the ten dimensions measures, how the deterministic total works, why confidence is separate, and when a recommendation is withheld."
permalink: /en/guides/use-case-scoring-framework/
---

# The Use Case Scoring Framework: Ten Dimensions Explained

An opportunity score exists to make use case candidates **comparable** — to
replace "the one we discussed longest wins" with a fixed set of questions
asked of every candidate. It is decision support, not market truth: a score
summarizes today's evidence and reasoning, and real feedback can and should
change it.

## The ten dimensions

Each dimension is reasoned independently, with its own justification,
so you can see *why* a candidate scores the way it does — and challenge it.

| Dimension | The question it asks |
|---|---|
| Pain frequency | How often does the target user hit this problem? |
| Pain severity | What does it cost them when they do? |
| Urgency | Do they need it solved now, or someday? |
| Existing spend | Is money (or paid staff time) already going to alternatives? |
| Product fit | How well does the actual product solve this specific problem? |
| Reachability | Can this audience be reached through channels you actually have? |
| Differentiation | In this use case, is there a reason to pick you over the obvious alternative? |
| Evidence quality | How strong and how plural are the sources behind the above? |
| Testability | Can this be validated cheaply and quickly? |
| Strategic fit | Does winning here fit the team's capabilities and direction? |

## How the total is calculated

The total is a deterministic weighted sum:

```
Total score = Σ (dimension score × configured weight)
```

The arithmetic is not a model's overall impression — the same dimension
scores always produce the same total. The exact production weights may be
tuned during beta; the public framework explains the reasoning model, not a
permanent ranking guarantee.

Two guard rules apply regardless of weights: a candidate with a confirmed
product capability gap cannot score high on product fit, and a candidate
that cannot be tested is floored on testability.

## Confidence is not part of the score

Alongside every score, UseCaseify reports **confidence** (low / medium /
high) and an **evidence level** (insufficient → single signal → repeated
signal → prospect feedback → behavioral signal). A candidate can score 75
with low confidence: promising on paper, thin underneath. Blending that
uncertainty into the number would hide exactly what you need to see.

## Missing data and contradictions

Missing data lowers evidence quality and confidence — it does not silently
default to average. Contradicting evidence is kept attached to the
opportunity, and unresolved contradictions are surfaced with the
recommendation, not smoothed over.

## Manual override

Scores can be overridden by the user, because the team knows things the
public web does not. Overrides are recorded, and downstream conclusions
(recommendations, reports) are invalidated and recomputed rather than left
stale.

## Why a recommendation is sometimes withheld

When no non-rejected candidate reaches sufficient confidence and evidence,
UseCaseify names no primary recommendation. A forced ranking over weak
evidence would be confident-sounding noise; "not enough evidence yet, here
is what to test" is the more useful output.

## Rescoring after validation

Real prospect responses generate score-change suggestions with stated
reasons. They apply only when you accept them, with provenance kept — so the
score's history tells you not just where the bet stands, but what moved it.

---

*Try UseCaseify at [usecaseify.com](https://usecaseify.com/) — free trial credit on sign-up, no credit card required.*

## Related documentation

- [Methodology]({{ site.baseurl }}/en/methodology/)
- [End-to-end example]({{ site.baseurl }}/en/examples/end-to-end-example/)
- [Product facts]({{ site.baseurl }}/en/product-facts/)
- [Glossary]({{ site.baseurl }}/en/glossary/)
