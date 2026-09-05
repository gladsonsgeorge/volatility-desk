# Volatility Desk

Daily volatility scans of the **S&P 500, Nasdaq-100 and liquid ETFs** — the names
moving hardest on news and earnings.

### 👉 [Open the scans](https://gladsonsgeorge.github.io/volatility-desk/)

Three scans, refreshed every weekday:

| Scan | When | What it answers |
|---|---|---|
| **Pre-market gaps** | ~08:15 ET | What dislocated overnight, on volume, with a catalyst behind it? |
| **Swing** | ~16:45 ET | Which names have started moving more than their own baseline? |
| **Earnings** | ~16:45 ET | Who reports soon, and how hard does this name usually move on a print? |

## About this repository

This repo holds **published output only** — the rendered page and a dated archive
of each day. It is written automatically; nothing here is edited by hand.

The scanner that produces it lives in a separate private repository. Only the
finished page is copied across, which is what allows free GitHub Pages hosting
without publishing the code.

## Reading it

Scores are **percentile ranks within a single scan** — a 90 means top-decile on
that day's inputs. Not a probability, and never a direction. Blue is up, red is
down, and every signed number carries its sign, so colour never does the work
alone.

A backtest over 67 weekly as-of dates found ranked names went on to move
**1.86× the universe** over the next session. That is volatility clustering
working as advertised — volatile periods tend to persist — not a trading edge.

---

**This is a research tool, not financial advice.** It ranks instruments by how
much they have been moving and whether a dated catalyst is nearby. It does not
know whether a move is over, does not predict direction, and knows nothing about
your position sizing, spreads, borrow costs or risk tolerance. Data comes from
free public feeds and can be wrong, stale or missing — verify anything you intend
to act on against your broker before trading.
