# PestRate

A partner pricing app for PESTABLE subcontractors. It's one file (`index.html`) with no build step, made for phones.

## How a subcontractor uses it
**⚡ Quick price** (two taps):
1. Tap the pest. Each tile shows the lowest price, or says "PESTABLE quotes".
2. For general pests only, tap the property type.

The result shows **Charge customer** and **You earn** side by side for **Standard** (charge this first) and **Lower** (only if the customer asks for less), with the maths underneath. Tap one, then **Send quote** (Copy, Text or WhatsApp). The charge and your earnings stay pinned at the bottom.

**📋 Price list** shows the whole PESTABLE partner price list at a glance, with charge and earnings for each service and a worked example of how prices are calculated.

## Visits
- **1 visit:** end of lease flea, general pest (unit, single-storey, double-storey).
- **2 visits (German cockroach):** $202.50 per visit = $405 total, you earn $52.50 per visit = $105 total (Standard).
- **2 visits, PESTABLE quotes:** fleas in a lived-in home, bed bugs, mites, book mites, bird lice (biting pests).
- **PESTABLE quotes:** rats and mice.

## Prices (PESTABLE partner price list, Nov 2026, the same for Homes & Hedges and Response Real Estate)
| Service | Base | Standard: charge / you earn | Lower: charge / you earn |
|---|---|---|---|
| End of lease flea (1 visit) | $150 | $202.50 / $52.50 | $155.25 / $20.25 |
| General pest – unit | $150 | $202.50 / $52.50 | $155.25 / $20.25 |
| General pest – single-storey | $250 | $337.50 / $87.50 | $258.75 / $33.75 |
| General pest – double-storey | $300 | $405.00 / $105.00 | $310.50 / $40.50 |
| German cockroach (per visit, ×2) | $150 | $202.50 / $52.50 | $155.25 / $20.25 |

Standard = base + 35%. Lower = base − 10%, then + 15%. Your commission is the charge less the PESTABLE base.
Prices are typed in exactly as listed in `SERVICES` at the top of the `<script>` in `index.html`.

## Link
https://thecyberexterminator.github.io/PestRate/ (GitHub Pages, from the `gh-pages` branch). On iPhone, use Safari → Share → **Add to Home Screen** so it opens like an app.
