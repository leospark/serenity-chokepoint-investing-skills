# Serenity Chokepoint Investing Skill

A Hermes / OpenClaw compatible research skill for analyzing public equities through the lens of AI infrastructure supply-chain chokepoints.

This skill is inspired by the Serenity-style investment framework: instead of simply buying obvious AI leaders, it focuses on identifying hidden bottlenecks across the AI industrial supply chain.

The core idea:

Find the real bottleneck first.
Find the listed company exposure second.
Verify through evidence third.
Size the position according to win rate, payoff, valuation, and risk.

---

## What This Skill Does

This skill helps an agent analyze companies and sectors by asking:

* Is this company truly exposed to AI infrastructure growth?
* Which part of the AI supply chain does it belong to?
* Is this a real bottleneck or just an AI narrative?
* Is supply constrained?
* Is capacity expansion slow?
* Is customer qualification difficult?
* Are there real orders, backlog, RPO, billings, or customer wins?
* Is the financial impact already visible?
* Has the market already priced in the thesis?
* Is this a high-win-rate opportunity or a high-payoff speculative bet?
* What portfolio role should this idea play?

It is designed for public equity research, sector analysis, and AI supply-chain due diligence.

---

## Best Use Cases

This skill is especially useful for analyzing:

* AI infrastructure
* Semiconductors
* HBM / DRAM / NAND
* Enterprise storage
* Advanced packaging
* Optical modules
* Silicon photonics
* CPO
* InP / GaAs / SOI substrates
* Lasers and external light sources
* Semiconductor testing equipment
* Data center power
* Transformers, UPS, switchgear, gas turbines
* Liquid cooling
* AI data centers
* Neocloud / GPU cloud
* Bitcoin miners converting to AI/HPC data centers
* Robotics supply chain
* High-volatility small-cap AI supply-chain stocks

---

## Core Framework

The skill follows this workflow:

1. Identify the supertrend.
2. Map the supply-chain position.
3. Score the chokepoint quality.
4. Analyze company positioning and competitors.
5. Validate orders, customers, and financials.
6. Assess valuation and market crowding.
7. Build the bear case.
8. Classify win rate and payoff.
9. Assign portfolio role and position size range.
10. Define key tracking indicators.

---

## Chokepoint Scoring

The skill scores each idea using 10 bottleneck questions:

1. Is demand structurally growing?
2. Is supply limited?
3. Is capacity expansion slow?
4. Are technical barriers high?
5. Is customer qualification difficult?
6. Are substitute technologies limited?
7. Are supplier options limited?
8. Does this product affect system-level delivery?
9. Are customers willing to pay for reliable supply?
10. Is the market still underestimating this node?

Each question is scored from 0 to 2.

Total score: 20 points.

Classification:

* 16–20: Strong chokepoint
* 12–15: Medium chokepoint
* 8–11: Weak chokepoint
* 0–7: Not a real chokepoint

---

## Evidence Levels

The skill separates narrative from evidence.

Evidence Level A: Financially Verified
The thesis is visible in revenue, backlog, RPO, billings, margin, operating income, or cash flow.

Evidence Level B: Order / Customer Verified
There are confirmed orders, customer contracts, qualification wins, supply agreements, or named customer relationships.

Evidence Level C: Management / Industry Supported
The thesis is supported by management commentary, industry reports, or credible supply-chain checks, but customer orders or revenue remain unclear.

Evidence Level D: Narrative Only
The thesis is mainly supported by KOL discussion, social media, or conceptual linkage.

KOL posts can generate ideas, but they are not treated as evidence.

---

## Opportunity Classification

The skill classifies each company into one of four categories:

Category A: High Win Rate, Low Payoff
Strong validation, strong company quality, but already recognized by the market.

Category B: Medium-High Win Rate, Medium-High Payoff
Clear industry logic, early validation, not fully priced, and reasonable upside.

Category C: Low Win Rate, High Payoff
Exciting thesis, small market cap, large upside, but uncertain orders, technology, or financing.

Category D: Low Win Rate, Low Payoff
Weak evidence, crowded narrative, high valuation, poor financials, or high dilution risk.

---

## Portfolio Role

The skill does not treat every AI idea as a core holding.

Each idea is assigned a portfolio role:

* Core compounder
* Thematic growth position
* Chokepoint basket candidate
* High-volatility option
* Watchlist only
* Avoid

Suggested sizing framework:

* Core compounder: 10%–20%
* Thematic growth position: 5%–10%
* Chokepoint basket candidate: 2%–5%
* High-volatility option: 0.5%–3%
* Watchlist only: 0%
* Avoid: 0%

These are framework ranges, not financial advice.

---

## Standard Output Structure

When used by an agent, the analysis should follow this structure:

1. One-Sentence Conclusion
2. Company / Sector Positioning
3. Supertrend Assessment
4. Supply-Chain Layer
5. Chokepoint Score
6. Competitive Position
7. Evidence Level
8. Order and Financial Validation
9. Market Pricing and Crowding
10. Bear Case
11. Win Rate / Payoff Classification
12. Portfolio Role
13. Position Size Range
14. Tracking Indicators

Final output should be written in Chinese unless the user requests English.

---

## Example Prompt

Use the Serenity Chokepoint Investing Framework to analyze the following company or sector. Do not give a direct buy or sell recommendation. First identify the supertrend, supply-chain position, chokepoint quality, order validation, financial validation, valuation, crowding risk, bear case, win-rate/payoff category, portfolio role, position sizing range, and key tracking indicators. Final output should be in Chinese.

---

## Recommended Repository Structure

Minimal version:

serenity-chokepoint-investing/

* SKILL.md

Recommended GitHub version:

serenity-chokepoint-investing-skill/

* README.md
* LICENSE
* serenity-chokepoint-investing/

  * SKILL.md
* examples/

  * example-ntap.md
  * example-sive.md
  * example-psix.md

---

## Installation

Clone this repository:

git clone https://github.com/your-username/serenity-chokepoint-investing-skill.git

Then copy the skill folder into your Hermes or OpenClaw skills directory:

serenity-chokepoint-investing/

Make sure the folder contains:

SKILL.md

---

## Safety Notes

This skill contains no executable code.

It does not:

* Request API keys
* Access wallets
* Access browsers
* Access local credentials
* Execute shell commands
* Modify files
* Connect to brokerage accounts

It is a text-based research workflow skill only.

---

## Disclaimer

This skill is for educational and research workflow purposes only.

It does not provide financial advice, investment recommendations, or personalized portfolio management.

All outputs should be treated as research assistance, not buy or sell instructions.

Investing involves risk, including the possible loss of principal. Always do your own due diligence.
