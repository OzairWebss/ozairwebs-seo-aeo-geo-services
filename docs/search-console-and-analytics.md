# Measurement design for search and business outcomes

This is an educational reporting guide. Reading this document does not authorise changes to any Search Console property. Repository discovery, a company's website and a GitHub Pages site are different surfaces, with different ownership and reporting boundaries.

## Choose measurements before changing pages

Define the intended outcome and denominator. For a consultancy, a qualified organic enquiry can be more useful than aggregate sessions. For a store, distinguish a placed order, a verified payment and net revenue after refunds. An event firing successfully is not proof of a business result.

Search Console records selected search-performance data such as clicks, impressions, CTR and average position. Query-level tables can omit anonymised queries, and different aggregation choices produce different totals. GA4 records site/app interactions subject to consent, identity and attribution settings. Do not expect the two products to report identical counts. Explain measurement gaps rather than hiding them.

## API and dashboard boundaries

The [Search Console API](https://developers.google.com/webmaster-tools/v1/api_reference_index) includes Search Analytics, sitemap management, properties and index inspection. URL Inspection API reports indexed-state information; it is not a general API for requesting indexing of arbitrary pages. Use least-privilege access, respect quotas and keep property identifiers explicit.

The [GA4 Data API](https://developers.google.com/analytics/devguides/reporting/data/v1) supports permitted reporting. Use agreed event definitions and compatible dimensions. Keep credentials outside public notebooks and minimise retained exports. Dashboards should state dates, filters, attribution assumptions and whether data is settled or incomplete.

## A useful monthly record

| Area | Evidence to report | Interpretation limit |
| --- | --- | --- |
| Discovery | Clicks, impressions and query groups | Demand and result formats can change |
| Engagement | Consent-aware journeys and conversion rate | Missing consent can reduce observable coverage |
| Business | Qualified leads or validated orders | Requires consistent operational classification |
| Technical | Verified issue closures and field performance | A tool score is not a ranking outcome |
| AI discovery | Saved mentions and cited sources | No equivalent cross-provider metric |

Compare meaningful periods and annotate launches, campaigns and tracking changes. Assisted conversions depend on the chosen attribution model; state that model instead of presenting assistance as an unambiguous causal claim. Report unresolved issues and regressions alongside improvements.

Use n8n, Make, Zapier or a scheduled Python/Node.js job only when authorised access and data policies are clear. Model-assisted summaries should reference the actual numbers and filters, with human review before sharing. See [AI visibility observations](ai-search-visibility.md) for a separate provider sampling record.
