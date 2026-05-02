# Amazon Listing Grader

A Claude-powered tool that scores Amazon product listings on conversion factors — built in one hour as a demo for Pixii.

## What it does

Paste any Amazon listing copy (title + bullet points). The tool instantly returns:

- **Overall score** (0–100) with a letter grade
- **6 conversion metrics** — title strength, bullet quality, keyword density, benefit clarity, character count, mobile readability
- **Keyword analysis** — what's present vs what's missing
- **Priority fixes** — ranked, specific, actionable
- **A Pixii pitch** — one line on how Pixii's AI design layer would solve this visually in 2 minutes

## Why I built this

I came across the Pixii Founding Engineer (Growth) role and wanted to show I'm a builder, not just an applicant.

Pixii's value proposition is clear: an agency charges $5,000 and takes 9 weeks. Pixii does it in 2 minutes for free. Before I could help take that message to 1 million people a month, I needed to understand the problem from the ground up — what makes a listing bad, what sellers actually struggle with, and why the visual gap matters.

So I built the grader. It surfaces exactly the kind of problems Pixii fixes — weak titles, missing keywords, bullets that list features instead of selling benefits — without the design layer that makes Pixii's output actually convert.

That gap between analysis and execution is Pixii's entire moat. I get it now.

## Tech

- Vanilla HTML/CSS/JS — no framework, no build step, just open in browser
- Claude Sonnet API (`claude-sonnet-4-20250514`) for listing analysis
- Structured JSON output parsed and rendered client-side

## How to run

1. Clone or download the repo
2. Open `pixii_listing_analyzer.html` in any browser
3. Paste an Amazon listing and hit **Grade Listing →**

No server. No setup. No dependencies.

## What I'd build next

If this were a real Pixii growth tool:

- Bulk analyzer — paste 100 ASINs, get a CSV of scores and fixes
- Competitor comparison — grade your listing vs the top 3 results for a keyword
- Before/after tracker — re-grade after Pixii redesigns and show the delta
- Shareable score cards — viral content for Amazon seller communities

---

Built by [Shikha Bansal](https://linkedin.com/in/shikhabansal7) · Made for [Pixii](https://pixii.ai)
