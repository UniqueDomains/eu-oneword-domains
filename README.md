# Available .EU One-Word Domains (7,593)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-7%2C593%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .eu one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **7,593 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 7,593 domains · **Median ask:** $281.72 · **High-demand under $2,500:** 5

**Last updated:** 2026-09-26
**Canonical page:** `https://unique.domains/domains/tld/eu`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/eu?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./eu.csv">CSV</a> / <a href="./eu.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .EU search](https://unique.domains/domains/tld/eu?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .EU search](https://unique.domains/domains/tld/eu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .EU one-word domain catalog.

### Files

- `eu.csv`, public CSV extract (1,000 rows)
- `eu.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/eu-oneword-domains/main/eu.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                                     |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------------------------------------------------------- |
| universal.eu  | resell    | —         | —             | high           | high   | 9      | Name: Porkbun LLC Website: https://porkbun.com/                               |
| commerce.eu   | resell    | —         | —             | high           | low    | 8      | Name: Greenmark IT GmbH Website: https://www.do.de                            |
| cure.eu       | resell    | —         | —             | high           | low    | 4      | Name: Spaceship, Inc. Website: https://www.spaceship.com/                     |
| market.eu     | resell    | —         | —             | high           | medium | 6      | Name: eu-artemis.at web invest gmbh & co KG Website: http://www.eu-artemis.at |
| rectify.eu    | resell    | —         | —             | high           | low    | 7      | Name: Dynadot, LLC Website: https://www.dynadot.com/domain/eu.html            |
| gorgeous.eu   | resell    | —         | —             | high           | low    | 8      | Name: info.at Internet GmbH Website: www.info.at                              |
| rwandan.eu    | available | $5.98     | $10.98        | high           | medium | 7      | namecheap                                                                     |
| convert.eu    | resell    | —         | —             | high           | low    | 7      | —                                                                             |
| danger.eu     | resell    | —         | —             | high           | low    | 6      | Name: EuroDNS S.A. Website: https://www.eurodns.com/                          |
| respected.eu  | premium   | $4,158.78 | —             | high           | low    | 9      | name.com                                                                      |
| beach.eu      | resell    | —         | —             | high           | low    | 5      | Name: Ascio Technologies Inc. Website: https://www.ascio.com                  |
| crowd.eu      | resell    | —         | —             | high           | low    | 5      | Name: EuroDNS S.A. Website: https://www.eurodns.com/                          |
| paris.eu      | resell    | —         | —             | high           | low    | 5      | —                                                                             |
| shortened.eu  | available | $5.49     | $9.99         | high           | medium | 9      | namesilo                                                                      |
| siliceous.eu  | available | $5.49     | $9.99         | high           | medium | 9      | namesilo                                                                      |
| feels.eu      | available | —         | —             | high           | low    | 5      | —                                                                             |
| sapphirine.eu | available | $5.98     | $10.98        | high           | medium | 10     | namecheap                                                                     |
| stand.eu      | resell    | —         | —             | high           | low    | 5      | Name: GoDaddy.com, LLC Website: http://www.godaddy.com                        |
| preeminent.eu | available | $5.49     | $9.99         | high           | medium | 10     | namesilo                                                                      |
| regressive.eu | available | $5.49     | $9.99         | high           | medium | 10     | namesilo                                                                      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 7,593 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 5 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/eu?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/eu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers 4,985 one-word .eu domain names, including everyday words like stuff.eu and strengthen.eu alongside compact compounds such as burgerbun.eu and coffeesenna.eu. Most names are single dictionary words or short two-part blends, making them easy to say and easy to remember. The median asking price across the set is about $673, giving both investors and founders a realistic baseline for budgeting. Because .eu is tied to the European market, these domains can carry regional trust signals for buyers or customers based in the EU.

- 4,985 one-word .eu domain names in this selection
- Median asking price near $673 across the set
- Mix of single words and short two-word blends
- Useful for EU-focused branding or portfolio building

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .EU One-Word Domains*. Version 2026-09-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .EU page](https://unique.domains/domains/tld/eu?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
