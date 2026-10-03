# Does Price Remember Where It Turned?

A research note by Zihan (Eric) Lin, October 2026.

**Read it:** https://faustzi.github.io/price-memory/ · [PDF](does-price-remember-where-it-turned.pdf)

## Summary

Do large one-way moves in E-mini S&P 500 futures start, or resume after a pullback, more often near recent turns that price has not broken, and where little has traded, than at other prices at the same time? The note states a trader-behaviour explanation, derives seven testable predictions, and measures each against fake markets: the real one-minute path cut into 13-minute blocks whose directions are flipped at random, which keep volatility and its clustering but erase any memory of price.

A two-term model fitted on 2022–2023 was frozen before the held-out year was read. In that year, each place was ranked only against the places price had visited over the previous trading day. Those in the top tenth went on to move eight times the session's typical swing 17.7% of the time, against 11.3% for the rest, a larger gap than in any of 20 fake markets. The edge lies at pullbacks that hold and at the first such place of each session, not at the exact origins of moves, and it disappears when the model reads the history of a price 4σ or 8σ away instead (σ = 0.206% of price), with the fake markets read the same way. The note also reports the explanations that did not hold, nine ways the measurement fooled itself, and what the data cannot show.

## Contents

- `index.html` — the note
- `does-price-remember-where-it-turned.pdf` — the same note as an A4 PDF

## Code and data

The research code and the market data are not included; the price data are licensed. The code is available on request.

## Licence

© 2026 Zihan (Eric) Lin. Licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/): you may share the note with credit, but not for commercial purposes and not in modified form.
