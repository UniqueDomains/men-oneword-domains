# Available .MEN One-Word Domains (9,593)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C592%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C593%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .men one-word domains from Unique Domains.

> **Important:** this repository is a **public 9,592-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,593 domains** on the canonical page below.

**Public extract:** 9,592 rows · **Live catalog:** 9,593 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/men`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/men?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./men.csv">CSV</a> / <a href="./men.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .MEN search](https://unique.domains/domains/tld/men?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .MEN search](https://unique.domains/domains/tld/men?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MEN one-word domain catalog.

### Files

- `men.csv` — public CSV extract (9,592 rows)
- `men.json` — public JSON extract (9,592 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/men-oneword-domains/main/men.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| dental.men     | available | $9.48     | —             | 90             | 36     | 6      | namecheap                                           |
| march.men      | resell    | —         | —             | 70             | 80     | 5      | Porkbun                                             |
| converse.men   | premium   | $437.50   | $62.50        | 64             | 73     | 8      | name.com                                            |
| personal.men   | available | $9.48     | —             | 91             | 35     | 8      | namecheap                                           |
| name.men       | resell    | —         | —             | 82             | 76     | 4      | West263 International Limited                       |
| seventeen.men  | premium   | $437.50   | $62.50        | 84             | 62     | 9      | name.com                                            |
| account.men    | available | $9.48     | —             | 98             | 34     | 7      | namecheap                                           |
| flash.men      | resell    | —         | —             | 64             | 67     | 5      | Porkbun                                             |
| ace.men        | premium   | $625      | $81.25        | 88             | 57     | 3      | name.com                                            |
| eleven.men     | available | $9.48     | —             | 88             | 33     | 6      | namecheap                                           |
| harvard.men    | resell    | —         | —             | 72             | 65     | 7      | GoDaddy.com, LLC                                    |
| zero.men       | premium   | $125      | $37.99        | 112            | 53     | 4      | name.com                                            |
| concrete.men   | available | $9.48     | —             | 102            | 31     | 8      | namecheap                                           |
| web.men        | resell    | —         | —             | 72             | 61     | 3      | NameCheap, Inc.                                     |
| business.men   | premium   | $13,000   | $130          | 100            | 53     | 8      | namecheap                                           |
| curative.men   | available | $9.48     | —             | 92             | 27     | 8      | namecheap                                           |
| state.men      | resell    | —         | —             | 90             | 58     | 5      | Chengdu West Dimension Digital Technology Co., Ltd. |
| true.men       | premium   | $1,250    | $125          | 86             | 52     | 4      | name.com                                            |
| management.men | available | $9.48     | —             | 76             | 26     | 10     | namecheap                                           |
| hamilton.men   | resell    | —         | —             | 66             | 54     | 8      | NameSilo, LLC                                       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,592-row public sample | 9,593 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/men?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/men?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .MEN One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MEN page](https://unique.domains/domains/tld/men?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
