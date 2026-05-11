# Available .MEN One-Word Domains (12,301)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C301%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .men one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,301 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,301 domains · **Median ask:** $166.18 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `men.csv` — public CSV extract (1,000 rows)
- `men.json` — public JSON extract (1,000 rows)
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

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| payments.men    | available | $9.48     | —             | 58             | 33     | 8      | namecheap       |
| events.men      | resell    | —         | —             | 68             | 37     | 6      | NameSilo, LLC   |
| coins.men       | premium   | $437.50   | —             | 56             | 41     | 5      | name.com        |
| systems.men     | available | $9.48     | —             | 46             | 27     | 7      | namecheap       |
| veterans.men    | resell    | —         | —             | 56             | 23     | 8      | NameSilo, LLC   |
| stories.men     | premium   | $437.50   | —             | 58             | 36     | 7      | name.com        |
| wheel.men       | available | $9.48     | —             | 74             | 24     | 5      | namecheap       |
| pestcontrol.men | resell    | —         | —             | 74             | 18     | 12     | NameSilo, LLC   |
| aliens.men      | premium   | $437.50   | —             | 56             | 35     | 6      | name.com        |
| gamers.men      | available | $5.25     | $6.25         | 62             | 24     | 6      | namesilo        |
| weddings.men    | resell    | —         | —             | 64             | 18     | 8      | Porkbun         |
| partners.men    | premium   | $437.50   | —             | 61             | 32     | 8      | name.com        |
| designs.men     | available | $9.48     | —             | 72             | 21     | 7      | namecheap       |
| landscaping.men | resell    | —         | —             | 80             | 16     | 11     | NameSilo, LLC   |
| trends.men      | premium   | $437.50   | —             | 60             | 32     | 6      | name.com        |
| affiliates.men  | available | $5.25     | $6.25         | 60             | 21     | 10     | namesilo        |
| mortgages.men   | resell    | —         | —             | 50             | 16     | 9      | Key-Systems LLC |
| brands.men      | premium   | $6,250    | —             | 62             | 28     | 6      | name.com        |
| restaurants.men | available | $9.48     | —             | 57             | 21     | 11     | namecheap       |
| surveys.men     | resell    | —         | —             | 56             | 15     | 7      | Dynadot Inc     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,301 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This set is defined by one trait: the .men extension. Within it, the quality spread comes from how naturally the word pairs with that ending. Generic words such as uproar.men, geek.men, and gather.men can read clearly and stay memorable, while some terms may feel awkward or overly broad. Pricing is relatively approachable at a median ask of 166.18, but low price alone does not make a name strong. When comparing these domains, focus on semantic fit, ease of recall, and whether the word creates avoidable trademark risk. For investors, discipline matters. For founders, the goal is a shortlist you can defend with confidence.

- Check whether the word reads naturally with .men
- Favor generic terms over obvious trademark exposure
- Use the 166.18 median ask as a pricing anchor
- Prefer memorable words with clean spelling

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MEN One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MEN page](https://unique.domains/domains/tld/men?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_men_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
