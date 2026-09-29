# 07 — BR RESEARCH PROTOCOL
## Banana Republic Intelligence OS
### Version 5.0 | September 2026

---

## CHANGE LOG
- v4.0: Six-question framework, priority scoring, event state tracking
- v5.0: Hard Data Layer added (Step 1B). Market Scan expanded with four new categories: Global Central Banks, Labor Market Internals, Credit Markets, Financial Conditions/Repo Stress. MOVE Index added. Four new mechanisms added to Library. Elite threshold defined. Hard limits on positioning claims formalized.

---

## THE GOVERNING PRINCIPLE

BR's authority rests on one thing: when it speaks, it has already done the work.

One wrong causal claim does more damage than a hundred correct posts can repair.

**Precision means:** a specific number, from a named primary source, tied to a named mechanism, that a reader could verify themselves.

"The market feels worried about demand" is not precise.
"Indirect bidder participation in the last auction fell to X% — the softest stretch since [period]" is precise.

**If the mechanism cannot be verified from primary sources — mark HOLD. Do not post.**

---

## STEP 1 — THE MARKET SCAN

Every BR session begins with a full scan across all input categories.
Compare to the previous scan. Only flag what materially changed.

```
MARKET PRICES:
S&P 500 / Nasdaq / Russell 2000: [level, % change, vs previous scan]
VIX: [level, direction — rising/falling]
Bitcoin: [price, % change]

BOND MARKET:
2Y Treasury: [yield, change in bps]
10Y Treasury: [yield, change in bps]
30Y Treasury: [yield, change in bps]
Yield curve: [steepening/flattening/inverted]
MOVE Index (bond volatility): [level, direction]
  → Cross-reference MOVE vs VIX — divergence is a signal

CURRENCY AND COMMODITIES:
DXY: [level, % change]
Oil (Brent + WTI): [price, % change]
Gold: [price, % change]
Copper: [price, % change]

SECTORS:
Best performing: [sector, %]
Worst performing: [sector, %]
Notable rotation: [from → to]

MAJOR STOCKS AND CORPORATE EVENTS:
Notable movers: [stock, %, context vs previous scan]
Earnings surprises: [company, beat/miss, guidance direction]
Insider activity: [Form 4 filings — company, buy/sell, size]
Unusual volume: [any notable]

MACRO AND POLICY EVENTS:
Fed speakers: [who, tone — hawkish/dovish/neutral]
Data releases: [CPI, PPI, jobs, GDP, retail sales — reading vs expectation, vs prior]
Treasury auctions: [bid-to-cover, indirect bidder %, yield vs expectations]

GLOBAL CENTRAL BANKS [NEW]:
BOJ policy stance or surprise moves: [note if yen carry is in play]
ECB policy stance or moves: [note if euro/rates diverging from Fed]
Other major central bank actions: [flag if pulling global yields or currencies]
  → Flag policy divergence explicitly — this is a named mechanism:
    Central Bank Policy Divergence

LABOR MARKET INTERNALS [NEW]:
JOLTS quits rate: [level, direction]
Continuing claims: [level, w/w change]
Labor force participation rate: [level, direction]
  → Check these even in weeks without headline payrolls — they often lead

CREDIT MARKETS [NEW]:
Investment grade (IG) spreads: [level, direction, w/w change]
High yield (HY) spreads: [level, direction, w/w change]
  → Flag divergence: spreads widening while equities stay calm is an early
    signal equities haven't priced yet — this is Credit Spread Divergence

FINANCIAL CONDITIONS / REPO STRESS [NEW]:
SOFR-EFFR spread: [level, any stress reading]
Financial conditions index: [level, direction]
  → Plumbing-level indicator — often leads the 10-year and equities

CHINA / GLOBAL GROWTH [NEW]:
China PMI: [reading, vs expectation]
Chinese refiner demand signals: [if relevant to oil mechanism]
Other major economy data with cross-asset relevance: [flag only if material]

SENTIMENT AND POSITIONING:
Put/Call ratio: [level, direction]
Crypto flows: [notable institutional or exchange movements]
ETF flows (aggregate only — see Tier 2 exclusions): [notable sector in/out]

SHIPPING / AIS [Tier 1 — directional only]:
Major route disruption or normalization signals: [directional only]
  → Never state a precise daily AIS figure unless source is confirmed same-day
  → Treat as supporting color, not a headline number
```

---

## STEP 1B — HARD DATA LAYER

BR's inputs now split into two explicit layers:

### NARRATIVE/CONTEXT LAYER (existing)
Fed speakers, policy, geopolitics, sentiment, price action, headlines.
These have always been BR's foundation. Continue as before.

### HARD DATA LAYER (new — public, free, pulled live each scan)

For the dominant story of each scan, check whether a structural data point from these sources adds evidence beyond the narrative layer:

| Source | What to pull | When it earns its place |
|---|---|---|
| **CFTC COT** (Fridays, weekly lag) | Net positioning by Leveraged Funds / Asset Managers, w/w change — for the asset central to the dominant story (oil, gold, S&P futures, Treasury futures, Bitcoin futures) | When positioning explains or contradicts price action |
| **FRED** | RRP balance (RRPONTSYD), Treasury General Account (WTGACN), 2s10s spread | Only when liquidity is the mechanism in play |
| **Treasury auctions/buybacks** | Bid-to-cover, indirect/direct bidder %, exact buyback operation size | When bond-market plumbing is the mechanism — cite the actual number, not a paraphrase |
| **Fed Nowcasts** | Atlanta Fed GDPNow delta, NY Fed Staff Nowcast — current quarter estimate vs prior update | When growth expectations are being repriced |
| **SEC filings** | Form 4 (insider buy/sell, filed within 2 business days), 13F (institutional holdings, 45-day lag), 8-K (material events) | Cite the actual filing language/numbers, not a secondhand paraphrase |
| **Shipping/AIS** | Directional supply signals — route disruption or normalization | Directional color only — never a precise daily figure without same-day confirmed source |

### HARD DATA RULES

**A hard data point earns its place only if it changes or confirms the MECHANISM — not as decoration.**

If a COT report shows leveraged funds were net reducing duration exposure before a major Treasury yield move — that's corroboration. Fold it into REVEAL as: "the Norway headline landed on top of something already visible in the data."

If no hard data point is available or verifiable — proceed on narrative sourcing. Do not force one in. Do not imply verification that did not happen.

**The open loop should point at something partially verifiable now**, not purely at a future event to watch cold. "Watch September's auction: indirect bidder % against the recent trend line" is better than "watch if the auction goes well."

### TIER 2 — EXCLUDED UNTIL FUNDED

**Never cite without a live paid feed:**
- Options flow
- Dark pool prints
- Dealer gamma / gamma walls
- Granular fund-by-fund ETF flows

If a story's mechanism depends on one of these — mark HOLD. A single fabricated or overstated positioning claim breaks the Research Protocol's core rule and undoes the credibility the entire brand is built on. This is gated on budget — Phase 2.

### ELITE THRESHOLD

**Priority candidate (score 18+):** needs 1+ verified hard data point supporting the mechanism

**Newsletter flagship pieces:** need 2+ corroborating hard data points from DIFFERENT layers
(COT + Treasury, or FRED + 13F — not two COT references)

---

## STEP 2 — IDENTIFY CANDIDATES

From the scan, identify events that potentially reveal a mechanism.

Apply the primary filter question:

> **Does this event reveal a mechanism worth teaching?**

For each candidate, run the six-question framework:

```
EVENT: What happened?
CONTRADICTION: Why is the obvious interpretation incomplete, surprising, or wrong?
MECHANISM: What actually caused the market reaction?
EVIDENCE: What proves or strongly supports that mechanism — including any Tier 1 hard data?
IMPLICATION: What does this reveal about how the market is functioning?
SIGNAL: What should we watch to determine whether the mechanism continues?
  → Prefer a signal partially verifiable now over one that is purely future
```

---

## STEP 3 — VERIFY THE MECHANISM

**Tier 1 primary sources (all public, all free):**

- Federal Reserve: fed.gov, FOMC statements, official speaker transcripts
- BLS: bls.gov — CPI, PPI, jobs reports
- BEA: bea.gov — GDP, PCE
- CFTC: cftc.gov — COT reports (published Fridays for prior Tuesday data)
- SEC EDGAR: sec.gov — Form 4, 13F, 8-K filings
- Treasury: treasurydirect.gov — auction results, buyback operations
- FRED: fred.stlouisfed.org — RRP, TGA, 2s10s, financial conditions data
- Atlanta Fed: GDPNow (gdpnow.atlantafed.org)
- NY Fed: Staff Nowcast (newyorkfed.org)
- Company investor relations pages — official earnings releases, transcripts
- Bloomberg, Reuters, FT, WSJ — for reported facts with named sources

**Verification rules:**
- Causation stated only where evidence supports it — correlation stated separately
- Chain links documented, not assumed
- Statistics in correct context — not annual as quarterly, not global as US-specific
- Hard data citations include the source and date
- Institutional flow claims require reported evidence — never inferred
- Fabricating prices, flows, filings, or causal claims is a filter failure

**When evidence is mixed:**
Acknowledge it. "The move combined X and Y, with Z amplifying — the dominant driver is contested" is more credible than forcing a clean single-cause narrative.

**When evidence is insufficient:**
Mark HOLD. State specifically what evidence would make it publishable.

---

## STEP 4 — SCORE THE CANDIDATE

| Dimension | Score | Question |
|---|---|---|
| Causal Clarity | /5 | Can we explain why it moved with supported evidence? |
| Contradiction | /5 | Meaningful gap between headline and actual reaction? |
| Investor Usefulness | /5 | Can reader use this framework again? |
| Distribution Potential | /5 | Natural curiosity, discussion, or visual interest? |
| Timeliness | /5 | Relevant now? |
| **TOTAL** | **/25** | |

**18+ = Strong candidate — proceed**
**21+ = Priority**
**24-25 = Exceptional**
**Below 18 = HOLD or REJECT**

---

## STEP 5 — ASSIGN EVENT STATE

**WATCHING** — Potential, insufficient evidence
**DEVELOPING** — Evidence accumulating, not ready
**POSTED** — BR explained this mechanism
**UPDATED** — Material change after publication — eligible for follow-up
**CLOSED** — No longer developing

A POSTED story only returns as UPDATED when something material changed — new data, new filing, new price action that confirms or contradicts the mechanism. A repeated headline without new evidence is not a new post.

---

## STEP 6 — CONTINUITY CHECK

Before drafting:

- Does this post reference a prior open loop where relevant?
- If a prior scan asked readers to "watch X" — and X has now moved — open with that before introducing new evidence
- If the current event is the fourth instance of a documented mechanism — say so: "We've seen this setup before. Here's what's different this time."

The archive compounds. Use it.

---

## STEP 7 — MECHANISM LIBRARY CHECK

Check against the full Mechanism Library (Constitution, Section 2):

- Does this event connect to a named mechanism?
- Is there a historical parallel in the Market Memory?
- Has BR posted on the same mechanism today without new evidence? (HOLD if yes)
- Can the mechanism be named precisely?

**New mechanisms added in v5.0:**
- Central Bank Policy Divergence
- Credit Spread Divergence
- Repo Stress
- Labor Market Leading Indicators

---

## STEP 8 — RESEARCH OUTPUT BRIEF

```
DATE AND SCAN NUMBER:
DOMINANT STORY: [one sentence]
STORY FORM: [1-7]
EVENT STATE: [WATCHING/DEVELOPING/POSTED/UPDATED/CLOSED]

SIX-QUESTION FRAMEWORK:
EVENT: [what happened]
CONTRADICTION: [why obvious reading is wrong/incomplete]
MECHANISM: [what actually caused the move — named precisely]
EVIDENCE: [what supports the mechanism — narrative + hard data]
IMPLICATION: [what this reveals about market functioning]
SIGNAL: [what to watch — specific, observable, partially verifiable now]

MECHANISM LIBRARY MATCH: [name]
HISTORICAL PARALLEL: [if any — from Market Memory]
PRIOR BR OPEN LOOP: [if this post resolves or develops a prior signal]
PRIORITY SCORE: [X/25]
ELITE STATUS: [1+ hard data point? Y/N] [2+ from different layers? Y/N]
EMOTIONAL ENGINE: [Fear/Pride/Shame/Recognition/Hope]
VISUAL RECOMMENDATION: [Text/Diagram/Chart/Screenshot/Silent Video]
UNCERTAINTY FLAGS: [anything mixed or unconfirmed]

VERIFIED FACTS:
- [Fact 1] — Source: [primary source], Date: [x]
- [Fact 2] — Source: [primary source], Date: [x]
- [Hard Data Point if applicable] — Source: [COT/FRED/Treasury/Nowcast/AIS/SEC], Date: [x]
```

---

*Version 5.0. The governing research standard for all BR content.*
