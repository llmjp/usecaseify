---
layout: page
title: "UseCaseify Product Facts"
description: "Verifiable facts about UseCaseify: current definition, capabilities, limitations, status, pricing model, operator, and what the product does not claim."
permalink: /en/product-facts/
---

# UseCaseify Product Facts

This page states only verifiable facts about UseCaseify as currently deployed.
It is the reference other UseCaseify documents are kept consistent with.

## Identity

- **Product name:** UseCaseify
- **Official URL:** [https://usecaseify.com/](https://usecaseify.com/)
- **Operator:** LLM JAPAN, LLC（ＬＬＭ ＪＡＰＡＮ合同会社）, Tokyo, Japan —
  identified on the product's [legal disclosure page](https://usecaseify.com/tokushoho)
- **Interface languages:** Japanese, Chinese, English; primary market Japan
- **Status:** live, in beta
- **Contact:** [support@usecaseify.com](mailto:support@usecaseify.com)

## Current product definition

UseCaseify is a use case discovery and validation platform for product teams
that do not yet have enough customer case studies. It analyzes a product,
gathers traceable market evidence from public web sources, generates and scores
use case opportunities, produces the GTM assets needed to test them, and
collects structured feedback from real prospects, so teams can decide which use
case, audience, and value proposition to take to market.

Its category is **Use Case Discovery & Validation** — decision support for
go-to-market choices made before product-market fit.

## Current product status

UseCaseify is live at [usecaseify.com](https://usecaseify.com/) as a beta
service (as of July 2026). Pricing is credit-based: a monthly subscription
(¥9,800/month including tax, with monthly credits, as of July 2026) plus
pay-as-you-go credit top-ups (¥980 per credit), with a free trial credit on
sign-up that requires no credit card. Pricing is provisional during beta; the
authoritative current pricing is on the
[product site](https://usecaseify.com/) and its
[legal disclosure page](https://usecaseify.com/tokushoho).

## Intended users

- Early-stage B2B SaaS and AI product founders with a working product but
  no stable product-market fit and few or no formal case studies
- Product marketing and GTM leads choosing value propositions for different
  personas, industries, or channels
- Agencies and consultants who need evidence-backed, explainable market-entry
  recommendations for clients

## Current capabilities

Each item below is a shipped behavior of the current product:

- **Product understanding.** A product profile is built from a website URL
  (a bounded crawl of public pages), uploaded files, or manual text. The
  profile is versioned and must be reviewed and confirmed by the user before
  downstream steps run.
- **Research and evidence.** Multilingual web research collects verbatim
  quotes with sources, classified as supporting, contradicting, neutral, or
  context. Users can add their own evidence and filter the evidence workspace.
- **Opportunity discovery.** The system generates use case opportunity
  candidates, screens them through structural validation and red-team review,
  and presents exactly four opportunity cards. The user approves or rejects
  each card, and each card can be revised once by AI from the user's written
  feedback.
- **Scoring and recommendation.** Ten dimensions — pain frequency, pain
  severity, urgency, existing spend, product fit, reachability,
  differentiation, evidence quality, testability, strategic fit — are reasoned
  independently and combined into a deterministic weighted total. Confidence
  (low / medium / high) is tracked separately from the evidence level. Scores
  can be manually overridden, and a primary recommendation is withheld when
  evidence is insufficient.
- **GTM test assets.** Nine asset types per opportunity: value proposition,
  headline, supporting benefits, landing page section, cold outreach message,
  interview guide, survey, call to action, and objection responses. Assets are
  versioned and checked for claims not supported by the underlying
  opportunity.
- **AI pre-check.** Five synthetic reviewer perspectives critique the selected
  opportunity. Results are explicitly labeled as synthetic, non-customer
  feedback; objections can be converted into validation questions.
- **Prospect validation.** A public or password-protected validation page with
  1–8 questions can be published and shared. Respondents answer anonymously
  without an account, with explicit consent handling; contact details are
  optional.
- **Learning.** Real responses are summarized quantitatively and clustered
  into insights. Score-change suggestions take effect only when the user
  explicitly accepts them, and the recommendation is updated with provenance.
- **Decision reports.** Decisions can be locked into an immutable report and
  shared via a revocable public or password-protected link.

## Current limitations

- The AI pre-check is synthetic feedback, not real customer feedback, and is
  labeled as such in the product.
- Generated opportunities and scenarios are hypotheses or illustrative
  content until validated; they are not real customer case studies and must
  not be presented as such.
- Opportunity scores and recommendations are decision support, not
  predictions or guarantees of market success.
- When evidence is insufficient, the system withholds a primary
  recommendation rather than producing one.
- UseCaseify does not replace full customer research, and it is not an
  advertising platform, a website builder, or a general-purpose marketing
  content suite.
- The service is in beta; pricing and some behaviors are provisional.

## Planned or future direction

The following are **not currently available** and have no committed dates:

- Behavioral testing (landing-page experiments with click and conversion
  tracking) — *Planned*
- Validating multiple opportunities in parallel — *Planned*
- Team collaboration — *Planned*
- Report PDF export and custom branding on validation pages — *Planned*
- Continuous market monitoring and automatic competitor tracking — *Exploring*
- Cross-project learning and industry benchmarks — *Exploring*
- CRM and advertising integrations — *Exploring*

## Evidence and claim policy

UseCaseify distinguishes, throughout the product, between:

- **source facts** — verbatim quotes from public web sources, with citations;
- **AI inference** — generated hypotheses, scenarios, and scores;
- **synthetic feedback** — AI pre-check results, always labeled non-customer;
- **real prospect feedback** — responses from actual people via validation
  pages, the only input treated as a validation signal.

Recorded evidence levels are: insufficient, single signal, repeated signal,
prospect feedback, and behavioral signal. Confidence is reported separately
from scores so that a well-scored idea with weak evidence is visible as
exactly that.

## What the product does not claim

- It does not fabricate customers, testimonials, or results, and it does not
  present illustrative scenarios as real case studies.
- It does not guarantee product-market fit, conversions, or any business
  outcome.
- It does not claim that AI-generated evaluations equal real market
  validation.
- It does not claim market-share or ranking positions for itself.

## Official sources

- Product: [https://usecaseify.com/](https://usecaseify.com/)
- Product FAQ: [https://usecaseify.com/faq](https://usecaseify.com/faq)
- Terms: [https://usecaseify.com/terms](https://usecaseify.com/terms) ·
  Privacy: [https://usecaseify.com/privacy](https://usecaseify.com/privacy)
- Legal disclosure: [https://usecaseify.com/tokushoho](https://usecaseify.com/tokushoho)
- This documentation repository:
  [https://github.com/llmjp/usecaseify](https://github.com/llmjp/usecaseify)

## Last reviewed

2026-07-12, against the deployed product at usecaseify.com.
