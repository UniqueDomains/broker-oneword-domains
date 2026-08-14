# Available .BROKER One-Word Domains (15,120)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C120%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .broker one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,120 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,120 domains · **Median ask:** $52.43 · **High-demand under $2,500:** 2

**Last updated:** 2026-08-14
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

- `broker.csv`, public CSV extract (1,000 rows)
- `broker.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/broker-oneword-domains/main/broker.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                      |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------ |
| ada.broker       | available | $19.99    | —             | medium         | medium | 3      | name.com                       |
| one.broker       | resell    | —         | —             | high           | medium | 3      | NameCheap, Inc.                |
| lp.broker        | premium   | $1,250    | —             | medium         | low    | 3      | name.com                       |
| ale.broker       | available | $19.99    | —             | medium         | low    | 3      | name.com                       |
| zen.broker       | resell    | —         | —             | high           | medium | 3      | Sav.com, LLC                   |
| mad.broker       | premium   | $1,250    | —             | medium         | medium | 3      | name.com                       |
| Ann.broker       | available | $19.99    | —             | high           | low    | 3      | name.com                       |
| great.broker     | resell    | —         | —             | high           | low    | 5      | Spaceship, Inc.                |
| org.broker       | premium   | $3,125    | —             | medium         | medium | 3      | name.com                       |
| any.broker       | available | $19.99    | —             | high           | medium | 3      | name.com                       |
| design.broker    | resell    | —         | —             | high           | medium | 6      | Soluciones Corporativas IP, SL |
| fair.broker      | premium   | $3,125    | —             | high           | low    | 4      | name.com                       |
| ate.broker       | available | $19.99    | —             | high           | low    | 3      | name.com                       |
| anything.broker  | resell    | —         | —             | medium         | low    | 8      | NameCheap, Inc.                |
| land.broker      | premium   | $6,250    | —             | medium         | low    | 4      | name.com                       |
| atp.broker       | available | $19.99    | —             | medium         | low    | 3      | name.com                       |
| nashville.broker | resell    | —         | —             | high           | low    | 9      | Dynadot Inc                    |
| blink.broker     | premium   | $3,125    | —             | high           | medium | 5      | name.com                       |
| awe.broker       | available | $19.99    | —             | high           | low    | 3      | name.com                       |
| house.broker     | premium   | $6,250    | —             | high           | medium | 5      | name.com                       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,120 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/broker?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/broker?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection covers one-word .broker domain names such as coffeemilk.broker, hellothere.broker, and lordoftherings.broker. Most of these 11,397 domains are priced under $500, with a median ask of $62.84, making the category accessible for both quick acquisition and longer-term evaluation. A small number of listings — including marketplace.broker and room.broker — show large gaps between current ask price and reference value, which is useful context when comparing options. The set spans modern, elegant, and playful naming styles, giving founders a range of brandable choices and investors a broad base for spotting mispriced listings.

- 11,397 available one-word .broker domains, updated daily
- Median ask of $62.84; most listings under $500
- 116 premium and 94 resell domains within this set
- Standout picks like marketplace.broker show high reference value

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BROKER One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BROKER page](https://unique.domains/domains/tld/broker?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_broker_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
