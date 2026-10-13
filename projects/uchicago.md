# UChicago Trading Competition 2026

The team's repository contains two distinct cases: an event-driven trading bot and portfolio-strategy research. This work is separate from the SIG Predictions Cup.

Saavan led development and research for the integrated Case 1 bot used at the competition. The code covers exchange-event handling, news and earnings response, strategy state, order management, inventory controls, cross-market integration, diagnostic traces, and settlement/shutdown handling. The system incorporates teammate strategy components, whose origins remain attributed.

Case 2 contains collaborative portfolio submissions, notebooks, backtesting, and diagnostics. Saavan contributed to this work, but it is not presented as his sole implementation.

The Case 1 suite passed 211 offline tests during the October 2026 audit, including a new check requiring explicit runtime credentials. The Case 2 evaluator's imports and supplied data loading were also checked. These checks establish the tested behaviors, not profitability or live trading performance. No unaudited return, ranking, or Sharpe ratio is claimed here.

A cleaned personal publication is being prepared with both cases, while the original shared repository and its contributor history remain intact.
