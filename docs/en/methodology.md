---
layout: page
title: "UseCaseify Methodology"
description: "How UseCaseify separates market evidence, AI inference, synthetic pre-checks, and real prospect feedback when discovering and validating use cases."
permalink: /en/methodology/
---

# UseCaseify Methodology

## Purpose

UseCaseify supports one decision: **which use case, audience, and value
proposition should a product take to market next, before it has enough
customer evidence to know for sure.** Free-form AI generation is not enough
for this decision, because it produces plausible ideas without showing which
are grounded in real market signals, which contradict them, and which remain
untested guesses. The methodology below exists to keep those categories
apart from the first research step to the final report.

## Inputs

The system currently works from:

- product information the user provides — a website URL, uploaded files, or
  written text;
- public web pages found through web research, quoted verbatim with their
  sources;
- evidence the user adds manually;
- the user's own judgments — profile confirmation, approvals and rejections,
  written feedback, and score overrides;
- responses from real prospects submitted through published validation pages.

Website ingestion is restricted to publicly reachable addresses and a bounded
crawl. UseCaseify does not claim to use social media firehoses, private
databases, or real-time market feeds.

## Process

1. **Product understanding.** A versioned product profile is drafted from the
   inputs. The user reviews, edits, and confirms it; nothing downstream runs
   against an unconfirmed profile.
2. **Research.** A research plan looks for both supporting and contradicting
   material. Findings are stored as verbatim quotes with sources and
   classified as supporting, contradicting, neutral, or context, with
   duplicates removed.
3. **Opportunity discovery.** Candidate use case opportunities are generated,
   structurally validated, red-team reviewed, and merged, leaving four cards
   for human review. The user approves or rejects each; one AI revision per
   card is possible based on the user's written feedback.
4. **Scoring.** Each opportunity is scored on ten dimensions, each reasoned
   independently, then combined by a deterministic weighted formula.
   Confidence and evidence level are computed separately from the score.
5. **Assets and pre-check.** For a selected opportunity, nine GTM test asset
   types are generated and checked for unsupported claims. An optional AI
   pre-check applies five synthetic reviewer perspectives, labeled as
   non-customer feedback.
6. **Prospect validation.** The user publishes a validation page (1–8
   questions, public or password-protected) and shares it with real people.
7. **Learning.** Responses are summarized and clustered into insights,
   producing score-change suggestions and an updated recommendation. Changes
   apply only when the user accepts them; accepted changes retain their
   provenance.
8. **Decision report.** The outcome — recommendation, main uncertainties, and
   next tests — is locked into an immutable, shareable report.

## How sources are used

Every research finding keeps its source and original wording. Evidence that
contradicts a use case is collected deliberately, not filtered out. Evidence
is bound to the exact product-profile version it was gathered for: when the
product inputs change, stale downstream conclusions are invalidated rather
than silently reused.

## How hypotheses and facts are separated

UseCaseify keeps four kinds of statements distinct:

- **Source facts** — quotes from public web sources, with citations.
- **AI inference** — generated scenarios, opportunity descriptions, and
  scores. These are hypotheses, however plausible they read.
- **Synthetic feedback** — AI pre-check output, always labeled as coming from
  synthetic reviewers rather than customers.
- **Real feedback** — responses from actual prospects via validation pages.
  Only this category counts toward the evidence levels "prospect feedback"
  and "behavioral signal".

The recorded evidence levels are: insufficient, single signal, repeated
signal, prospect feedback, and behavioral signal. Confidence (low, medium,
high) is reported alongside — not inside — the score, so a high-scoring
opportunity with thin evidence remains visibly unproven.

## Quality control

Quality controls that exist in the current product:

- structural validation of every generated candidate against a fixed schema;
- red-team review of candidates before they reach the user;
- unsupported-claim checks on GTM assets, bound to the current opportunity
  content;
- deterministic score aggregation — the weighted total is arithmetic, not a
  model's opinion;
- invalidation rules: editing the product context, evidence, or an
  opportunity invalidates dependent scores, claim checks, and recommendations
  so stale conclusions cannot be confirmed or published;
- withholding behavior: when no candidate reaches sufficient confidence and
  evidence, the system declines to name a primary recommendation.

## Human judgment

The user, not the system, confirms the product profile, keeps or rejects
each opportunity, overrides scores, accepts or declines score-change
suggestions, and decides what to publish. UseCaseify structures the decision;
it does not make it.

## Limitations

- Public web evidence shows that a problem is discussed, not that anyone
  will pay to solve it; the methodology treats it as a weak signal by design.
- Synthetic pre-checks can surface objections but cannot substitute for real
  customer conversations.
- Small validation samples support directional judgments, not statistical
  significance.
- Scores depend on the quality of the product information provided and on
  what public evidence exists; sparse markets yield honest but thin results.

## Future methodology

Behavioral validation (measuring real clicks and sign-ups on test pages) is
planned but not currently available. Until it ships, the highest evidence
level reachable in practice comes from prospect feedback collected through
validation pages.
