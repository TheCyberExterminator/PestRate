# PestRate

A partner pricing app for PESTABLE subcontractors. It's one file (`index.html`) with no build step, made for phones.

## How a subcontractor uses it
**⚡ Quick price** (two taps):
1. Tap the pest. Each tile shows the standard price, or says "PESTABLE quotes".
2. For general pests only, tap the property type.

The result shows **Charge customer** next to **You earn** at the standard price.

**Customer wants a lower price?** Drag the slider, or tap ▼ Lower / ▲ Higher (in $5 steps). The discount comes out of the subcontractor's commission, and the colour bar shows how much commission is left. The price can't go below the PESTABLE base, where they earn $0. **Back to standard** resets it. **Send quote** (Copy, Text or WhatsApp) uses whatever price is set.

**📋 Price list** shows every service at the standard price, with commission and the lowest possible price.

## Visits
- **1 visit:** end of lease flea, general pest (unit, single-storey, double-storey).
- **German cockroach:** priced per visit, 2 visits required.
- **2 visits, PESTABLE quotes:** fleas in a lived-in home, bed bugs, mites, book mites, bird lice (biting pests).
- **PESTABLE quotes:** rats and mice.

## Prices (PESTABLE partner price list, Nov 2026)
| Service | PESTABLE base (lowest price) | Standard charge | You earn at standard |
|---|---|---|---|
| End of lease flea (1 visit) | $150 | $202.50 | $52.50 |
| General pest – unit | $150 | $202.50 | $52.50 |
| General pest – single-storey | $250 | $337.50 | $87.50 |
| General pest – double-storey | $300 | $405.00 | $105.00 |
| German cockroach (per visit, ×2) | $150 | $202.50 | $52.50 |

Standard = base + 35%. You earn = the price charged − the PESTABLE base. Prices are in `SERVICES` at the top of the `<script>` in `index.html`.

## Link
https://thecyberexterminator.github.io/PestRate/ (GitHub Pages, from the `gh-pages` branch). On iPhone, use Safari → Share → **Add to Home Screen** so it opens like an app.
