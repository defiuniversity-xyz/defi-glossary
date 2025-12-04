# DeFi Glossary

A comprehensive glossary of terms, definitions, and concepts extracted from the DeFi University course materials.

**Source Courses:**
- Beginner DeFi Concepts
- Liquidity Provision
- Money Markets
- Perpetual Futures Trading
- Investor Mindset

---

## Table of Contents

- [A](#a)
- [B](#b)
- [C](#c)
- [D](#d)
- [E](#e)
- [F](#f)
- [G](#g)
- [H](#h)
- [I](#i)
- [L](#l)
- [M](#m)
- [O](#o)
- [P](#p)
- [R](#r)
- [S](#s)
- [T](#t)
- [U](#u)
- [V](#v)
- [W](#w)
- [Z](#z)

---

## A

### Aave
**Source:** Money Markets

A decentralized lending protocol and the largest DeFi money market, managing over $70 billion in total value locked (TVL). Aave uses a monolithic pool model where all assets are pooled together into shared liquidity reserves. Key features include High Efficiency Mode (eMode) for correlated assets, Isolation Mode for risky assets, and a unified risk management system via governance.

**Related Terms:** Money Market, LTV, Health Factor, Isolation Mode, E-Mode

---

### Account Abstraction
**Source:** Beginner DeFi Concepts

Emerging wallet technology that improves user experience by allowing features like social recovery, daily spending limits, and bundled transactions. This represents the future of user interaction, abstracting away raw private key management.

**Related Terms:** Smart Contract Wallet, Wallet, Private Key

---

### Algorithmic Interest Rates
**Source:** Money Markets

Interest rates in DeFi money markets that adjust automatically based on supply and demand, unlike banks that set fixed rates. High borrowing demand leads to higher interest rates (encouraging more deposits, discouraging borrowing), while low demand leads to lower rates.

**Related Terms:** Money Market, Utilization Rate, Interest Rate Curve

---

### Algorithmic Stablecoin
**Source:** Beginner DeFi Concepts

A type of stablecoin that attempts to maintain a peg via supply elasticity and incentives rather than full collateral backing. History (e.g., Terra/Luna) suggests these are highly risky and prone to "death spirals" where the mechanism fails catastrophically.

**Related Terms:** Stablecoin, Fiat-Collateralized Stablecoin, Crypto-Collateralized Stablecoin, Stablecoin Trilemma

---

### Anchoring Bias
**Source:** Investor Mindset

A cognitive bias where traders fixate on all-time highs or purchase prices instead of current market reality. The fix: Use multiple valuation metrics beyond price—TVL growth, user adoption, revenue generation.

**Related Terms:** Cognitive Bias, Loss Aversion, Confirmation Bias

---

### AMM (Automated Market Maker)
**Source:** Beginner DeFi Concepts, Liquidity Provision

A decentralized exchange protocol that uses mathematical formulas instead of order books to determine prices and execute trades. Think of it as a robot market maker that's always ready to trade, 24/7, without needing human market makers or centralized exchanges.

**Key Innovation:** Instead of waiting for someone to match your order, you trade directly against the pool's reserves.

**Related Terms:** DEX, Liquidity Pool, Constant Product Formula, Price Impact

---

### AppChain (Application-Specific Blockchain)
**Source:** Perpetual Futures

A dedicated blockchain optimized exclusively for a specific application (e.g., dYdX v4, Hyperliquid). These chains run on their own infrastructure, optimized for trading activity with high throughput and low latency.

**Related Terms:** CLOB, Hyperliquid, dYdX

---

### Arbitrage
**Source:** Liquidity Provision, Perpetual Futures

The practice of buying an asset on one exchange and selling it on another to profit from price differences. In DeFi, arbitrageurs help maintain price consistency across pools by buying "cheap" assets and selling "expensive" ones.

**Related Terms:** Price Impact, Slippage, MEV

---

### Atomic Settlement
**Source:** Beginner DeFi Concepts

Trades settle within the block time of the network (e.g., ~12 seconds on Ethereum, ~0.4 seconds on Solana). There is no T+2 delay; the trade and the settlement are the same event, eliminating counterparty settlement risk.

**Related Terms:** Smart Contract, DeFi, Blockchain

---

### Atomic Transaction
**Source:** Beginner DeFi Concepts

A transaction that either fully succeeds or fully reverts—there is no partial execution. This property enables flash loans and complex DeFi strategies.

**Related Terms:** Flash Loan, Smart Contract

---

## B

### Blockchain Trilemma
**Source:** Beginner DeFi Concepts

Coined by Ethereum co-founder Vitalik Buterin, this concept posits that a decentralized network can only optimize for two of three properties simultaneously: **Decentralization, Security, and Scalability**.

- **Bitcoin/Ethereum**: Prioritize Decentralization + Security → Sacrifice Scalability
- **Solana**: Prioritize Scalability + Security → Sacrifice some Decentralization

**Related Terms:** Layer 1, Layer 2, Rollup, Scalability

---

### Bridge
**Source:** Beginner DeFi Concepts

A protocol that allows transferring assets between different blockchains (e.g., from Ethereum to Arbitrum). Bridges can have security risks, so always use official, audited bridges.

**Related Terms:** Layer 2, Cross-Chain, Bridge Risk

---

## C

### CeFi (Centralized Finance)
**Source:** Beginner DeFi Concepts

Centralized crypto finance platforms like Coinbase or Binance. These platforms offer crypto services but maintain custody of user funds and operate on private, proprietary ledgers. They replicate the structural weaknesses of traditional finance—centralized trust, opaque ledgers, and human fallibility—often without the regulatory guardrails of TradFi.

**Key Characteristics:**
- **Custodial**: Exchange holds your funds
- **Opaque**: Private ledgers, not publicly verifiable
- **Permissioned**: KYC/AML requirements

**Related Terms:** TradFi, DeFi, Custody

---

### CLOB (Central Limit Order Book)
**Source:** Perpetual Futures

A trading model that replicates the traditional exchange experience where market makers post buy/sell orders at specific prices, traders execute against the order book, and price discovery happens through supply and demand.

**Examples:** Hyperliquid, dYdX v4, EdgeX

**Benefits:**
- CEX-like performance
- Transparent order book
- Limit orders, stop losses
- Deep liquidity (if market makers active)

**Risks:**
- Slippage on large orders
- Front-running risk
- Requires active market makers

**Related Terms:** Oracle Pool, Perpetual Future, Order Book

---

### Cognitive Bias
**Source:** Investor Mindset

Systematic errors in thinking that affect decision-making. In DeFi trading, common biases include confirmation bias, FOMO, loss aversion, anchoring bias, herd mentality, and overconfidence.

**Related Terms:** Fixed Mindset, Growth Mindset, Risk Tolerance

---

### Collateral
**Source:** Money Markets, Perpetual Futures

Assets deposited to secure a loan or trading position. In DeFi lending, you must deposit collateral worth more than the amount you borrow (over-collateralization). In perpetual futures, margin serves as collateral for leveraged positions.

**Related Terms:** Over-Collateralization, LTV, Margin, Health Factor

---

### Composability
**Source:** Beginner DeFi Concepts

The ability for different DeFi protocols to work together seamlessly, like "Money Legos." Because tokens follow standards (ERC-20, ERC-721), protocols can build on top of each other.

**Example:** Deposit USDC in Aave → Receive aTokens → Use aTokens as collateral in Compound → Swap tokens on Uniswap, all in a single transaction.

**Related Terms:** ERC-20, ERC-721, Smart Contract, DeFi

---

### Concentrated Liquidity
**Source:** Liquidity Provision

Uniswap V3's innovation that allows liquidity providers to concentrate their liquidity in a specific price range rather than across the entire price curve. This enables up to 4000x capital efficiency for stablecoin pairs.

**Trade-off:** Higher efficiency = higher risk if price exits your range.

**Related Terms:** Uniswap V3, Liquidity Pool, Ticks, Price Range

---

### Confirmation Bias
**Source:** Investor Mindset

A cognitive bias where your brain seeks information confirming your beliefs while actively filtering out contradictory evidence. This destroys portfolios by creating echo chambers of false confidence.

**The Fix:** Red team your thesis—for every bull case, create an equally detailed bear case.

**Related Terms:** Cognitive Bias, FOMO, Loss Aversion

---

### Constant Product Formula
**Source:** Liquidity Provision, Beginner DeFi Concepts

The fundamental equation governing most AMMs (like Uniswap V2):

$$x \cdot y = k$$

Where:
- **x** = Reserve of token X (e.g., ETH)
- **y** = Reserve of token Y (e.g., USDC)
- **k** = Constant (must remain the same after every trade)

**How It Works:** When a trader buys Token A from the pool, the supply of x decreases. To keep k constant, the supply of y must increase. This algorithmic relationship automatically adjusts the price based on supply and demand.

**Related Terms:** AMM, Liquidity Pool, Price Impact, Slippage

---

### Crypto-Collateralized Stablecoin
**Source:** Beginner DeFi Concepts

A decentralized and trustless stablecoin where users lock volatile crypto assets in a smart contract to mint stablecoins. This requires over-collateralization to absorb volatility.

**Example:** DAI

**Related Terms:** Stablecoin, Fiat-Collateralized Stablecoin, Algorithmic Stablecoin, Over-Collateralization

---

### Custody
**Source:** Beginner DeFi Concepts

The control and storage of assets. In TradFi and CeFi, users do not truly own their money; they are creditors to the bank or exchange. In DeFi, self-custody means you control your private keys and thus your funds.

**Related Terms:** Self-Custody, Wallet, Private Key, CeFi, TradFi

---

## D

### DAI
**Source:** Beginner DeFi Concepts

A decentralized, crypto-collateralized stablecoin created by MakerDAO. Users lock ETH or other crypto assets to mint DAI, which maintains its peg through over-collateralization and algorithmic mechanisms.

**Related Terms:** Stablecoin, Crypto-Collateralized Stablecoin, MakerDAO

---

### DeFi (Decentralized Finance)
**Source:** Beginner DeFi Concepts

A financial system built on public, permissionless blockchains (primarily Ethereum) where financial services are executed by Smart Contracts—autonomous, self-executing code—rather than by centralized intermediaries.

**Key Characteristics:**
- **Non-Custodial**: You control your funds
- **Radical Transparency**: Every transaction is visible on-chain
- **Permissionless Access**: Open to anyone with an internet connection
- **Atomic Settlement**: Trades settle within block time
- **Composability**: Protocols work together seamlessly

**Related Terms:** TradFi, CeFi, Smart Contract, AMM, Money Market

---

### DEX (Decentralized Exchange)
**Source:** Beginner DeFi Concepts, Liquidity Provision

A cryptocurrency exchange that operates without a central authority, using smart contracts to facilitate trades. DEXs use AMMs (Automated Market Makers) instead of traditional order books.

**Examples:** Uniswap, SushiSwap, Curve

**Related Terms:** AMM, CEX, Liquidity Pool, Order Book

---

### Disposition Effect
**Source:** Investor Mindset

A cognitive bias where traders sell winners too early while holding losers too long, systematically reducing returns over time.

**The Fix:** Use systematic rebalancing rules based on conviction changes, not comfort levels.

**Related Terms:** Cognitive Bias, Loss Aversion

---

### Double-Entry Bookkeeping
**Source:** Beginner DeFi Concepts

A system codified by Luca Pacioli in 1494, popularized by the Medici family. This system ensures that every transaction is recorded twice—once as a debit and once as a credit—ensuring that the books always balance:

$$Assets = Liabilities + Equity$$

**Related Terms:** Ledger, TradFi, Historical Finance

---

## E

### E-Mode (Efficiency Mode)
**Source:** Money Markets

Aave's High Efficiency Mode that allows extremely high LTVs (up to 97%) for correlated assets. Example: USDC/USDT pairs can leverage at 97% LTV. Designed for forex-style arbitrage and yield farming.

**Risk:** Small depegs (like USDC's $0.87 in March 2023) can trigger instant liquidations.

**Related Terms:** Aave, LTV, Isolation Mode, Money Market

---

### ERC-20
**Source:** Beginner DeFi Concepts

A token standard for fungible tokens on Ethereum. Every ERC-20 token is identical to another of the same type (e.g., 1 USDC = 1 USDC). They serve as the medium of exchange in DeFi, collateral in lending protocols, and governance voting power.

**Key Properties:**
- **Fungible**: Each token is identical and interchangeable
- **Divisible**: Can be split into smaller units (e.g., 0.001 USDC)
- **Transferable**: Can be sent between addresses

**Related Terms:** ERC-721, Token Standard, Smart Contract, Composability

---

### ERC-721
**Source:** Beginner DeFi Concepts

A token standard for non-fungible tokens (NFTs) on Ethereum. While popular for art, in DeFi, NFTs represent unique financial positions. For example, a liquidity provider position in Uniswap V3 is represented as an NFT because it has unique parameters (price range, amount) specific to that user.

**Key Properties:**
- **Non-Fungible**: Each token is unique
- **Indivisible**: Cannot be split (you own the whole NFT or none)
- **Metadata**: Can store additional information

**Related Terms:** ERC-20, NFT, Uniswap V3, Concentrated Liquidity

---

### EVM (Ethereum Virtual Machine)
**Source:** Beginner DeFi Concepts

A turing-complete environment that allows developers to upload persistent scripts known as "smart contracts." The EVM is a state machine: a global computer that transitions from one state to the next with every block of transactions.

**Related Terms:** Ethereum, Smart Contract, Gas, State Machine

---

## F

### Fiat-Collateralized Stablecoin
**Source:** Beginner DeFi Concepts

A centralized stablecoin where a centralized entity holds $1 in a bank account for every 1 token issued. These are capital efficient (1:1 backing) but suffer from centralization risk (custodian can freeze funds).

**Examples:** USDC, USDT

**Related Terms:** Stablecoin, Crypto-Collateralized Stablecoin, Algorithmic Stablecoin, Stablecoin Trilemma

---

### Fiat Currency
**Source:** Beginner DeFi Concepts

Money by decree, where value is not derived from an underlying commodity but solely from trust in the issuing government's stability, military power, and ability to levy taxes. The term fiat is Latin for "let it be done" or "it shall be."

**Historical Context:** The Nixon Shock (August 15, 1971) marked the end of the Gold Standard and the birth of the modern fiat monetary regime.

**Related Terms:** Gold Standard, TradFi, Money

---

### Fixed Mindset
**Source:** Investor Mindset

A trading psychology where traders view losses as personal failures and avoid challenging DeFi opportunities to protect their ego. They believe trading ability is innate talent—you either have it or you don't.

**Contrast:** Growth Mindset

**Related Terms:** Growth Mindset, Trading Psychology, Cognitive Bias

---

### Flash Loan
**Source:** Beginner DeFi Concepts

A financial primitive with **no equivalent in traditional finance**. Flash loans allow borrowing immense capital without upfront collateral, provided the liquidity is returned within the same transaction block.

**The Mechanism:**
1. Borrow funds (no collateral needed)
2. Execute operations (arbitrage, collateral swapping, etc.)
3. Repay loan + fee in the same transaction
4. If repayment fails → entire transaction reverts

**Use Cases:** Arbitrage, collateral swapping, liquidation, and (unfortunately) exploits.

**Related Terms:** Atomic Transaction, Smart Contract, DeFi

---

### FOMO (Fear of Missing Out)
**Source:** Investor Mindset

A cognitive bias that creates compulsive buying at exactly the wrong times. Your brain treats missed gains as actual losses, driving irrational urgency.

**The Fix:** Implement the 48-Hour Rule—never invest in anything trending for less than 48 hours.

**Related Terms:** Cognitive Bias, Confirmation Bias, Loss Aversion

---

### Funding Rate
**Source:** Perpetual Futures

The mechanism that keeps perpetual prices aligned with spot prices. The funding rate is calculated as:

$$Funding Rate = \frac{Perpetual Price - Spot Price}{Spot Price} \times Adjustment Factor$$

**Key Points:**
- **Positive Funding**: Perp > Spot → Longs pay shorts
- **Negative Funding**: Perp < Spot → Shorts pay longs
- **Frequency**: Most protocols calculate funding every hour or every 8 hours

**Strategic Implication:** Funding rates can be significant. In strong trends, annualized funding rates can exceed 100%. Holding a position against the funding rate can erode capital.

**Related Terms:** Perpetual Future, Margin, Leverage, CLOB

---

## G

### Gas
**Source:** Beginner DeFi Concepts

The fee paid to network validators to execute computational steps. It serves a dual purpose:
1. **Incentivizing Security**: Paying validators to secure the network
2. **Preventing Spam**: Making infinite loops prohibitively expensive

**Key Understanding:** Complex DeFi interactions (like entering a liquidity pool) cost more gas than simple transfers because they require more computational work from the EVM.

**Gas Units vs. Gas Price:**
- **Gas Units**: The computational work required (e.g., a simple transfer = 21,000 gas units)
- **Gas Price**: The price per unit (measured in Gwei, where 1 Gwei = 0.000000001 ETH)
- **Total Cost**: Gas Units × Gas Price = Transaction Fee

**Related Terms:** EVM, Gwei, Transaction Fee, Layer 2

---

### Governance Risk
**Source:** Beginner DeFi Concepts, Money Markets

The risk that protocol governance (often via DAOs) is compromised, allowing malicious actors to drain protocols or make harmful changes. Many protocols are governed by DAOs, and if governance is compromised, protocols can be drained.

**Mitigation:** Understand governance structures. Be wary of highly centralized governance.

**Related Terms:** DAO, Smart Contract Risk, Oracle Risk

---

### Gwei
**Source:** Beginner DeFi Concepts

A unit of measurement for gas price, where 1 Gwei = 0.000000001 ETH. Gas prices are typically measured in Gwei.

**Related Terms:** Gas, Transaction Fee, EVM

---

### Growth Mindset
**Source:** Investor Mindset

A trading psychology where traders see losses as expensive but valuable education. They embrace complex DeFi protocols as learning opportunities and believe skills improve through deliberate practice.

**Contrast:** Fixed Mindset

**Related Terms:** Fixed Mindset, Trading Psychology, Cognitive Bias

---

## H

### Health Factor
**Source:** Money Markets, Beginner DeFi Concepts

The single most important metric when borrowing in money markets. The Health Factor formula is:

$$Health Factor = \frac{Collateral Value \times Liquidation Threshold}{Total Debt}$$

**Interpreting Health Factor:**
- **HF > 1.0**: Position is safe
  - HF = 2.0: Can withstand ~50% collateral price drop
  - HF = 1.5: Can withstand ~33% collateral price drop
  - HF = 1.1: Danger zone—any small price movement risks liquidation
- **HF ≤ 1.0**: Position is liquidatable

**Strategic Health Factor Targets:**
- **For Beginners**: HF > 2.0 (substantial buffer)
- **For Active Traders**: HF = 1.5 - 2.0 (higher capital efficiency, requires monitoring)

**Related Terms:** LTV, Liquidation Threshold, Collateral, Money Market

---

### Herd Mentality
**Source:** Investor Mindset

A cognitive bias where traders follow crypto Twitter consensus without independent analysis, leading to buying tops and selling bottoms with the crowd.

**The Fix:** Actively seek contrarian viewpoints. If everyone agrees, everyone is probably wrong.

**Related Terms:** Cognitive Bias, Confirmation Bias, FOMO

---

### Hot Wallet
**Source:** Beginner DeFi Concepts

A wallet connected to the internet (e.g., MetaMask, Phantom). They are convenient for daily DeFi interaction but vulnerable to malware, screen scrapers, and clipboard hijacking.

**Best Practice:** Treat hot wallets like a physical wallet—carry only "walking around money." Never store significant amounts in hot wallets.

**Related Terms:** Cold Wallet, Hardware Wallet, Wallet, Private Key

---

### Hub-and-Spoke Architecture
**Source:** Money Markets, Beginner DeFi Concepts

A financial architecture model where a central hub (headquarters) connects to multiple spokes (branches). In Aave V4, the Hub consolidates all protocol-wide liquidity, while Spokes are user-facing modules with specific lending logic.

**Historical Context:** The Medici Bank popularized this model in Renaissance Italy, centralizing trust but introducing a Single Point of Failure.

**Related Terms:** Aave V4, Money Market, Monolithic Pool Model

---

## I

### Impermanent Loss (IL)
**Source:** Liquidity Provision, Beginner DeFi Concepts

The difference between:
- What your LP position is worth
- What your tokens would be worth if you just held them

**Key Point:** IL occurs when the price ratio of the two tokens changes from when you deposited.

**Why It Happens:** AMMs automatically rebalance your position as prices change. You're always selling winners and buying losers—the opposite of what profitable traders do.

**Important:** IL is called "impermanent" because it only becomes permanent when you withdraw, but the reality is: most LPs lose money to IL, even when earning fees.

**Related Terms:** Liquidity Pool, AMM, Price Impact, Liquidity Provider

---

### Initial Margin
**Source:** Perpetual Futures

The minimum collateral required to open a position:

$$Initial Margin = \frac{Position Size}{Leverage}$$

**Example:** Position Size: $10,000, Leverage: 10x → Initial Margin: $1,000

**Related Terms:** Maintenance Margin, Margin, Leverage, Perpetual Future

---

### Interest Rate Curve
**Source:** Money Markets

The mathematical relationship between utilization rate and interest rates in a money market. As utilization increases, interest rates rise to incentivize more deposits and discourage borrowing.

**Related Terms:** Money Market, Utilization Rate, Algorithmic Interest Rates

---

### Isolation Mode
**Source:** Money Markets

Aave's feature that allows listing newer, volatile assets safely. Restrictions include:
- Can only borrow stablecoins (USDC, USDT, DAI)
- Cannot use other assets as collateral simultaneously
- Debt ceiling caps total borrowing

**Purpose:** Firewall to prevent contagion from risky assets.

**Related Terms:** Aave, E-Mode, Money Market, LTV

---

## L

### Layer 0
**Source:** Beginner DeFi Concepts

The infrastructure and interoperability layer connecting different blockchains. If blockchains (Bitcoin, Ethereum) are independent cities with their own laws and currencies, Layer 0 is the highway system and diplomatic corps connecting them.

**Examples:**
- **Polkadot**: Uses a central "Relay Chain" (Layer 0) to provide shared security and consensus to connected "Parachains" (specialized Layer 1s)
- **Cosmos**: Uses the Inter-Blockchain Communication (IBC) protocol to allow independent "Zones" to swap assets and data

**Related Terms:** Layer 1, Layer 2, Blockchain, Interoperability

---

### Layer 1 (L1)
**Source:** Beginner DeFi Concepts

The base blockchain (e.g., Ethereum, Bitcoin). In a modular stack, the L1 is not where you buy a coffee; it is where you settle the books at the end of the day.

**The Supreme Court Analogy:** Think of Ethereum (L1) as the Supreme Court. It is expensive, slow, and authoritative. You do not go to the Supreme Court to contest a speeding ticket (a micro-transaction). You only go there to resolve major disputes or to finalize the "ultimate truth."

**Role:** The L1 provides Data Availability and Consensus. It ensures that the record is immutable and secure. It is the anchor of trust.

**Related Terms:** Layer 0, Layer 2, Rollup, Blockchain Trilemma

---

### Layer 2 (L2)
**Source:** Beginner DeFi Concepts

Solutions that sit on top of L1. They handle the heavy lifting of processing transactions (Execution) and only report the final results to L1 for settlement.

**The Highway Analogy:** If L1 is a congested, single-lane road through a city center, L2 is an elevated Express Highway built above it. Cars (transactions) zip along the express highway at high speed. Periodically, the express highway bundles all the traffic data and sends a single "bus" (batch) down to the main road to register the movement.

**Types of Rollups:**
1. **Optimistic Rollups** (e.g., Arbitrum, Optimism): Assume transactions are valid by default, with a challenge period
2. **ZK-Rollups** (e.g., zkSync, Starknet): Use advanced cryptography to prove transaction validity instantly

**Security Inheritance:** Crucially, L2s inherit the security of L1. A user on Arbitrum (L2) is ultimately protected by Ethereum's (L1) consensus.

**Related Terms:** Layer 1, Rollup, Optimistic Rollup, ZK-Rollup, Gas

---

### Ledger
**Source:** Beginner DeFi Concepts

A record of financial transactions. The history of finance is the history of the ledger: the record of who owes what to whom. Money is, and always has been, a system of accounting—a technology for recording debts and credits.

**Related Terms:** Blockchain, Money, Trust, Double-Entry Bookkeeping

---

### Leverage
**Source:** Perpetual Futures

The ability to control a larger position with less capital. With 10x leverage, $1,000 controls a $10,000 position. Profits and losses are multiplied by the leverage factor.

**Common Leverage Levels:**
- **Conservative**: 2-5x (recommended for beginners)
- **Moderate**: 5-10x (intermediate traders)
- **Aggressive**: 10-50x+ (advanced traders, high risk)

**Related Terms:** Margin, Initial Margin, Maintenance Margin, Perpetual Future

---

### Liquidation
**Source:** Money Markets, Perpetual Futures

The forced sale of collateral to repay debt when a position becomes unsafe. In money markets, liquidation is triggered automatically when Health Factor drops below 1.0. In perpetual futures, liquidation occurs when margin falls below maintenance margin.

**The Process:**
1. Position becomes unsafe (HF < 1.0 or margin < maintenance)
2. Liquidator bots detect the unsafe position
3. Liquidator repays debt (or part of it)
4. Liquidator receives collateral at a discount (e.g., 5-10% bonus)
5. Remaining collateral (if any) returns to you

**Liquidation Penalty:** Typically 5-10% of liquidated collateral value.

**Related Terms:** Health Factor, LTV, Liquidation Threshold, Margin, Maintenance Margin

---

### Liquidation Risk
**Source:** Beginner DeFi Concepts, Money Markets

The risk that a position will be liquidated if collateral value drops or debt grows. In lending protocols, positions can be liquidated if collateral value drops. In perpetual futures, positions are liquidated if margin falls below maintenance margin.

**Mitigation:** Monitor health factors. Don't max out borrowing capacity. Maintain adequate margin buffers.

**Related Terms:** Liquidation, Health Factor, Margin, Collateral

---

### Liquidation Threshold (LT)
**Source:** Money Markets

The safety line—the collateral-to-debt ratio at which liquidation is triggered. If LT = 85%, liquidation occurs when your debt equals 85% of collateral value.

**The Safety Buffer** = LT - LTV

**Example:** Collateral: $10,000, LTV: 80%, LT: 85%
- Maximum borrow: $8,000
- Safety buffer: $500 (can withstand $500 price drop before liquidation)

**Related Terms:** LTV, Health Factor, Liquidation, Collateral

---

### Liquidity Pool
**Source:** Liquidity Provision, Beginner DeFi Concepts

A smart contract that holds two tokens in reserve. When you provide liquidity, you're depositing both tokens in equal value. Traders swap against the pool's reserves rather than matching with individual orders.

**Pool Components:**
1. **Token Pair**: Two tokens (e.g., ETH/USDC, DAI/USDT)
2. **Reserves**: Current amounts of each token
3. **Liquidity Providers (LPs)**: People who deposit tokens
4. **Trading Fees**: Usually 0.3% (0.05% for stablecoins) paid to LPs
5. **LP Tokens**: Receipt tokens representing your share of the pool

**Related Terms:** AMM, Liquidity Provider, Constant Product Formula, Impermanent Loss

---

### Liquidity Provider (LP)
**Source:** Liquidity Provision

A user who deposits tokens into a liquidity pool to earn fees from trades. When you provide liquidity, you deposit equal values of both tokens and receive LP tokens representing your share. You earn fees from all trades in the pool, proportional to your share.

**Related Terms:** Liquidity Pool, AMM, Impermanent Loss, Fee Distribution

---

### Loan-to-Value (LTV)
**Source:** Money Markets

The maximum borrowing capacity as a percentage of collateral value. If LTV = 80%, you can borrow up to $80 for every $100 of collateral.

**Important:** This is NOT the liquidation point. The Liquidation Threshold (LT) is the actual danger line.

**Example:** Collateral: $10,000 worth of ETH, Maximum LTV: 80% → Maximum borrow: $8,000

**Related Terms:** Liquidation Threshold, Health Factor, Over-Collateralization, Collateral

---

### Loss Aversion
**Source:** Investor Mindset

A cognitive bias where losses feel twice as painful as equivalent gains feel good, leading to holding losers far too long and selling winners far too early.

**The Fix:** Set pre-commitment stops before entering positions. Adopt the portfolio perspective—focus on total performance, not individual position outcomes. Reframe losses as tuition.

**Related Terms:** Cognitive Bias, Disposition Effect, Confirmation Bias

---

## M

### Maintenance Margin
**Source:** Perpetual Futures

The minimum collateral required to keep a position open (usually 50-80% of initial margin):

$$Maintenance Margin = Position Size \times Maintenance Margin Rate$$

**Example:** Position Size: $10,000, Maintenance Margin Rate: 0.5% → Maintenance Margin: $50

**Critical:** If your margin falls below maintenance, you're liquidated.

**Related Terms:** Initial Margin, Margin, Leverage, Liquidation

---

### Margin
**Source:** Perpetual Futures

The collateral you deposit to open and maintain a position:
- **Initial Margin**: Required to open a position (e.g., 10% for 10x leverage)
- **Maintenance Margin**: Minimum required to keep position open (e.g., 5%)
- **Margin Call**: When margin falls below maintenance, position is liquidated

**Example:** Open 10x long BTC with $1,000 margin → Position size: $10,000. If BTC drops 10%, you lose $1,000 (100% of margin). If BTC drops 11%, you're liquidated.

**Related Terms:** Initial Margin, Maintenance Margin, Leverage, Liquidation

---

### Margin Ratio
**Source:** Perpetual Futures

Your current margin relative to position size:

$$Margin Ratio = \frac{Current Margin}{Position Size} \times 100\%$$

**Related Terms:** Margin, Initial Margin, Maintenance Margin

---

### MEV (Maximal Extractable Value)
**Source:** Liquidity Provision

The value that can be extracted from block production in excess of the standard block reward and gas fees. In DeFi, MEV includes front-running, back-running, and arbitrage opportunities.

**Related Terms:** Front-Running, Arbitrage, Gas, Blockchain

---

### Money Market
**Source:** Money Markets

A decentralized protocol that enables users to lend and borrow cryptocurrency assets without intermediaries. Think of it as a peer-to-peer bank that runs 24/7 on blockchain, where you can earn yield on deposits or borrow against your assets using smart contracts.

**Key Innovation:** Instead of trusting a bank, you trust code. Instead of underwriting credit risk, the protocol uses over-collateralization—you must deposit more value than you borrow.

**Related Terms:** Aave, Lending, Borrowing, Over-Collateralization, Health Factor

---

### Monolithic Pool Model
**Source:** Money Markets

A money market architecture where all deposited assets are pooled together into a single, massive liquidity reserve. All lenders share the same pool of liquidity.

**Benefits:**
- Immediate liquidity: Deep, fragmented pools mean instant deposits/withdrawals
- Simple UX: Deposit Asset A, Borrow Asset B—straightforward
- Diversified risk: Large pools can absorb individual defaults

**Systemic Risk:**
- Weakest link problem: If governance votes to accept a risky asset as collateral and that asset crashes, the entire protocol can suffer bad debt
- Socialized losses: All depositors are at risk, even those who never interacted with the risky asset

**Examples:** Aave V3, JustLend, Suilend

**Related Terms:** Modular Market Model, Money Market, Aave

---

## O

### Oracle
**Source:** Beginner DeFi Concepts, Perpetual Futures

A service that provides external data (typically price data) to smart contracts. Smart contracts rely on oracles for price data. If oracles are manipulated, protocols can be exploited.

**Oracle Risk:** The risk that oracle data is incorrect or manipulated, leading to protocol exploits.

**Mitigation:** Protocols using multiple oracles are safer than single-oracle protocols.

**Related Terms:** Oracle Risk, Smart Contract Risk, Price Feed

---

### Oracle Pool
**Source:** Perpetual Futures

A perpetual DEX architecture where traders trade against a unified liquidity pool (not other traders). Prices come from external oracles (Chainlink, Pyth), and trades are executed at oracle price with zero price impact.

**Examples:** GMX V2, Gains Network, Jupiter

**Benefits:**
- Zero slippage (executed at oracle price)
- Simple execution (swap-like interface)
- No need for market makers

**Risks:**
- Oracle latency arbitrage
- Pool insolvency risk
- Limited price discovery

**Related Terms:** CLOB, Perpetual Future, Oracle, Funding Rate

---

### Order Book
**Source:** Liquidity Provision, Perpetual Futures

A list of buy and sell orders at different prices. Traditional exchanges use order books where prices are determined by matching buy and sell orders. In DeFi, AMMs replace order books with liquidity pools.

**Related Terms:** CLOB, AMM, DEX, Market Maker

---

### Over-Collateralization
**Source:** Money Markets, Beginner DeFi Concepts

The requirement that you must deposit collateral worth MORE than the amount you borrow. This is the fundamental security mechanism of DeFi lending, replacing credit checks with mathematical guarantees.

**Example:** You deposit $1,000 worth of ETH, Maximum LTV = 80% → You can borrow up to $800 of USDC. The $200 difference is your safety buffer.

**Why Over-Collateralization?**
- Crypto prices are volatile
- The buffer protects against price drops
- No credit checks needed—the math ensures solvency

**Related Terms:** LTV, Collateral, Health Factor, Money Market

---

### Overconfidence
**Source:** Investor Mindset

A cognitive bias where early DeFi success creates dangerous confidence, leading to excessive risk-taking and position sizing that eventually destroys accounts.

**The Fix:** Keep detailed performance records tracking actual versus perceived skill. Reality is sobering.

**Related Terms:** Cognitive Bias, Risk Tolerance, Fixed Mindset

---

## P

### Perpetual Future (Perp)
**Source:** Perpetual Futures

A derivative contract that allows you to speculate on the price of an asset without an expiration date. Unlike traditional futures that settle on a specific date, perpetuals use a "funding rate" mechanism to keep the contract price aligned with the spot price indefinitely.

**Key Innovation:** Instead of forcing price convergence through expiration, perpetuals use periodic funding payments to incentivize arbitrage and maintain price parity with spot markets.

**Related Terms:** Funding Rate, Margin, Leverage, CLOB, Oracle Pool

---

### Permissionless Access
**Source:** Beginner DeFi Concepts

The property that DeFi protocols are open to anyone. A smart contract does not discriminate based on nationality or credit score; it only checks if the transaction meets the mathematical criteria (e.g., is there enough collateral?).

**Contrast:** TradFi and CeFi require KYC/AML checks and geographic restrictions.

**Related Terms:** DeFi, Smart Contract, CeFi, TradFi

---

### Price Impact
**Source:** Liquidity Provision

The change in price caused by a trade. The larger your trade relative to the pool, the more price impact:

$$\text{Price Impact} = \frac{\Delta x}{x} \times 100\%$$

**Key Insight:** Trade size matters. A $100,000 trade in a $1M pool will have significant impact. A $100 trade in the same pool will have minimal impact.

**Related Terms:** Slippage, Constant Product Formula, Liquidity Pool, AMM

---

### Private Key
**Source:** Beginner DeFi Concepts

The cryptographic key that signs transactions to prove ownership without revealing the key itself. **Never share your private key with anyone.** Whoever has your private key controls your funds.

**Key Point:** The private key is like the key to your mailbox. It proves ownership without revealing the key itself.

**Related Terms:** Public Key, Seed Phrase, Wallet, Self-Custody

---

### Public Key
**Source:** Beginner DeFi Concepts

The wallet address (like `0x742d35Cc6634C0532925a3b844Bc9e7595f0bEb`) that is safe to share publicly—this is where people send you crypto.

**Key Point:** You can share your public address freely. It's how you receive funds.

**Related Terms:** Private Key, Wallet Address, Wallet

---

## R

### Recency Bias
**Source:** Investor Mindset

A cognitive bias where traders believe current market conditions will continue indefinitely, causing them to buy aggressively in bulls and sell desperately in bears.

**The Fix:** Study full crypto cycles (2017, 2018, 2020, 2022) for perspective on how quickly narratives change.

**Related Terms:** Cognitive Bias, Herd Mentality, Confirmation Bias

---

### Risk Tolerance
**Source:** Investor Mindset

Your psychological capacity to handle losses and volatility. Risk tolerance assessment helps identify whether you're a conservative, moderate, or aggressive trader.

**Risk Profile Types:**
- **Conservative traders**: Gravitate toward established protocols like Aave and Compound, prioritizing capital preservation
- **Moderate traders**: Create a balanced mix of blue chips and emerging protocols
- **Aggressive traders**: Chase early protocol adoption and high-APY farming opportunities

**Related Terms:** Cognitive Bias, Fixed Mindset, Growth Mindset

---

### Rollup
**Source:** Beginner DeFi Concepts

A Layer 2 technology that bundles (rolls up) hundreds or thousands of transactions into a single piece of data and posts it to Ethereum. This compresses the data, splitting the L1 gas fee among thousands of users, reducing costs by 10-100x.

**Types:**
1. **Optimistic Rollups**: Assume transactions are valid by default, with a challenge period
2. **ZK-Rollups**: Use advanced cryptography to prove transaction validity instantly

**Related Terms:** Layer 2, Optimistic Rollup, ZK-Rollup, Gas

---

## S

### Scalability
**Source:** Beginner DeFi Concepts

The property that determines how many users can use the network simultaneously and how cheap transactions are. Scalability is one of the three properties in the Blockchain Trilemma (along with Decentralization and Security).

**Trade-off:** Blockchains that prioritize scalability often sacrifice some decentralization or security.

**Related Terms:** Blockchain Trilemma, Layer 2, Rollup, Gas

---

### Seed Phrase
**Source:** Beginner DeFi Concepts

A human-readable backup of your private key, usually 12-24 words. **This phrase IS your wallet.** The hardware or software is merely a window to view the blockchain.

**Critical Understanding:**
- If your device is destroyed but your phrase is saved → funds are safe
- If your phrase is lost → funds are unrecoverable
- If someone sees your phrase → they can steal your funds

**Related Terms:** Private Key, Wallet, Self-Custody, Backup

---

### Self-Custody
**Source:** Beginner DeFi Concepts

The practice of controlling your own private keys and thus your funds. In DeFi, self-custody means you are your own bank. If you lose your private keys, your funds are gone forever.

**Key Principle:** Your keys, your crypto. If you don't control the keys, you don't own the crypto.

**Related Terms:** Custody, Wallet, Private Key, Seed Phrase, Hot Wallet, Cold Wallet

---

### Sidechain
**Source:** Beginner DeFi Concepts

A separate blockchain that runs parallel to a main blockchain (e.g., Polygon PoS). Unlike Layer 2s, sidechains have their own validator sets and can fail independently. They do not inherit the security of the main chain.

**Related Terms:** Layer 2, Rollup, Blockchain, Security Inheritance

---

### Slippage
**Source:** Liquidity Provision

The difference between the expected price of a trade and the actual execution price. Slippage occurs due to price impact—larger trades move prices more.

**Related Terms:** Price Impact, Constant Product Formula, Liquidity Pool, AMM

---

### Smart Contract
**Source:** Beginner DeFi Concepts

Autonomous, self-executing code that hold tokens and execute financial logic (swaps, loans, collateralization) automatically. They eliminate the need for intermediaries by encoding trust into code.

**The Vending Machine Analogy:** A vending machine is a physical smart contract—it holds assets (soda), executes logic (checks payment), and dispenses goods automatically without requiring a clerk.

**Key Principle:** Code is Law. In DeFi, smart contracts execute deterministically. If the code says it will happen, it will happen (bugs notwithstanding).

**Related Terms:** EVM, Gas, DeFi, Atomic Transaction

---

### Smart Contract Risk
**Source:** Beginner DeFi Concepts

The risk that code has bugs or vulnerabilities. Even audited contracts can have vulnerabilities. This is why audits and security are critical.

**Mitigation:** Use well-audited, time-tested protocols. Start with small amounts.

**Related Terms:** Smart Contract, Oracle Risk, Governance Risk, Audit

---

### Stablecoin
**Source:** Beginner DeFi Concepts

A cryptocurrency designed to maintain a stable value, typically pegged to a fiat currency like the US dollar. Stablecoins bridge the gap between volatile cryptocurrencies and a functional financial system.

**Types:**
1. **Fiat-Collateralized** (e.g., USDC, USDT): Centralized, 1:1 backing
2. **Crypto-Collateralized** (e.g., DAI): Decentralized, over-collateralized
3. **Algorithmic**: Risky, prone to failure

**Related Terms:** Stablecoin Trilemma, Fiat-Collateralized Stablecoin, Crypto-Collateralized Stablecoin, Algorithmic Stablecoin

---

### Stablecoin Trilemma
**Source:** Beginner DeFi Concepts

A stablecoin can only optimize for two of three properties—**Decentralization, Stability, and Capital Efficiency**. No stablecoin perfectly achieves all three properties.

**Related Terms:** Stablecoin, Fiat-Collateralized Stablecoin, Crypto-Collateralized Stablecoin, Algorithmic Stablecoin

---

### State Machine
**Source:** Beginner DeFi Concepts

A system that transitions from one state to the next with every block of transactions. The EVM is a state machine: a global computer that transitions from one state to the next with every block.

**Related Terms:** EVM, Blockchain, Smart Contract

---

## T

### Ticks
**Source:** Liquidity Provision

Discrete price points where liquidity can be placed in Uniswap V3. The price at tick i is calculated based on a formula, and liquidity providers can place liquidity at specific tick ranges.

**Related Terms:** Concentrated Liquidity, Uniswap V3, Price Range, Liquidity Pool

---

### Token Approval
**Source:** Beginner DeFi Concepts

The process of granting a smart contract permission to spend your tokens. Before using a DEX or DeFi protocol, you must approve the contract to access your tokens. This is a security feature but can be a risk if you approve malicious contracts.

**Best Practice:** Only approve trusted contracts. Revoke unused approvals regularly.

**Related Terms:** Smart Contract, Wallet, Security, DeFi

---

### Token Standard
**Source:** Beginner DeFi Concepts

A set of rules that define how tokens work on a blockchain. Standards like ERC-20 and ERC-721 ensure "composability"—the ability for different applications to work together.

**Related Terms:** ERC-20, ERC-721, Composability, Smart Contract

---

### TradFi (Traditional Finance)
**Source:** Beginner DeFi Concepts

The traditional financial system including banks, brokers, and centralized institutions. In TradFi, users do not truly own their money; they are creditors to the bank. The bank acts as the custodian, holding the assets on its balance sheet.

**Key Characteristics:**
- **Custody**: Bank holds your funds
- **Permissioned Access**: KYC/AML checks required
- **Opacity**: Balance sheets audited quarterly, not real-time

**Related Terms:** CeFi, DeFi, Custody, Permissioned Access

---

### Trust Paradox
**Source:** Beginner DeFi Concepts

The tension between the efficiency gained by centralization and the systemic fragility introduced by relying on fallible intermediaries. The 2008 financial crisis exposed this paradox—society was forced to trust untrustworthy institutions.

**Related Terms:** Centralization, Decentralization, Trust, Blockchain

---

## U

### Uniswap V3
**Source:** Liquidity Provision

The third version of Uniswap, introducing concentrated liquidity that allows liquidity providers to concentrate their liquidity in a specific price range. This enables up to 4000x capital efficiency for stablecoin pairs compared to V2.

**Key Innovation:** Instead of providing liquidity across the entire price curve (0 to ∞), V3 lets you choose a **price range** [P_min, P_max] where your liquidity is active.

**Related Terms:** Concentrated Liquidity, AMM, Liquidity Pool, Ticks, Fee Tiers

---

### Utilization Rate
**Source:** Money Markets

The percentage of total deposits that are currently borrowed. High utilization rates lead to higher interest rates (encouraging more deposits, discouraging borrowing), while low utilization leads to lower rates.

**Related Terms:** Money Market, Interest Rate Curve, Algorithmic Interest Rates

---

## V

### Virtual AMM (vAMM)
**Source:** Perpetual Futures

A perpetual DEX architecture that uses a virtual liquidity pool (not real assets) to determine prices. Trades are settled against the virtual pool, and positions are netted.

**Related Terms:** Perpetual Future, CLOB, Oracle Pool, AMM

---

## W

### Wallet
**Source:** Beginner DeFi Concepts

A tool for storing and managing cryptocurrency. Wallets don't actually "hold" crypto—they hold private keys that prove ownership of assets on the blockchain.

**Types:**
- **Hot Wallet**: Connected to the internet (e.g., MetaMask, Phantom)
- **Cold Wallet**: Hardware device that keeps private keys air-gapped (e.g., Ledger, Trezor)
- **Smart Contract Wallet**: Emerging technology with features like social recovery

**Key Principle:** Your keys, your crypto. If you don't control the keys, you don't own the crypto.

**Related Terms:** Private Key, Public Key, Seed Phrase, Self-Custody, Hot Wallet, Cold Wallet

---

### Wallet Address
**Source:** Beginner DeFi Concepts

The public identifier for your wallet (like `0x742d35Cc6634C0532925a3b844Bc9e7595f0bEb`). This is safe to share publicly—this is where people send you crypto.

**Related Terms:** Public Key, Wallet, Private Key

---

## Z

### ZK-Rollup (Zero-Knowledge Rollup)
**Source:** Beginner DeFi Concepts

A Layer 2 solution that uses advanced cryptography (Validity Proofs, e.g., zk-SNARKs) to prove transaction validity instantly. The rollup generates a complex mathematical proof that verifies the correctness of the entire batch before it is posted to Ethereum. The L1 contract verifies the proof. If the proof is valid, the transactions are final immediately.

**Analogy:** An impregnable mathematical seal of approval that requires no "challenge period" because the math cannot lie.

**Examples:** zkSync, Starknet

**Related Terms:** Rollup, Optimistic Rollup, Layer 2, Validity Proof

---

## Mathematical Formulas Reference

### Constant Product Formula
$$x \cdot y = k$$

### Health Factor
$$Health Factor = \frac{Collateral Value \times Liquidation Threshold}{Total Debt}$$

### Funding Rate
$$Funding Rate = \frac{Perpetual Price - Spot Price}{Spot Price} \times Adjustment Factor$$

### Initial Margin
$$Initial Margin = \frac{Position Size}{Leverage}$$

### Maintenance Margin
$$Maintenance Margin = Position Size \times Maintenance Margin Rate$$

### Margin Ratio
$$Margin Ratio = \frac{Current Margin}{Position Size} \times 100\%$$

### Price Impact
$$\text{Price Impact} = \frac{\Delta x}{x} \times 100\%$$

---

## Course-Specific Term Index

### Beginner DeFi Concepts
- Blockchain Trilemma, Layer 0/1/2, EVM, Gas, Smart Contract, ERC-20, ERC-721, Wallet, Self-Custody, DeFi, TradFi, CeFi, AMM, DEX, Money Market, Stablecoin, Flash Loan, Oracle Risk, Governance Risk, Liquidation Risk, Impermanent Loss, Rollup, ZK-Rollup, Optimistic Rollup

### Liquidity Provision
- AMM, Constant Product Formula, Liquidity Pool, Liquidity Provider, Impermanent Loss, Price Impact, Slippage, Concentrated Liquidity, Ticks, Fee Tiers, Uniswap V3, MEV, Arbitrage

### Money Markets
- Money Market, Over-Collateralization, LTV, Liquidation Threshold, Health Factor, Utilization Rate, Interest Rate Curve, Algorithmic Interest Rates, Aave, Isolation Mode, E-Mode, Monolithic Pool Model, Modular Market Model, Hub-and-Spoke Architecture

### Perpetual Futures
- Perpetual Future, Funding Rate, Margin, Initial Margin, Maintenance Margin, Leverage, CLOB, Oracle Pool, Virtual AMM, AppChain, Liquidation

### Investor Mindset
- Fixed Mindset, Growth Mindset, Risk Tolerance, Cognitive Bias, Confirmation Bias, FOMO, Loss Aversion, Anchoring Bias, Herd Mentality, Overconfidence, Recency Bias, Disposition Effect

---

**Last Updated:** 2025-01-27

**Note:** This glossary is compiled from the DeFi University course materials. Definitions are extracted directly from the lessons to maintain accuracy and consistency with the course content.

