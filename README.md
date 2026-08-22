# ExchangeRate-API

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

ExchangeRate-API is a currency exchange rate REST API providing real-time and historical exchange rates for 165 currencies across 200 countries. Operating since 2010, the service delivers reliable currency conversion data via simple HTTP GET requests with over 99.99% measured uptime.

**Base URL:** `https://v6.exchangerate-api.com/v6/`

**Open Access (no key):** `https://open.er-api.com/v6/latest/{CURRENCY}`

## Key Features

- 165 supported currencies across 200 countries
- Real-time and historical exchange rates (data back to 1990)
- Two authentication methods: URL-embedded key or Bearer token header
- Free tier with 1,500 requests/month and daily updates
- Paid plans with hourly or 5-minute update frequencies
- Multi-AZ AWS infrastructure with Cloudflare CDN
- No-key Open Access endpoint for low-volume and development use

## Plans

| Plan | Price | Requests/Month | Update Frequency |
|------|-------|----------------|------------------|
| Free | $0/mo | 1,500 | Daily |
| Pro | $10/mo | 30,000 | Every 60 min |
| Business | $30/mo | 125,000 | Every 5 min |
| Volume | Custom | Custom | Custom |

## Links

- **Website:** https://www.exchangerate-api.com
- **Documentation:** https://www.exchangerate-api.com/docs/overview
- **Pricing:** https://www.exchangerate-api.com/#pricing
- **Status Page:** https://stats.pingdom.com/qv69spvrz94m/8069768
- **Sign Up:** https://app.exchangerate-api.com/sign-up
- **Support:** support@exchangerate-api.com

## Repository Contents

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/exchangerate-plans-pricing.yml` — Detailed plan and pricing information
- `rate-limits/exchangerate-rate-limits.yml` — Rate limiting policies by plan tier
- `finops/exchangerate-finops.yml` — Financial operations and cost optimization guidance
