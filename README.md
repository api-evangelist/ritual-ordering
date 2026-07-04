# Ritual (ritual-ordering)

Ritual is a Toronto-based restaurant order-ahead and "social ordering" platform ([ritual.co](https://ritual.co), founded 2014 by Ray Reddy, Larry Stinson, and Robert Kim). Consumers use the Ritual mobile app to pre-order, pay, and skip the line at local restaurants and coffee shops, and colleagues can pile onto a shared order for group pickup. For restaurants, Ritual offers Ritual ONE (online ordering), plus perk programs for companies and buildings and a Ritual for Coffee product.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ritual-ordering/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ritual-ordering/refs/heads/main/apis.yml)

## API Access Model

**Ritual does not publish a public or self-serve developer API.** This entry is an honest documentation stub. As of this review:

- There is **no developer portal, API reference, SDK, or authentication documentation** on ritual.co.
- The [API Tracker](https://apitracker.io/a/ritual-co) profile for Ritual is an empty placeholder with no endpoints, auth, or docs.
- Restaurant-side integration (getting Ritual orders into a point-of-sale system) is delivered through **partner/POS integrations** documented for operators at [partnersupport.ritual.co](https://partnersupport.ritual.co/hc/en-us/categories/360005652153-POS-Integrations) (e.g. Toast) and through **third-party ordering aggregators** such as [Deliverect](https://www.deliverect.com/en-us/integrations/ritual), which run a two-way integration between Ritual and the restaurant's POS.
- None of this exposes a Ritual-published, publicly consumable API. Access is via the consumer apps (iOS/Android/web) and partner-gated integrations arranged through Ritual's partnerships team.

Because no public API is documented, no `openapi/`, `plans/`, `rate-limits/`, `finops/`, or `collections/` artifacts are included, and no endpoints are modeled (`endpointsModeled: none`).

## Operating Status

**Operational but distressed and in transition.** Ritual continues to run its consumer order-ahead app and Ritual ONE online-ordering platform as of 2025, but the business has been in financial decline - revenue fell from ~US$11M (2021) to ~US$8.4M (2023) to ~US$3.9M (H1 2024), with dwindling cash and repeated layoffs (staff cut to under 50). In **January 2025, Shopify "acqui-hired"** the co-founders (CEO Ray Reddy joined Shopify as VP of Retail, working on Shopify POS) and much of the R&D team, while a **separate process to sell the standalone Ritual business** (with at least two interested buyers in due diligence) was underway. The long-term future of the standalone platform is uncertain.

## Pricing

- **Consumers:** the app is free to download and use.
- **Restaurants:** historically a flat **~US$49/month per location** for Ritual ONE; Ritual has repeatedly marketed its basic online-ordering tool as **commission-free / "free"** to restaurants (including a City of Toronto partnership providing a free ordering tool to local foodservice businesses). No current public pricing page is published - restaurant pricing is quoted through sales.

## Tags

- Restaurants
- Order Ahead
- Online Ordering
- Food Ordering
- Social Ordering
- Payments
- POS Integration
- No Public API

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## Common Properties

- [Website](https://ritual.co)
- [LinkedIn](https://ca.linkedin.com/company/ritual-co)
- [Documentation (Partner POS Integrations)](https://partnersupport.ritual.co/hc/en-us/categories/360005652153-POS-Integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
