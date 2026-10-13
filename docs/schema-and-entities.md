# Structured data and business entities

Structured data describes information that a page actually presents. Start by identifying the subject and its owner, then decide which vocabulary is appropriate. Schema.org defines types and properties; Google's supported feature documentation defines eligibility for Google enhancements. These are related but different questions.

## A defensible modelling sequence

1. Inventory the page's visible facts and authoritative data source.
2. Identify the primary entity: an organisation, article, product or another supported subject.
3. Choose stable identifiers and relationships across templates.
4. Generate markup from the same data used by the page.
5. Validate syntax and type usage, then test eligibility for any intended search feature.
6. Monitor mismatches after edits and data synchronisation.

For organisation information, reconcile the name, website, contact information and verified public profiles. Do not claim affiliations through sameAs links to unrelated businesses. Brand aliases can be explained without inventing separate companies. Qualification and review claims need evidence, not a more elaborate vocabulary.

## Commerce needs live data agreement

Product variants, offers, availability and currency should correspond to the customer-visible catalogue. A product feed generated yesterday and a page updated today may diverge. Put an owner and reconciliation process around updates. Discontinued products need deliberate page and feed behaviour rather than a permanent unavailable offer copied across every template.

Reviews must describe genuine visible evidence and follow the intended feature's policies. Do not create AggregateRating values from agency claims, unpublished customer statements or illustrative examples. FAQ content can be useful even when a site is not eligible for Google's restricted FAQ rich-result treatment; usefulness and visual enhancement are separate outcomes.

## Validation and release review

Test a representative entity, variant and empty state. Parse the JSON, compare its facts to the page and inspect relevant validation tools. A passing syntax test does not prove the underlying claims. Include regression checks for removed fields, stock transitions, URL changes and multilingual output.

This Markdown repository does not inject JSON-LD into its README, and GitHub does not provide a repository author with arbitrary control over the page's search markup. Example planning fields are available in [the evidence register](../examples/README.md). Start with [Google's structured-data introduction](https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data) and the [references](references.md) before implementing a specific feature.
