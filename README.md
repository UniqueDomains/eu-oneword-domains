# Available .EU One-Word Domains

**Looking for a name, not a file?** [Find the strongest domain still available for your business](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_home).

1,000 real .eu one-word domain names, refreshed every night, with their status and, when known, the price to register or buy them and what they renew at. One line of pandas, no scraping, no key.

Each word exists once on each ending. Unique.domains tracks [37,520 names on .eu](https://unique.domains/tld/eu); this file is an extract of the ones you can still register or buy, in the list's own neutral order, not a ranking.

29,453 one-word .eu names are free to register today. Cheapest first year $4.21 at Dynadot, renewal $6.05 there. 117 .eu sales in the last 12 months, median $3,375.

Live page: [unique.domains/tld/eu](https://unique.domains/tld/eu?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=top_tld_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [eu.csv](https://github.com/UniqueDomains/eu-oneword-domains/raw/main/eu.csv), 1,000 rows
- [eu.json](https://github.com/UniqueDomains/eu-oneword-domains/raw/main/eu.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/eu-oneword-domains/main/eu.csv")
print(df.head())
```

Also on Kaggle, with every ending: [One-Word Domains by Ending](https://www.kaggle.com/datasets/uniquedomains/one-word-domains-by-ending).

## Sample rows

The first 20 rows of the file, in the file's order.

| domain           | status    | purchase_price | renewal_price | attractiveness | demand | length |
| ---------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| supergallant.eu  | available | $5.49          | $9.99         | high           | low    | 12     |
| moderately.eu    | available | $5.68          | $5.68         | high           | low    | 10     |
| recompost.eu     | available | $5.68          | $5.68         | high           | low    | 9      |
| creations.eu     | resell    | —              | —             | high           | low    | 9      |
| accorded.eu      | available | $5.68          | $5.68         | medium         | low    | 8      |
| dysfunctional.eu | available | $6.98          | $10.98        | medium         | low    | 13     |
| involves.eu      | available | $5.49          | $9.99         | high           | low    | 8      |
| dismantler.eu    | available | $5.68          | $5.68         | high           | low    | 10     |
| jocosity.eu      | available | $5.68          | $5.68         | high           | low    | 8      |
| expendable.eu    | available | $4.84          | $6.19         | high           | low    | 10     |
| bactericide.eu   | available | $5.49          | $9.99         | high           | low    | 11     |
| blinking.eu      | available | $5.49          | $9.99         | high           | low    | 8      |
| snuba.eu         | available | $5.68          | $5.68         | high           | low    | 5      |
| encryption.eu    | resell    | —              | —             | high           | low    | 10     |
| concluding.eu    | available | $5.49          | $9.99         | high           | low    | 10     |
| timelessness.eu  | available | $5.49          | $9.99         | high           | low    | 12     |
| sanctified.eu    | available | $5.49          | $9.99         | high           | low    | 10     |
| hydrator.eu      | available | $5.88          | $5.88         | high           | low    | 8      |
| regarde.eu       | available | $6.98          | $10.98        | high           | low    | 7      |
| uphold.eu        | resell    | —              | —             | high           | low    | 6      |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the 9,770 names in the live list today.
- Every row is a one-word domain name.
- Check a name before you act on it: a status or a price can change.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique.domains, One-word .eu domains, https://unique.domains/tld/eu, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique.domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=related_hub).

## About Unique.domains

[Unique.domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts.

From code: the [Node.js SDK and CLI](https://github.com/UniqueDomains/nodejs) (`npm install domain-name-api`), the [Python client](https://github.com/UniqueDomains/python) (`pip install uniquedomains`) and the [MCP server](https://github.com/UniqueDomains/mcp-server) for AI assistants, hosted at `https://mcp.unique.domains/mcp`.

Questions and corrections: `kai@unique.domains`

[Start a Radar for .eu names](https://unique.domains/tld/eu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_eu_oneword_domains&utm_content=about)
