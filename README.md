# Lattice Engines

Lattice Engines was a predictive marketing and AI-driven B2B customer data platform that
scored accounts and leads from CRM, marketing automation, firmographic, technographic, and
intent data to prioritize sales outreach and power account-based marketing.

**Status: acquired.** Dun & Bradstreet acquired Lattice Engines in 2019. The product was
rebranded D&B Lattice and later folded into the Dun & Bradstreet Rev.Up ABX platform.

- Successor product: https://www.dnb.com/en-us/products/dnb-rev-up-abx.html
- Successor profile: https://github.com/api-evangelist/dun-and-bradstreet

## Developer surface

None. Enrichment probes on 2026-07-19 found no public API, documentation, or discovery
surface under this brand:

| Host | Result |
|---|---|
| `www.lattice-engines.com` | 301 → dnb.com |
| `lattice-engines.com` | 403 |
| `api.lattice-engines.com` | 404 |
| `developer.lattice-engines.com` | DNS does not resolve |
| `docs.lattice-engines.com` | DNS does not resolve |

## Artifacts

- `security/lattice-engines-domain-security.yml` — probed TLS/DNS posture
- `well-known/lattice-engines-well-known.yml` — probed `/.well-known/` surface (empty)
- `llms/lattice-engines-llms.txt` — generated agent-facing summary

Backed by: battery-ventures
