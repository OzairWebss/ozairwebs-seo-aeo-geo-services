# Reusable audit finding register

The accompanying CSV is an original blank planning template. Copy it into a private project workspace and add authorised findings. It contains no client data and does not perform a crawl or change a site.

Use one row for a confirmed finding, with the affected template and sample URL. Record the expected response and observed evidence separately. A hypothesis should explain a plausible mechanism, while the verification field states what would demonstrate the repair. Assign an owner and a review date so the record can survive handover.

For example, a category filter might generate empty pages that return 200. Record the exact sampled states, expected removal or valid empty-state behaviour, the decision about discoverability and the deployment retest. Do not mark the issue fixed merely because a ticket was closed.

Keep sensitive exports and authenticated URLs out of the public repository. The template's value is its evidence structure; populated rows must follow the site's data policy. See [audit workflow](../docs/seo-audit-workflow.md).
