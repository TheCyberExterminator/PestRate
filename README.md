# PestRate

A partner pricing app for PESTABLE subcontractors. It's one file (`index.html`) with no build step, made for phones.

## The journey
1. **What are you dealing with?** Tap the pest. Pests that need two treatments are marked with a **2 TREATMENTS** badge. Pests PESTABLE prices itself are marked **QUOTE**.
2. **What type of property?** This step only appears for general pest (unit, single-storey or double-storey).
3. **Which price?** Choose **Standard**, or **Lower price** when the customer needs a reduction. Both options show your commission.
4. **Your quote.** You see the price per treatment, what the customer pays, your commission, the vacancy rules and what's included. You can add more services, switch between Standard and Lower, and Copy, Text or WhatsApp the quote. The total and your commission stay pinned at the bottom.

## Two treatments required
- **Biting pests:** fleas, mites, book mites, bird lice and bed bugs.
- **German cockroaches.**

Prices are per treatment. The customer total is the price per treatment × the number of treatments.

## Prices (from the PESTABLE Homes & Hedges price list, 13 Oct 2026)
| Service | Base | Standard (+35%) | Lower (base −10%, +15%) |
|---|---|---|---|
| End of lease flea | $150 | $202.50 | $155.25 |
| General pest – unit | $150 | $202.50 | $155.25 |
| General pest – single-storey | $250 | $337.50 | $258.75 |
| General pest – double-storey | $300 | $405.00 | $310.50 |
| German cockroach | $150 | $202.50 | $155.25 |

Bed bugs, mites, book mites, bird lice and rodents: contact PESTABLE (1300 197 368) for a quote.

Commission is the retail price less the PESTABLE base. To change prices, markups or the number of treatments, edit `PESTS`, `PROPERTY` and the constants at the top of the `<script>` in `index.html`.

## Link
https://thecyberexterminator.github.io/PestRate/ (GitHub Pages, from the `gh-pages` branch). On iPhone, use Safari → Share → **Add to Home Screen** so it opens like an app.
