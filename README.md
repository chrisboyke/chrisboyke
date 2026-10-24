## Chris Boyke

Principal Solution Engineer at [commercetools](https://commercetools.com), and the
technical lead on our side of enterprise commerce evaluations. I work with manufacturers,
distributors, healthcare and life sciences organizations, and retailers on architecture,
migration planning, business cases and proofs of concept — helping them decide whether
composable commerce is right for them, and what it would take to get there.

When something I build generalises beyond one customer, I publish it to
[**ct-builders**](https://github.com/ct-builders) as an MIT-licensed reference
implementation: unsupported, readable, and meant to be taken apart.

### Reference implementations

**[auto-categorization](https://github.com/ct-builders/auto-categorization)** —
Rule-driven category membership for commercetools. A merchandiser writes a rule; the
products that match belong in the category, now and as the catalog changes. Product API
Extension, a resumable catalog sweep, two Merchant Center surfaces.

**[abandoned-carts](https://github.com/ct-builders/abandoned-carts)** —
Abandoned cart recovery as a Connect connector: carts gone quiet, a scheduled job, an
email sender, order-conversion tracking, and a Merchant Center app for rules and queue.

**[ct-release-manager](https://github.com/ct-builders/ct-release-manager)** —
Catalog release management. Edit products, categories and discounts inside a named
release, deploy the bundle to production in one step, roll it back in one.

**[ct-project-clone](https://github.com/ct-builders/ct-project-clone)** —
Clone data and settings between commercetools projects, in any region. Key-based,
idempotent and resumable, with count, field-diff and live smoke verification. A
dependency-free Node CLI.

**[discount-deploy-mc-app](https://github.com/ct-builders/discount-deploy-mc-app)** —
Promote discounts from staging to production with a diff, dependency expansion, and an
audit that rewrites ids embedded in predicates to the target project.

**[customer-service-mc-app](https://github.com/ct-builders/customer-service-mc-app)** —
A CSR workspace in the Merchant Center: customer 360, orders, returns and refunds,
assisted ordering, lists and cases.

**[ct-analytics](https://github.com/ct-builders/ct-analytics)** —
Shopper journey analytics for ecommerce sites. One script tag, a Postgres collector, a
reporting admin.

### What I think about

Agentic engineering applied to technical pre-sales — using AI coding tools to build a
customer-specific demo in a couple of hours, and building the starters, tooling and
instrumentation that let a field team do the same. Most of the leverage turns out to
be in the scaffolding, not the demo.

Happy to compare notes on composable or agentic commerce, B2B self-service buying, or
replatforming off a legacy monolith.
