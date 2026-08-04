# Ritual (ritual-ordering)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
