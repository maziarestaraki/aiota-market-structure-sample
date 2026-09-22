# AIOTA Market Structure Suite — Portfolio Excerpt

A deliberately limited Pine Script v6 excerpt from a much larger market-structure product. The production indicator contains approximately 3,500 lines and six integrated analysis modules. The proprietary module logic is not included here.

## The product problem

Traders often combine several market-structure methods, but separate indicators create visual noise, overlapping labels, inconsistent signals, and fragmented decisions. I designed one modular system that could cover major structure concepts while remaining configurable and readable.

## Production system coverage

- Smart Money concepts: BOS/CHoCH, order blocks, fair-value gaps, equal highs/lows, and premium/discount zones
- Dynamic trendline and channel zones
- Major and minor support/resistance
- Trading-session killzones
- Break-and-retest analysis
- ICT concepts including OTE, Judas Swing, Turtle Soup, and Power of Three

## What the public excerpt demonstrates

- A shared display engine with ATR-scaled collision handling across modules
- Automatic text contrast for configurable label backgrounds
- A shared bullish/bearish signal bus
- A configurable four-slot confluence engine
- State tracking with bar-window logic
- Alert generation for combined BUY and SELL events

[View the limited Pine Script excerpt](./aiota-market-structure-excerpt.pine)

## My role

I defined the product behavior, modules, configuration model, visual rules, signal interactions, and edge cases. I directed Claude and ChatGPT through implementation, tested the output inside TradingView, identified compilation and behavioral problems, and iterated until it matched the intended behavior.

I am an AI-assisted product builder rather than a traditional software engineer. My value is translating a complex domain problem into a structured product, maintaining the full system context, testing hard, diagnosing gaps, and continuing until the result works.

## Related work

- [AIOTA platform](https://www.aiota.trade/)
- [AIOTA Trading Journal Pro on the official MQL5 Market](https://www.mql5.com/en/market/product/196135)
- [Maziar Estaraki — GitHub profile](https://github.com/maziarestaraki)

## Scope and intellectual property

This repository is a portfolio sample. Six proprietary analysis modules and the complete production implementation are intentionally omitted. It is provided for evaluation and discussion, not as the complete commercial product.
