---
layout: page
title: "End-to-End Example: From Product Input to Decision Report"
description: "A fictional AI meeting-minutes tool walked through the complete UseCaseify workflow: evidence, opportunity scoring, GTM assets, prospect validation, and the decision report."
permalink: /en/examples/end-to-end-example/
---

# End-to-End Example: From Product Input to Decision Report

> **Illustrative example.** "NotesAI" is a fictional product invented to
> explain the UseCaseify workflow. Every quote, number, and response below is
> fictional. This is not a customer case study, and the fictional prospect
> answers are not real market data.

## 1. Product input

The team behind NotesAI — a fictional AI meeting-minutes tool for Japanese
businesses (transcription, structured minutes, action items; around
¥1,500/user/month) — enters the product URL and a short description. They
have a working product and zero customer case studies.

## 2. Product profile

UseCaseify drafts a versioned product profile: category, core problem,
capabilities, target hints, and open questions. The team corrects one field —
the draft assumed on-premise deployment was available; it is not — and
confirms the profile. Nothing downstream runs against an unconfirmed profile.

## 3. Research questions

The research plan asks, among others: Who complains publicly about writing
minutes? Do teams already pay for alternatives? Where does resistance to
recording meetings appear?

## 4. Evidence collected

### Supporting evidence

- Posts by sales managers about spending evenings writing call summaries and
  follow-ups (repeated signal across several forums).
- Job postings assigning minutes duty to junior staff — evidence that
  companies already pay for this work with salaried time.
- Comparison articles about paid transcription tools, showing an existing
  paid category.

### Contradicting evidence

- Multiple threads arguing that bundled AI features in existing office
  suites are "good enough" for internal meetings.
- IT administrators expressing concern about recording customer-facing
  calls at all.

### Unknowns

- Willingness to pay among licensed professionals (tax accountants, labor
  consultants) — no usable public signal found.

## 5. Opportunity candidates

The system generates ten candidates, merges duplicates, and red-team review
removes weak ones. Four opportunity cards reach human review:

- **A. Sales-call minutes with same-day follow-up** for B2B sales teams
- **B. Client-meeting records for licensed professionals**
- **C. Council and committee minutes for local government**
- **D. Internal recurring-meeting minutes rolled out by IT**

## 6. Opportunity scoring

Each card is scored on ten dimensions and summed deterministically
(fictional values):

| Card | Total | Confidence | Evidence level |
|---|---|---|---|
| A. Sales follow-up | 72 | medium | repeated signal |
| B. Professionals | 68 | low | single signal |
| C. Government | 55 | low | insufficient |
| D. Internal meetings | 61 | medium | repeated signal |

The team rejects C outright (no channel into government sales). B scores
well but its confidence is low — the "unknown willingness to pay" from step 4
is visible instead of hidden inside the score.

## 7. Selected opportunity

The system names **A** the primary recommendation (highest score at medium
confidence, no unresolved contradiction) and states the reasons and the main
counter-argument: recording resistance on customer calls.

## 8. GTM test assets

For A, nine asset types are generated with unsupported-claim checks. Three
examples (fictional):

- **Value proposition:** "Send the follow-up while the deal is still warm —
  minutes and action items ready before you're back at your desk."
- **Headline:** 「商談が終わった瞬間、議事録とフォローメールの下書きまで。」
- **Cold outreach opening:** a two-sentence email referencing the evening
  hours sales managers spend on call summaries.

The claim check flags one draft sentence — "trusted by sales teams across
Japan" — as unsupported (no customers yet) and it is removed.

## 9. Validation questions

The team publishes a five-question validation page (password-protected) and
shares it with sales managers in their network: relevance of the problem,
current handling, most valuable outcome, biggest concern, willingness to see
a demo.

## 10. Prospect feedback

Eleven fictional responses come back. The pain is confirmed, but the resonant
outcome is not "minutes written faster" — it is **"the follow-up email goes
out the same day."** Two respondents name recording resistance as a blocker;
several report the current alternative is "a junior colleague does it."

## 11. Learning update

The analysis clusters the responses and proposes score changes: urgency up,
evidence quality up (evidence level rises to *prospect feedback*), and the
recording concern is filed as contradicting evidence. The suggestions apply
only when the team accepts them — they accept all three.

## 12. Recommendation change

The primary opportunity remains A, but the recommended value proposition
pivots from "write minutes faster" to "same-day follow-up," and the next
test is cold outreach using the new hook. B stays queued for a later cycle.
This is the loop working as intended: real feedback changed the message
before any ad budget was spent.

## 13. Decision report

The team locks the decision into an immutable report: the chosen
opportunity, the pivoted value proposition, the evidence for and against,
the accepted score changes with provenance, and the next tests — shareable
with advisors through a revocable link.

## 14. What remains uncertain

Recording resistance in regulated industries, actual willingness to pay
(feedback is interest, not purchase), and channel economics. The report says
so explicitly. A decision made on eleven responses is directional — the
point is that it is *traceable*, and the next test is already defined.

---

*Try UseCaseify at [usecaseify.com](https://usecaseify.com/) — 2 credits on sign-up, no credit card required.*

## Related documentation

- [Product facts]({{ site.baseurl }}/en/product-facts/)
- [Methodology]({{ site.baseurl }}/en/methodology/)
- [Use case scoring framework]({{ site.baseurl }}/en/guides/use-case-scoring-framework/)
- [How to validate a use case]({{ site.baseurl }}/en/guides/how-to-validate-a-use-case/)
