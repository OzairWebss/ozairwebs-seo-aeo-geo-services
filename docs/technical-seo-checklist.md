# Technical SEO acceptance checklist

Use this checklist against an authorised site and a recorded release. Sample each meaningful template and priority journey; a homepage-only pass leaves catalogues, language pages and errors untested. Record the URL, expected behaviour, observed evidence, owner and retest date. A checkbox represents a completed check, not an inferred ranking benefit.

## Inventory and discovery

- [ ] Identify the preferred host, HTTPS policy and public URL surface.
- [ ] Export the content inventory, sitemap URLs and a crawl of linked pages.
- [ ] Compare the three sets; investigate orphan and unexpectedly missing pages.
- [ ] Sample category pagination and filters with and without results.
- [ ] Confirm meaningful navigation uses links with valid destinations.
- [ ] Document which facets provide distinct useful landing pages.

## HTTP and index controls

- [ ] Important live pages return the intended successful status.
- [ ] Retired pages redirect to a relevant equivalent or return an appropriate removal status.
- [ ] Redirect chains and loops are absent on priority paths.
- [ ] Error templates do not return successful responses for missing content.
- [ ] Robots rules permit resources required to render intended public pages.
- [ ] Intentional noindex instructions are visible to a permitted crawler.
- [ ] Authentication protects private content; robots rules are not the protection.
- [ ] Sitemap entries are preferred, indexable URLs with meaningful modification dates.
- [ ] Canonicals agree with navigation, redirects and sitemap choices.

## Templates, languages and media

- [ ] Compare server HTML and browser-rendered content on representative templates.
- [ ] Titles and headings describe the actual page, including empty-state behaviour.
- [ ] Language alternatives have valid reciprocal hreflang annotations where used.
- [ ] Mobile output retains meaningful content and navigation.
- [ ] Product identity, visible availability and structured data agree.
- [ ] Image dimensions and alternative text match their purpose.
- [ ] Video pages provide accessible context and relevant transcripts or descriptions.

## Operations and acceptance

- [ ] Check LCP, INP and CLS from available field data, with lab reproduction of failures.
- [ ] Review CDN and application caches for stale or personalised content leakage.
- [ ] Verify crawler identity before interpreting bot logs; retain logs appropriately.
- [ ] Test enquiry or purchase steps independently of analytics scripts.
- [ ] Preserve a migration redirect map and a recoverable release boundary.
- [ ] Attach before/after evidence to each closed issue and document unresolved dependencies.

Prioritise confirmed failures on valuable templates before minor audit warnings. A sitemap fetch, valid canonical or passing lab test does not demonstrate that a page is indexed. See [audit workflow](seo-audit-workflow.md) and [primary references](references.md).
