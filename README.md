# Gold-SnR-Bot-MQL5
High win-rate XAUUSD trading bot with structural breakout protection.

🏆 XAUUSD High Win-Rate Performance Portfolio
This repository documents the live performance and risk management logic of my proprietary Gold Trading EA.

📊 Performance Summary (Example)
Daily Profit: $370.32
Win Rate: 80.50%
Max Drawdown: Currently being optimized from 31% down to <15% using new momentum filters.

🧠 Strategy Methodology (Private Logic)
The EA utilizes a mean-reversion strategy on the M1 timeframe:
Dynamic S&R: Scans the last 60 minutes to establish high/low boundaries.
Color Twin Filter: Price action confirmation before entering at range edges.
Structural Purge (New Update): A safety handshake that detects breakouts. If 3 consecutive candles show >100 points of momentum against the zone, all positions are closed to preserve capital.

🛡 Risk Controls
Hidden Hard Stop: $80 per position.
Profit Circuit Breaker: EA shuts down automatically at $255 profit.
Volatility Filter: ATR-based entry blocking during unstable market conditions.
