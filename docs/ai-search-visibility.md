# AI search visibility: access, evidence and observation

AI discovery work should begin with ownership decisions and readable public information. This guide does not define an invented AI ranking formula. Google, OpenAI and other providers operate different systems; conclusions about one provider cannot establish how another selects sources.

## Separate access policies

Google's [AI feature guidance](https://developers.google.com/search/docs/appearance/ai-features) says familiar search requirements remain relevant and no special AI schema is needed. The public page still needs useful content and consistent search controls. Eligibility is not a citation guarantee.

OpenAI's [crawler reference](https://platform.openai.com/docs/bots) distinguishes OAI-SearchBot from GPTBot. The former supports search discovery, while the latter relates to possible training use. Decide search and training preferences separately. ChatGPT-User describes user-initiated visits and is not the automatic search crawler. Check provider guidance before changing rules; do not assume every user-initiated fetch observes the same robots controls.

Keep a provider register: purpose, documented user agent, published verification mechanism, owner-approved rule and date checked. WAF allowlists should use appropriate verification rather than a user-agent string alone. Protect private records with authentication and explicit permissions. Adding a public README cannot override GitHub's own crawler controls.

## Make information useful to quote

Write self-contained explanations that name the subject, answer a concrete question and state material limits. Link the evidence supporting a factual claim. Keep original tables and explanations in text rather than only in an image. Transparent company identity and real portfolio references help readers assess a source; they are not substitutes for independent evidence.

llms.txt can serve as an optional curated index, but Google does not require it as a ranking mechanism. Machine-readable product information should agree with visible prices, stock and descriptions. Semantic HTML, labelled controls and predictable navigation also help accessible browsing and agent-assisted research without granting authority to execute transactions.

## Record observations consistently

Use a fixed prompt set covering genuine buyer questions. For each observation record the provider, date, locale, account context, exact prompt, answer, linked sources and whether the mention accurately represents the business. Compare repeated samples rather than treating a single answer as a stable rank.

Separate brand mentions, direct citations and citations to another source that mentions the business. Preserve inspectable answer evidence where permitted. Search Console and provider referral traffic may capture selected visits, but they do not measure every zero-click answer. Different providers expose different reporting. Note unavailable measurements explicitly rather than replacing them with invented scores.

Changes should have a recorded hypothesis, affected URLs and review date. A measurable observation can guide the next revision; it cannot establish exclusive causation. See [measurement guidance](search-console-and-analytics.md).
