---
layout: page
title: "Whitepaper: Go-to-Market Decisions Before Customer Evidence"
description: "UseCaseify whitepaper v1.0 (July 2026). Why use case decisions fail before product-market fit, and how evidence-based discovery and validation structures them."
permalink: /en/whitepaper/
---

# Go-to-Market Decisions Before Customer Evidence

**UseCaseify Whitepaper v1.0** ·
Published 2026-07-12 · Publisher: LLM JAPAN, LLC

> This whitepaper describes the current UseCaseify product (beta, as of July
> 2026). For exact current capabilities, limitations, and pricing, see
> [Product facts]({{ site.baseurl }}/en/product-facts/). Anything under
> "Future direction" is not currently available and carries no committed date.

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "TechArticle",
  "headline": "Go-to-Market Decisions Before Customer Evidence",
  "version": "1.0",
  "datePublished": "2026-07-12",
  "inLanguage": "en",
  "author": { "@type": "Organization", "name": "LLM JAPAN, LLC" },
  "publisher": { "@type": "Organization", "name": "LLM JAPAN, LLC" },
  "about": "UseCaseify"
}
</script>

## 1. Executive summary

The product exists. The case studies don't. At this stage a team's hardest
problem is not building — it is deciding **which use case, audience, and value
proposition to bet on first**, without the customer evidence that would
normally justify the bet.

This paper describes a way to make that decision from traceable market
evidence and feedback from real prospects rather than from intuition or a
single AI brainstorming session. Three commitments define the approach:

1. Separate *generating* ideas from *choosing* which idea deserves budget.
2. Never blur the line between source facts, AI inference, synthetic
   feedback, and feedback from real people.
3. Feed validation results back into the recommendation, and freeze the
   decision in a report that can be traced afterwards.

UseCaseify implements this approach as a product, but the methodology can be
applied with or without the tool.

## 2. The problem: messaging before evidence

Early-stage products live inside a paradox. Winning the first customers
requires a clear value proposition and concrete use cases; knowing which
value proposition and use cases are right requires customer feedback. The
evidence is needed at exactly the moment it does not yet exist.

What actually happens in most teams is one of the following:

- **Founder intuition plus an internal vote.** The team picks the direction
  that "sounds right." When it fails, nobody can tell whether the product,
  the audience, the channel, or the wording was wrong.
- **A pile of AI-generated scenarios.** A general-purpose chat produces a
  dozen plausible use cases in seconds. The options multiply; the decision
  gets harder, because nothing distinguishes ideas grounded in real market
  signals from fluent invention.
- **Manual desk research.** Search results and forum threads confirm that a
  problem is *discussed*. They say nothing about whether anyone will pay,
  and the findings never connect to the copy that eventually ships.
- **Jumping straight to market tests.** Landing pages and ads are the right
  instinct, but running them before deciding *what to test* spends
  production and ad budget on hypothesis selection.

What is missing in every variant is the same pair of things: a **shared
structure that makes candidates comparable**, and a **hard line between what
is evidence and what is guesswork**.

## 3. Why generic AI generation is not a decision

Large language models are excellent at producing use case ideas and terrible,
on their own, at telling you which one to bet on. Four gaps matter:

- **No grounding guarantee.** A fluent scenario reads the same whether it
  reflects a real market signal or none at all.
- **No contradiction search.** A chat answers the question it was asked;
  it does not go looking for evidence *against* the idea it just produced.
- **No comparable scoring.** Ten ideas from one prompt do not come with a
  consistent basis for ranking them.
- **No validation path.** The conversation ends at text. Nothing connects
  the idea to real prospects, and nothing updates when reality answers back.

None of this makes generic AI useless — it makes it an ideation layer. A
decision needs the layers above it: evidence, comparison, validation, and
memory.

## 4. Evidence before recommendation

The methodology starts by making evidence a first-class object rather than a
research byproduct:

- Every finding is stored as a **verbatim quote with its source**, not as a
  paraphrase that quietly drifts from what was actually said.
- Evidence is classified by direction — **supporting, contradicting, neutral,
  or context** — and contradicting evidence is *sought deliberately*.
  Research that only collects support is confirmation bias with a UI.
- Evidence is bound to the **exact version of the product understanding** it
  was gathered for. When the product inputs change, stale conclusions are
  invalidated instead of silently reused.

Public web evidence has a known ceiling: it shows that a problem is talked
about, not that anyone will pay to solve it. The methodology treats it as a
weak signal by design, sufficient to *rank hypotheses*, never to declare a
market validated.

## 5. Scoring that stays honest

Candidate use cases are screened (structural validation plus red-team
review), and the survivors are scored on ten dimensions — pain frequency,
pain severity, urgency, existing spend, product fit, reachability,
differentiation, evidence quality, testability, and strategic fit. Each
dimension is reasoned independently; the total is a **deterministic weighted
sum**, not a model's overall impression.

Two separations keep the score honest:

- **Confidence is reported next to the score, never inside it.** A
  high-scoring opportunity with thin evidence stays visibly unproven.
- **Evidence level is tracked on its own scale** — from insufficient, through
  single and repeated public signals, up to levels only real people can
  grant: prospect feedback and behavioral signal.

When no candidate reaches sufficient confidence, the honest output is to
**withhold the recommendation**. "The evidence does not support a bet yet"
is a more valuable answer than a forced ranking.

## 6. Synthetic feedback is not customer evidence

Before spending anything on outreach, an opportunity can be stress-tested by
synthetic reviewers — AI perspectives that attack the idea and its materials
from different angles. This is cheap and useful for finding objections early,
and it is **permanently labeled as synthetic, non-customer feedback**.

Validation begins only where real people enter: a published validation page,
answered anonymously by actual prospects, with explicit consent and optional
contact details. Only these responses can raise an opportunity's evidence
level. The distinction is not a disclaimer buried in a footer; it is enforced
in the data model.

## 7. The learning loop

Prospect responses are summarized and clustered into insights, which produce
**suggestions** — score changes and an updated recommendation — that take
effect only when a human accepts them, with provenance recorded. The loop is
deliberately conservative: reality proposes, the team disposes.

## 8. Deciding on the record

The outcome — the recommendation, the main uncertainties, and the next tests
— is frozen into an immutable decision report, shareable through a revocable
link. Six months later, the team can see not just *what* was decided but
*on what evidence*, which is the difference between a decision and a mood.

## 9. Limitations

- Public evidence shows discussion, not willingness to pay.
- Synthetic reviewers surface objections; they cannot replace conversations
  with real customers.
- Small validation samples support directional judgment, not statistical
  significance.
- Scores inherit the quality of the product information provided and the
  public evidence that exists; thin markets yield honestly thin results.
- Neither the methodology nor the product predicts or guarantees
  product-market fit or any business outcome.

## 10. Future direction

Behavioral validation — measuring real clicks and sign-ups on test pages —
is the natural next evidence level and is planned but not currently
available. Until it ships, the strongest evidence reachable in practice is
structured feedback from real prospects.

## Publication

- Publisher: LLM JAPAN, LLC (Tokyo, Japan)
- Product: [https://usecaseify.com/](https://usecaseify.com/)
- Contact: [support@usecaseify.com](mailto:support@usecaseify.com)
- Citation: see [CITATION.cff](https://github.com/llmjp/usecaseify/blob/main/CITATION.cff);
  reference this page's URL and version (v1.0, 2026-07-12).

---

*Try UseCaseify at [usecaseify.com](https://usecaseify.com/) — free trial credit on sign-up, no credit card required.*

## Related documentation

- [Product facts]({{ site.baseurl }}/en/product-facts/)
- [Methodology]({{ site.baseurl }}/en/methodology/)
- [End-to-end example]({{ site.baseurl }}/en/examples/end-to-end-example/)
- [Glossary]({{ site.baseurl }}/en/glossary/)
