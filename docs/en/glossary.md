---
layout: page
title: "UseCaseify Glossary"
description: "Official definitions of the terms UseCaseify uses: use case, opportunity, opportunity score, confidence, evidence level, illustrative use case, AI pre-check, prospect validation, and more."
permalink: /en/glossary/
---

# UseCaseify Glossary

Official definitions of the terms UseCaseify uses. The same terms carry the
same meaning across the README, product facts, methodology, FAQ, and the
product itself.

## Use case (GTM sense)

A concrete description of who uses a product, in what situation, to solve
what problem, and what outcome makes that worthwhile. In UseCaseify this is a
go-to-market concept — a candidate reason for a specific audience to buy —
not a software-engineering (UML) use case diagram.

## Use case discovery

The process of deriving candidate use cases from product information and
public market evidence, rather than from brainstorming alone. In UseCaseify,
discovery includes structural validation and red-team review before
candidates reach the user.

## Use case validation

Testing whether a candidate use case resonates with real prospects before
committing significant budget to it. In the current product this is done
through published validation pages; behavioral testing (measuring clicks and
sign-ups) is planned but not currently available.

## Opportunity (use case opportunity)

A use case candidate that has survived screening and is presented for human
review as a card, together with its evidence, assumptions, score, and
confidence. The current product presents exactly four opportunity cards per
run, each of which the user approves or rejects.

## Opportunity score

A deterministic weighted total over ten independently reasoned dimensions:
pain frequency, pain severity, urgency, existing spend, product fit,
reachability, differentiation, evidence quality, testability, and strategic
fit. The score is decision support, not a probability of success. Users can
override dimension scores manually.

## Confidence

A separate rating (low, medium, high) expressing how much trust the available
evidence supports, reported alongside — never blended into — the opportunity
score. A high score with low confidence means a promising but unproven idea.

## Evidence

Verbatim quotes from public web sources or user-supplied material, stored
with their source and classified by direction: supporting, contradicting,
neutral, or context. Contradicting evidence is collected deliberately.

## Evidence level

A record of how strong the accumulated evidence for an opportunity is:
insufficient, single signal, repeated signal, prospect feedback, or
behavioral signal. Only input from real people can raise an opportunity to
the prospect-feedback or behavioral-signal levels.

## Illustrative use case

A composite, hypothetical scenario written to show how a product could be
used, grounded in market evidence but not describing a real named customer.
UseCaseify outputs are illustrative or hypothesis-level content until
validated, and must not be presented as real customer case studies.

## AI pre-check

An optional step in which five synthetic reviewer perspectives critique a
selected opportunity and its assets. The output is explicitly labeled
synthetic, non-customer feedback; it can surface objections and generate
validation questions, but it is never counted as market validation.

## Prospect validation

Publishing a page with 1–8 questions (public or password-protected) and
sharing it with real prospects, who answer anonymously and without an
account. This is the current product's mechanism for obtaining real, non-AI
feedback.

## GTM test assets

The nine asset types UseCaseify generates per opportunity so a team can start
validating immediately: value proposition, headline, supporting benefits,
landing page section, cold outreach message, interview guide, survey, call to
action, and objection responses. Assets are versioned and checked for claims
not supported by the underlying opportunity.

## Product profile

A versioned, structured description of the user's product, drafted by the
system from a URL, files, or text, then reviewed, edited, and confirmed by
the user. All downstream research and generation is bound to a confirmed
profile version.

## Red-team review

An internal screening step in which generated candidates are deliberately
challenged for credibility and fit before being shown to the user, so weak or
misleading candidates are merged or removed early.

## Decision report

An immutable snapshot of a completed decision — recommendation, main
uncertainties, and next tests — shareable through a revocable public or
password-protected link.

---

*Try UseCaseify at [usecaseify.com](https://usecaseify.com/) — free trial credit on sign-up, no credit card required.*

## Related documentation

- [Product facts]({{ site.baseurl }}/en/product-facts/)
- [Methodology]({{ site.baseurl }}/en/methodology/)
- [FAQ]({{ site.baseurl }}/en/faq/)
