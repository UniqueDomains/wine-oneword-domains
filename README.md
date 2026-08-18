# Available .WINE One-Word Domains (16,127)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C127%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .wine one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,127 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,127 domains · **Median ask:** $16.66 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-18
**Canonical page:** `https://unique.domains/domains/tld/wine`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/wine?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./wine.csv">CSV</a> / <a href="./wine.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .WINE search](https://unique.domains/domains/tld/wine?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .WINE search](https://unique.domains/domains/tld/wine?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .WINE one-word domain catalog.

### Files

- `wine.csv`, public CSV extract (1,000 rows)
- `wine.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/wine-oneword-domains/main/wine.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| away.wine    | available | $9.99     | —             | high           | low    | 4      | name.com                                                  |
| special.wine | premium   | $500      | —             | high           | low    | 7      | name.com                                                  |
| cut.wine     | available | $9.99     | $77.99        | high           | low    | 3      | name.com                                                  |
| aft.wine     | available | $8.48     | $75.98        | low            | low    | 3      | namecheap                                                 |
| gas.wine     | resell    | $75.98    | —             | high           | low    | 3      | HOSTINGER operations, UAB                                 |
| org.wine     | premium   | $500      | —             | medium         | medium | 3      | name.com                                                  |
| apt.wine     | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| bio.wine     | resell    | —         | —             | high           | medium | 3      | Name.com, Inc.                                            |
| gold.wine    | premium   | $520      | $520          | high           | medium | 4      | namecheap                                                 |
| awe.wine     | available | $9.99     | —             | high           | low    | 3      | name.com                                                  |
| Bets.wine    | resell    | —         | —             | high           | low    | 4      | Dynadot Inc                                               |
| rice.wine    | premium   | $500      | —             | high           | low    | 4      | name.com                                                  |
| bce.wine     | available | $9.99     | —             | medium         | low    | 3      | name.com                                                  |
| case.wine    | resell    | —         | —             | high           | low    | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| zone.wine    | premium   | $242      | $242          | high           | low    | 4      | namesilo                                                  |
| farm.wine    | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc.                                           |
| blind.wine   | premium   | $500      | —             | medium         | low    | 5      | name.com                                                  |
| cxx.wine     | available | $8.48     | $75.98        | low            | low    | 3      | namecheap                                                 |
| park.wine    | resell    | —         | —             | high           | low    | 4      | Dynadot Inc                                               |
| photo.wine   | premium   | $118.80   | $118.80       | high           | medium | 5      | namesilo                                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,127 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/wine?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/wine?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=related_pricing)

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

This list covers 11,887 one-word .wine domain names, most carrying a median ask near $21. The set spans everyday words and phrases turned into single-string domains — names like fitthebill.wine, getready.wine, and criteria.wine show the range, from action-oriented phrases to abstract nouns. For wine brands, tasting rooms, or beverage startups, these domains offer short, memorable options that are ownable now. When comparing entries, weigh word clarity, spelling ease, and renewal cost against how well the name fits a wine or lifestyle brand.

- 11,887 one-word .wine domains updated daily
- Median ask near $21 across this .wine selection
- Brandable names like criteria.wine and forces.wine
- Short, single-word domains that are easy to spell and own

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .WINE One-Word Domains*. Version 2026-08-18. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WINE page](https://unique.domains/domains/tld/wine?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_wine_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
