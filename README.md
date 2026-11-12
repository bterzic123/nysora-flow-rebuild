# Growth Audit — NYSORA Nerve Blocks

**Live: https://bterzic123.github.io/nysora-flow-rebuild/**

NYSORA Nerve Blocks asks every new install five questions, then never shows the paywall on first launch: it waits behind Settings → Subscribe Now. This audit rebuilds the first launch in NYSORA's own design and at its own prices, so the paywall answers each profession and specialty. The prototype has three phones, one for each of the Meta ads running today.

## The five ideas

| # | Idea | Expected effect |
| :-- | :-- | :-- |
| 1 | Show the paywall at the end of first launch | CR +10–20% |
| 2 | Name their profession and specialty in the headline | CR +15–20% |
| 3 | Use the answers before the paywall (a loader that reads them back, then "Your first blocks") | CR +10–15% |
| 4 | Ask for the account and push after the paywall | CR +5–10%, ARPU +10–17% |
| 5 | Put your rating and a named review next to the plans | CR +5–10% |

The paywall's X always closes straight into the app. There is no second paywall.

## Grounding

The screens, copy, question lists, paywall quotes, bullets and prices come from the NYSORA Nerve Blocks iOS app, recorded on 12 November 2026 (EU storefront: 149,99 € a year, 22,99 € a month). The 4.9 rating from 1.1K ratings and the review by denelson2 come from the US App Store. The 15,000+ anesthesiologists, 70+ techniques and institutional access come from nysora.com. The ads and their dates are from Meta, as seen by AppMagic.

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for NYSORA.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?view=proto` to open the prototype directly.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
