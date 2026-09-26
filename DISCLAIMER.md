# Scope and terms

A personal research project, published as an engineering demonstration. Not a
product, not a service, not advice.

## The result is negative, and that is the finding

A round trip costs about **1.9%**, roughly 0.95% each way, taken in the spread
rather than charged as a fee, while the instruments it watches typically move
**2 to 3% in a day**. Over a month of replayed real prices the book is down, at
roughly 40% winners. The cost floor, not the strategy, decides the outcome.

This is reported rather than buried because measuring it was the point. See
[§6 of the README](README.md) for the numbers and
[§7](README.md) for what they do and do not support.

## It cannot place an order

The broker integration was removed before publication: the venue client is
deleted, `Settings.live_enabled` returns `False` unconditionally, and the only
execution modes are `paper` and `advisory`. The reasoning is in
[`docs/ROBINHOOD_API.md`](docs/ROBINHOOD_API.md).

## Terms

MIT License (see [`LICENSE`](LICENSE)), provided **"AS IS", without warranty of
any kind**. Nothing here is financial advice or a recommendation to buy, sell or
hold anything; the author is not a financial adviser and is not acting as one.

The software and every document in this repository are for research and
engineering study only. They are not investment, trading, legal or tax advice,
and past or simulated results say nothing about future results. Anyone who uses
any part of it does so entirely at their own risk, and the author accepts no
liability for any financial loss or other damage arising from that use.
