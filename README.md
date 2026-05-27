# Available .BROKER One-Word Domains (10,013)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C013%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .broker one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,013 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,013 domains · **Median ask:** $70.11 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-27  
**Canonical page:** `https://unique.domains/domains/tld/broker`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/broker?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./broker.csv">CSV</a> / <a href="./broker.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BROKER search](https://unique.domains/domains/tld/broker?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BROKER search](https://unique.domains/domains/tld/broker?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BROKER one-word domain catalog.

### Files

- `broker.csv` — public CSV extract (1,000 rows)
- `broker.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/broker-oneword-domains/main/broker.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain                | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| --------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| movies.broker         | available | $19.99    | —             | 80             | 28     | 6      | name.com    |
| carrie.broker         | available | $19.99    | —             | 82             | 10     | 6      | name.com    |
| getup.broker          | available | $19.99    | —             | 82             | 15     | 6      | name.com    |
| lyrics.broker         | available | $19.99    | —             | 90             | 20     | 6      | name.com    |
| Keys.broker           | available | $47.98    | —             | 66             | 46     | 4      | namecheap   |
| david.broker          | resell    | —         | —             | 74             | 47     | 5      | Dynadot Inc |
| stockmarket.broker    | premium   | $6,250    | —             | 80             | 29     | 12     | name.com    |
| its.broker            | available | $19.99    | —             | 78             | 42     | 3      | name.com    |
| hey.broker            | resell    | —         | —             | 68             | 45     | 3      | Dynadot Inc |
| shares.broker         | premium   | $6,250    | —             | 58             | 18     | 6      | name.com    |
| Flowers.broker        | available | $47.98    | —             | 72             | 40     | 7      | namecheap   |
| budget.broker         | resell    | —         | —             | 72             | 29     | 6      | Dynadot Inc |
| AOL.broker            | premium   | —         | —             | 76             | 17     | 3      | —           |
| justin.broker         | available | $19.99    | —             | 58             | 38     | 7      | name.com    |
| AnnaKournikova.broker | premium   | —         | —             | 72             | 1      | 15     | —           |
| Greg.broker           | available | $47.98    | —             | 66             | 34     | 4      | namecheap   |
| hashtag.broker        | available | $19.99    | —             | 82             | 32     | 7      | name.com    |
| teams.broker          | available | $19.99    | —             | 62             | 32     | 5      | name.com    |
| William.broker        | available | $47.98    | —             | 74             | 31     | 7      | namecheap   |
| partners.broker       | available | $19.99    | —             | 61             | 31     | 8      | name.com    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,013 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/broker?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/broker?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is entirely made up of one-word .broker domains. The naming patterns range from first names like Liam.broker, Cindy.broker, Laura.broker, and girls.broker to generic terms such as feet.broker, WiFi.broker, LGBTQ.broker, and emoji.broker. That makes the selection broad, but also uneven in commercial fit. For investors, the main question is whether a term has credible buyer depth inside broker-led categories. For founders, the decision is simpler: choose a name that is easy to say, easy to remember, and clearly compatible with a brokerage, intermediary, or advisory positioning. Median ask is 70.28, which keeps price comparison straightforward across a large pool.

- All results use the .broker extension
- One-word names span people, terms, and niche concepts
- Median ask across this selection is 70.28
- Favor clear brokerage relevance over novelty

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BROKER One-Word Domains*. Version 2026-05-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BROKER page](https://unique.domains/domains/tld/broker?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
