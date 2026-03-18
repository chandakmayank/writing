# Article Outline: Binary Momentum Trading on Polymarket

## Hook
- "70% of Polymarket traders lose money. The top 0.04% capture 70% of profits. What separates them? Momentum."
- Opening statistic that creates urgency
- Promise: learn the strategy that turns binary contracts into systematic gains

## Introduction
- What is Polymarket? (prediction market, binary outcomes)
- What is momentum trading? (following strong price movements)
- Why binary momentum trading matters now (2026 surge, $7.7B volume)
- Who this article is for (crypto traders, quant enthusiasts, prediction market newcomers)

## Section 1: Understanding Polymarket's Binary Structure
### 1.1 YES/NO Contracts Explained
- Each market = two ERC-1155 tokens (YES and NO)
- Prices $0.00-$1.00, always sum to $1
- Resolution: winner gets $1, loser gets $0

### 1.2 Order Book Mechanics
- Central Limit Order Book (CLOB) on Polygon
- Maker (0% fee) vs Taker (~1.4% fee)
- Visible depth and liquidity

### 1.3 Why Binary Markets Are Different
- Finite outcomes vs infinite price range
- Probability-based pricing
- Event-driven, not asset-driven

[Research needed: Polymarket API documentation for technical accuracy]

## Section 2: Momentum Trading Fundamentals
### 2.1 What Is Momentum Trading?
- Definition: buying/selling based on strength of price movement
- Traditional markets vs prediction markets
- Time horizon: short-term price acceleration

### 2.2 Momentum in Binary Markets
- YES/NO prices as probability signals
- News events create rapid repricing
- Example: "Will Fed cut rates?" YES jumps from 30% to 65% after dovish statement

### 2.3 The Edge: Speed and Information
- First movers capture the price shift
- Bots vs manual trading advantage
- 24/7 market means opportunities at all hours

[Research needed: specific examples of momentum events on Polymarket]

## Section 3: Binary Momentum Trading Strategy
### 3.1 Strategy Overview
- Identify markets experiencing major price shifts
- Enter in direction of momentum (buy rising YES or NO)
- Exit before momentum exhausts or event resolves

### 3.2 Entry Signals
- Breaking news (political, economic, crypto)
- Large order flow imbalances
- Cross-market correlation (crypto price moves → crypto prediction markets)
- Social sentiment shifts (Twitter, news volume)

### 3.3 Exit Rules
- Price target (e.g., 10-20% move from entry)
- Time-based exit (don't hold through resolution)
- Momentum reversal signals (price stalls, opposing news)

### 3.4 Position Sizing
- Kelly Criterion for binary bets
- Fixed fractional sizing
- Maximum exposure per event

[Research needed: backtesting data or case studies]

## Section 4: Building a Momentum Bot
### 4.1 Architecture Overview
- Polymarket Gamma API (market data)
- Polymarket CLOB API (order execution)
- Price monitoring and signal generation
- Risk management layer

### 4.2 Python Implementation
- Setting up API authentication
- Fetching market data
- Monitoring YES/NO price changes
- Placing orders programmatically
- [Code example: simple momentum bot skeleton]

### 4.3 Open Source Options
- GitHub: polymarket-kalshi-momentum-trading-bot
- PredictEngine no-code bot builder
- Polymarket official agents framework

[Research needed: actual code examples from GitHub repos]

## Section 5: Real-World Performance & Statistics
### 5.1 The Sobering Truth
- 70% of traders lose money
- Top 0.04% capture 70% of profits
- Only 5% make >$1,000
- Monthly active traders: ~462,600

### 5.2 Why Most Lose
- Overtrading and emotional decisions
- Poor risk management
- Trading illiquid markets
- Not understanding resolution criteria

### 5.3 How Winners Differ
- Systematic, rules-based approach
- Automation (bots execute without emotion)
- Focus on high-liquidity markets
- Proper position sizing

[Data source: on-chain analysis by defioasis.eth]

## Section 6: Risks and Pitfalls
### 6.1 Market Risks
- Event resolution ambiguity
- Illiquid markets with wide spreads
- Smart contract risks
- Regulatory actions (CFTC history)

### 6.2 Strategy Risks
- Momentum reversal (whipsaws)
- False/misleading news
- Slippage in fast markets
- Overconfidence after wins

### 6.3 Mitigation Strategies
- Trade only liquid markets (>$10K volume)
- Set strict stop-losses
- Verify news from multiple sources
- Size positions conservatively

## Section 7: Getting Started
### 7.1 Prerequisites
- Web3 wallet (MetaMask)
- USDC funding (via MoonPay or crypto transfer)
- Basic understanding of prediction markets

### 7.2 Paper Trading First
- Use small amounts to learn mechanics
- Track every trade in a spreadsheet
- Analyze what worked and what didn't

### 7.3 Scaling Up
- Start with single-contract positions
- Gradually increase size as you prove profitability
- Consider automation once strategy is validated

## Conclusion
- Summary of key takeaways
- Momentum trading on Polymarket is possible but difficult
- Automation and discipline separate winners from the 70% who lose
- Call to action: start with paper trading, study the data, build systematically

## Research To-Do
- [x] Polymarket binary structure mechanics
- [x] Momentum trading fundamentals
- [x] Trading strategies overview
- [x] Trader statistics and profit distribution
- [x] Bot architecture and open source projects
- [ ] Specific case studies of momentum trades
- [ ] Code examples for bot implementation
- [ ] Comparison with traditional momentum trading
- [ ] Regulatory landscape details
