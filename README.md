## Foreign Exchange Hedging Recommendation – €4.5M European Receivable

**Created by:** [Mia Umeda]  
**Updated by:** [Mia Umeda]  
**Date Created:** [October 23, 2025]  
**Date Updated:** [October 23, 2025] 
**Version:** 1.0  
**LLM Used:** Claude Sonnet 4

---

## Executive Summary

Our firm faces foreign exchange exposure on a €4,500,000 receivable due in one year from our European solar equipment contract. At today's spot rate (1.1607 USD/EUR), this represents $5,223,150, but the forward market prices EUR at 1.0875, suggesting a potential $329,400 loss. I recommend implementing a forward contract hedge to eliminate this risk and ensure predictable cash flows.

## Background & Objectives

We will receive €4,500,000 in twelve months from our European customer. As a U.S. company operating in USD, exchange rate fluctuations create significant uncertainty. The current environment presents structural headwinds: the Fed maintains rates at 4.25% while the ECB rate sits at 2.15%, creating a 210-basis-point differential favoring USD strength. 

In a worst-case scenario where EUR falls to 1.05, we could lose nearly $500,000 in value—representing 9.5% erosion of expected proceeds. This unhedged exposure creates earnings volatility that complicates financial guidance and may concern investors. Our objective is to eliminate FX risk and protect profit margins while maintaining cost-effective hedging.

## Methods

I evaluated three hedging strategies using current market data:

**Forward Contract:** Lock in 1.0875 rate, guaranteeing $4,893,750. *Pros:* Zero upfront cost, complete certainty. *Cons:* No upside if EUR strengthens.

**Put Option:** Strike at 1.1607 with $67,500 premium, guaranteeing minimum $5,155,650 net. *Pros:* Downside protection with upside potential. *Cons:* Significant premium cost.

**Money Market Hedge:** Borrow €4.4M at 2.15%, convert at spot, invest at 3.55%. Projects $5,295,158. *Pros:* Best economics. *Cons:* High complexity, uses credit lines.

## Limitations & Next Steps

**Limitations:** Forward rate assumes stable conditions; execution may vary ±20 bps. No flexibility if payment timing changes.

**Technical Specification:** Excel model requirements: Inputs (EUR receivable, spot rate, forward rate, USD/EUR interest rates, option premium/strike, time period). Outputs (USD proceeds per strategy, net cost comparison, break-even analysis). Include sensitivity table showing proceeds across EUR scenarios (1.00-1.20 range).

**Recommendation:** Forward contract optimal for zero-cost certainty.

**Next Steps:** Treasury to secure CFO approval (Oct 25), obtain bank quotes (Oct 28), execute forward (Oct 30), and build Excel model for future decisions.

---

## References

Bloomberg Terminal. (2025, October 23). *EURUSD spot and forward rates*. Bloomberg L.P.

Board of Governors of the Federal Reserve System. (2025, October 23). *Federal funds rate*. https://www.federalreserve.gov

European Central Bank. (2025, October 23). *Key ECB interest rates*. https://www.ecb.europa.eu

U.S. Department of the Treasury. (2025, October 23). *Daily Treasury par yield curve rates*. https://home.treasury.gov

Yahoo Finance. (2025, October 23). *EUR/USD exchange rate*. https://finance.yahoo.com

---

**Word Count:** 392 words
