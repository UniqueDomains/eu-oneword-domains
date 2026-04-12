# Available .EU One-Word Domains (2,568)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-2%2C570%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-2%2C568%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .eu one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 2,570 rows · **Live catalog:** 2,568 domains

**Last updated:** 2026-04-12  
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

- `eu.csv` — public CSV extract (2,570 rows)
- `eu.json` — public JSON extract (2,570 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/eu-oneword-domains/main/eu.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                                                              |
| ------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ---------------------------------------------------------------------- |
| partyhat.eu   | available | $6.19      | $6.19         | 85             | 7      | 9      | namesilo                                                               |
| bullish.eu    | resell    | $3,195.85  | $11.99        | 73             | 18     | 7      | Name: Realtime Register B.V. Website: https://www.realtimeregister.com |
| textbook.eu   | premium   | $4,010.05  | $11.99        | 84             | 98     | 8      | Name: Realtime Register B.V. Website: https://www.realtimeregister.com |
| aberrant.eu   | available | $4.99      | $10.99        | 74             | 7      | 8      | name.com                                                               |
| stallion.eu   | resell    | $14,369.25 | $11.99        | 76             | 15     | 8      | Name: Dynadot, LLC Website: https://www.dynadot.com/domain/eu.html     |
| auditory.eu   | premium   | $3,331.55  | $11.99        | 88             | 97     | 8      | Name: Realtime Register B.V. Website: https://www.realtimeregister.com |
| annoyed.eu    | available | $4.99      | $11.99        | 58             | 7      | 7      | name.com                                                               |
| doable.eu     | resell    | $4,019.25  | $11.99        | 96             | 13     | 6      | Name: Dynadot, LLC Website: https://www.dynadot.com/domain/eu.html     |
| unshakable.eu | premium   | $2,684.10  | $11.99        | 72             | 97     | 10     | Name: Realtime Register B.V. Website: https://www.realtimeregister.com |
| andean.eu     | available | $4.99      | $11.99        | 76             | 6      | 6      | name.com                                                               |
| thirteen.eu   | resell    | $38,872.30 | $11.99        | 84             | 12     | 8      | Name: EuroDNS S.A. Website: https://www.eurodns.com/                   |
| astounding.eu | premium   | $3,331.55  | $11.99        | 70             | 97     | 10     | Name: Realtime Register B.V. Website: https://www.realtimeregister.com |
| aneurismal.eu | available | $4.99      | $11.99        | 50             | 6      | 10     | name.com                                                               |
| nineteen.eu   | resell    | $3,197     | $11.99        | 84             | 10     | 8      | Name: Realtime Register B.V. Website: https://www.realtimeregister.com |
| coloured.eu   | premium   | $3,355.70  | $11.99        | 68             | 97     | 8      | Name: Realtime Register B.V. Website: https://www.realtimeregister.com |
| monstrous.eu  | available | $4.99      | $11.99        | 46             | 6      | 9      | name.com                                                               |
| thousand.eu   | resell    | $38,973.50 | $10.99        | 84             | 9      | 8      | Name: EuroDNS S.A. Website: https://www.eurodns.com/                   |
| documented.eu | premium   | $3,331.55  | $11.99        | 66             | 97     | 10     | Name: Realtime Register B.V. Website: https://www.realtimeregister.com |
| adoring.eu    | available | $10.99     | $11.99        | 90             | 5      | 7      | name.com                                                               |
| forty.eu      | resell    | $939.55    | $11.99        | 80             | 9      | 5      | Name: TLD Registrar Solutions Ltd                                      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 2,570-row public sample | 2,568 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/eu?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/eu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .EU One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .EU page](https://unique.domains/domains/tld/eu?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
