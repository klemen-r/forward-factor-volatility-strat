# Forward Factor Volatility Strategy
A fully systematic options strategy that exploits persistent mispricings in the term structure of implied volatility.

This project implements the complete quant framework behind the Forward Factor calendar strategy — from signal generation to execution and portfolio management. It computes forward volatility between expirations, detects dislocations via the Forward Factor metric, and allocates capital across long calendar or double-calendar spreads based on the magnitude of the mispricing.

Includes:
• Full-featured research & backtesting engine (event-driven)
• Signal pipeline (forward vol, X-earn IV, liquidity filters)
• Portfolio construction with fractional Kelly sizing
• Execution model with spread-aware slippage and risk controls
• Live dashboard for analytics, reporting, and monitoring
