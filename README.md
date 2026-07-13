# UseCaseify

> Find the use cases your market will actually respond to — before you have customer case studies.

**UseCaseify** ([usecaseify.com](https://usecaseify.com/)) is a use case discovery and validation platform that helps product teams decide which use case, audience, and value proposition to take to market — backed by traceable market evidence and feedback from real prospects instead of guesswork. It analyzes a product from its website, files, or a written description, gathers cited evidence from public web sources, generates and scores use case opportunities, produces the go-to-market assets needed to test them, and collects structured feedback from real prospects. The output is not a pile of ideas: it is a supported recommendation, a clearly labeled priority validation candidate when evidence is still early, or an explicit indication that no candidate passes the guardrails yet.

UseCaseify（ユースケーシファイ）は、出典をたどれる市場エビデンスと実在の見込み顧客からのフィードバックをもとに、「誰に・どのユースケースを・どんな価値提案で」市場に出すかを決められる、ユースケース発見・検証プラットフォームです。製品情報の分析からエビデンス収集、機会のスコアリング、検証用 GTM 素材の作成、見込み顧客からのフィードバック収集までを一つのワークフローにまとめ、勘に頼らない GTM の意思決定を支援します。

**Try it:** [usecaseify.com](https://usecaseify.com/) — 2 credits on sign-up, no credit card required.

## What problem does UseCaseify address?

Early-stage products face a messaging-before-evidence paradox: a team needs a clear value proposition and concrete use cases to win its first customers, but it needs customer feedback to know which value proposition and use cases are right. Before product-market fit, teams typically have no real case studies, no structured interviews, and no verified buying reasons — yet they still have to write the landing page, the outreach email, and the sales pitch.

Generating use case *ideas* was never the hard part; a general-purpose AI chat can produce a dozen in seconds. The hard part is deciding which one deserves the team's limited budget: whether the pain is frequent and severe, whether buyers already pay for alternatives, whether the audience is reachable, and whether the idea can be tested cheaply. Discussion threads and search results show that a problem is *talked about*; they do not show that anyone will pay to solve it.

In practice this decision work is scattered across search engines, note-taking tools, AI chats, survey tools, and page builders, with no shared data structure connecting the evidence found, the scenarios written, and the feedback received. UseCaseify addresses this specific stage of go-to-market work: after a product exists, but before there is enough customer evidence to know where to aim it.

## What does the current product do?

All of the following is live in the current product. Specific counts and limits
(cards, dimensions, asset types, question ranges) describe the **current beta
implementation** — last reviewed 2026-07-13 — and may be tuned during beta; the
workflow itself is the stable part.

- **Product understanding** — Build a product profile from a website URL (bounded crawl of public pages), uploaded files, or manual text. The profile is versioned, and you review, edit, and confirm it before anything downstream runs.
- **Market research and evidence** — Multilingual web research collects verbatim quotes with their sources, classified as supporting, contradicting, neutral, or context. You can add your own evidence and filter the evidence workspace.
- **Opportunity discovery** — The system generates use case opportunity candidates, screens them through structural validation and red-team review, and presents four opportunity cards. You approve or reject each card, and each card can be revised once by AI based on your written feedback.
- **Opportunity scoring and recommendation** — Ten dimensions (pain frequency, pain severity, urgency, existing spend, product fit, reachability, differentiation, evidence quality, testability, strategic fit) are reasoned independently and combined into a deterministic weighted total. Confidence (low / medium / high) is tracked separately from the evidence level. You can override scores manually. A candidate that clears the recommendation rules is shown as supported; when none does, a candidate that passes the validation-priority guardrails may be shown as an early hypothesis to test. If none passes, no recommendation is named.
- **GTM test assets** — Nine asset types per opportunity: value proposition, headline, supporting benefits, landing page section, cold outreach message, interview guide, survey, call to action, and objection responses. Assets are versioned, editable, regenerable, and checked for claims not supported by the underlying opportunity.
- **AI pre-check** — Five synthetic reviewer perspectives critique the selected opportunity and its assets. Results are explicitly labeled as synthetic, non-customer feedback, and objections can be converted into validation questions.
- **Prospect validation** — Publish a public or password-protected validation page with 1–8 questions. Respondents answer anonymously without an account, with explicit consent handling; leaving contact details is optional.
- **Learning and decision reports** — Real responses are summarized and clustered into insights, producing score-change suggestions that take effect only when you explicitly accept them, plus an updated recommendation. Decisions can be locked into an immutable report and shared through a revocable public or password-protected link.

The product interface is available in Japanese, Chinese, and English. The primary market is Japan.

## Who is it for?

- **Early-stage B2B SaaS and AI product founders** who have a working product but no stable product-market fit, few customers, and no formal case studies.
- **Product marketing and GTM leads** who must choose value propositions for different personas, industries, or channels before committing to large-scale production and campaigns.
- **Agencies and consultants** who need to understand an unfamiliar industry quickly and give clients an evidence-backed, explainable market-entry recommendation.

UseCaseify is not aimed at large enterprises with mature customer-research teams, content teams that only need bulk marketing copy, or product managers looking for software-engineering (UML-style) use case diagrams.

## How does it work?

1. Enter your product's URL, upload files, or describe the product in text; review and confirm the product profile UseCaseify builds from it.
2. UseCaseify researches public web sources and records verbatim evidence with citations, separated into supporting, contradicting, neutral, and context.
3. It generates use case opportunity candidates, filters them through red-team review, and presents four cards for your judgment.
4. You approve or reject each card. Every card carries a ten-dimension score and a confidence rating. The decision layer names either a supported recommendation, a clearly labeled priority validation candidate, or no candidate when the guardrails are not met.
5. For the opportunity you choose, UseCaseify generates the nine GTM test assets, with unsupported-claim checks.
6. Optionally run the synthetic AI pre-check, then publish a validation page and share it with real prospects.
7. Prospect responses produce score-change suggestions and an updated recommendation; you accept or decline them, then lock the decision into a shareable report.

## Product principles

- **Traceable evidence.** Research findings keep their source and original wording, and are explicitly separated into supporting, contradicting, neutral, and context.
- **Facts, inference, and feedback are never mixed.** AI-generated scenarios are hypotheses; the AI pre-check is labeled synthetic; only real prospect responses count as validation signals.
- **Confidence is separate from the score.** A high score with weak evidence is shown as exactly that. A priority validation candidate is labeled as an early hypothesis, never validated demand; if its guardrails are not met, the system withholds the recommendation.
- **Humans make the final call.** The product profile, opportunity shortlist, score overrides, and score-change suggestions all require explicit user confirmation.

See [Methodology](https://llmjp.github.io/usecaseify/en/methodology/) for details.

## Current product and future direction

**Current (live, beta):** everything listed under "What does the current product do?" above, at [usecaseify.com](https://usecaseify.com/).

**Planned or deferred (not currently available, no committed dates):** behavioral testing with landing-page experiments, validating multiple opportunities in parallel, team collaboration, report PDF export, custom branding on validation pages, continuous market monitoring, cross-project learning, and CRM/advertising integrations.

Planned items describe direction, not commitments; they may change or be dropped based on validation results.

## What UseCaseify is not

- UseCaseify does **not** manufacture customer case studies. Generated use
  cases are hypotheses or illustrative scenarios grounded in market evidence,
  and are labeled as such.
- UseCaseify does **not** treat synthetic (AI) feedback as real customer
  validation. Only responses from real prospects count as validation signals.
- UseCaseify does **not** guarantee product-market fit, conversion rates, or
  any business outcome. Scores and recommendations are decision support.
- UseCaseify is **not** a general-purpose copywriting suite, an ad platform,
  or a website builder, and it does not replace talking to customers.

## Public resources

- [Documentation home](https://llmjp.github.io/usecaseify/) — English and Japanese
- [Product facts (EN)](https://llmjp.github.io/usecaseify/en/product-facts/) / [プロダクトファクト (JA)](https://llmjp.github.io/usecaseify/ja/product-facts/)
- [Methodology (EN)](https://llmjp.github.io/usecaseify/en/methodology/) / [方法論 (JA)](https://llmjp.github.io/usecaseify/ja/methodology/)
- [FAQ (EN)](https://llmjp.github.io/usecaseify/en/faq/) / [よくある質問 (JA)](https://llmjp.github.io/usecaseify/ja/faq/)
- [Glossary (EN)](https://llmjp.github.io/usecaseify/en/glossary/) / [用語集 (JA)](https://llmjp.github.io/usecaseify/ja/glossary/)
- [Whitepaper (EN)](https://llmjp.github.io/usecaseify/en/whitepaper/) / [ホワイトペーパー (JA)](https://llmjp.github.io/usecaseify/ja/whitepaper/)
- [End-to-end example (EN)](https://llmjp.github.io/usecaseify/en/examples/end-to-end-example/) / [エンドツーエンド例 (JA)](https://llmjp.github.io/usecaseify/ja/examples/end-to-end-example/) — a fictional product walked through the whole workflow
- [How to validate a use case (EN)](https://llmjp.github.io/usecaseify/en/guides/how-to-validate-a-use-case/) / [ユースケース検証ガイド (JA)](https://llmjp.github.io/usecaseify/ja/guides/how-to-validate-a-use-case/)
- [Use case scoring framework (EN)](https://llmjp.github.io/usecaseify/en/guides/use-case-scoring-framework/) / [スコアリングフレームワーク (JA)](https://llmjp.github.io/usecaseify/ja/guides/use-case-scoring-framework/)
- [UseCaseify vs ChatGPT (EN)](https://llmjp.github.io/usecaseify/en/comparisons/usecaseify-vs-chatgpt/) / [UseCaseify と ChatGPT の違い (JA)](https://llmjp.github.io/usecaseify/ja/comparisons/usecaseify-vs-chatgpt/)
- [AI limitations (EN)](https://llmjp.github.io/usecaseify/en/ai-limitations/) / [AI の限界 (JA)](https://llmjp.github.io/usecaseify/ja/ai-limitations/)
- [Privacy and data overview (EN)](https://llmjp.github.io/usecaseify/en/privacy-and-data/) / [プライバシーとデータの扱い (JA)](https://llmjp.github.io/usecaseify/ja/privacy-and-data/)
- [llms.txt](https://llmjp.github.io/usecaseify/llms.txt) — machine-readable summary for AI systems

## Official links

- Product: [https://usecaseify.com/](https://usecaseify.com/)
- FAQ: [https://usecaseify.com/faq](https://usecaseify.com/faq)
- Terms: [https://usecaseify.com/terms](https://usecaseify.com/terms) / Privacy: [https://usecaseify.com/privacy](https://usecaseify.com/privacy)
- Legal disclosure (特定商取引法に基づく表記): [https://usecaseify.com/tokushoho](https://usecaseify.com/tokushoho)
- Operator: LLM JAPAN, LLC（ＬＬＭ ＪＡＰＡＮ合同会社）, Tokyo, Japan
- Contact: [support@usecaseify.com](mailto:support@usecaseify.com)

## Repository scope

This repository contains the official public documentation for UseCaseify: product facts, methodology, FAQ, glossary, and whitepaper. It does **not** contain the product's source code, and UseCaseify is not an open-source project. The official product entry point is [usecaseify.com](https://usecaseify.com/); this repository exists so that users, media, and AI systems have a stable, verifiable reference for what UseCaseify currently is and is not.

Code contributions are not applicable here. Factual corrections, broken-link reports, and translation fixes are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Citation

To cite UseCaseify or this documentation, use the metadata in [CITATION.cff](CITATION.cff). Publisher: LLM JAPAN, LLC.

## Last reviewed

2026-07-13, against the deployed product at [usecaseify.com](https://usecaseify.com/).
For conflicts between documents, [Product facts](https://llmjp.github.io/usecaseify/en/product-facts/) is the current source of truth.
