# Rummy Fun — Growth Audit (Shop)

**Live page: https://plykhvar-glitch.github.io/rummyfun-paywall-rebuild/**

Rummy Fun's coin Shop, rebuilt in its own design as a clickable landscape prototype. Your Shop stays
your own screen; Adapty tells it what to show, to whom, and which version wins. Under the phone,
the Remote Config payload that draws the Shop updates live as you switch the player segment or the
A/B test variant. English, German and French, light and dark, plus a 30-second walkthrough.

## The five ideas

| # | Idea | What changes | Potential outcome |
| :-- | :-- | :-- | :-- |
| 1 | A/B test your Shop without shipping a build | Packs, order, badges and bonus labels come from Adapty Remote Config. First test: “+7,500 free” instead of “30% free” | ARPU +5–10% |
| 2 | Open a different Shop for each kind of player | New players open on the Starter Pack, payers on 2,500, high spenders on the 75,000 chest | CR +10–15% |
| 3 | Show the Starter Pack when a new player leaves the Shop | Your 3,49 € Starter Pack opens as a sheet on back, with your own timer | ARPU +10–15% |
| 4 | Win back refunded coin packs, on iOS and on Android | Refund Saver answers Apple refund requests and Google Play chargebacks with how the coins were used | Refunds up to −40% |
| 5 | See where every coin goes | Coin-spend analytics we would build for you: coins bought, earned and spent, by segment | Built for you |

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across apps — not measured
lift for Rummy Fun. The refund figure is the reduction Adapty publishes for Refund Saver.*

Packs, prices, bonuses, badges and the Starter Pack timer come from Rummy Fun's own Shop
(build 2026.40.9). Ratings come from the App Store and Google Play listings.

## Run locally

```bash
python3 -m http.server 8000
```
