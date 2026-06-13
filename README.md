# ExchangeRate-API

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
