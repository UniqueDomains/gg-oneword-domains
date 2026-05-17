# Available .GG One-Word Domains (77,997)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-77%2C997%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .gg one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **77,997 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 77,997 domains · **Median ask:** $82.08 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-17  
**Canonical page:** `https://unique.domains/domains/tld/gg`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/gg?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./gg.csv">CSV</a> / <a href="./gg.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GG search](https://unique.domains/domains/tld/gg?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GG search](https://unique.domains/domains/tld/gg?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GG one-word domain catalog.

### Files

- `gg.csv` — public CSV extract (1,000 rows)
- `gg.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/gg-oneword-domains/main/gg.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                         |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------- |
| pinch.gg      | available | $82.98    | —             | 80             | 18     | 5      | namecheap                                         |
| laugh.gg      | premium   | —         | —             | 86             | 14     | 5      | —                                                 |
| jewels.gg     | available | $82.98    | —             | 80             | 15     | 6      | namecheap                                         |
| recipe.gg     | available | $82.98    | —             | 82             | 26     | 6      | namecheap                                         |
| Adidas.gg     | available | $82.98    | —             | 88             | 24     | 6      | namecheap                                         |
| iPhone.gg     | available | $82.98    | —             | 90             | 83     | 6      | namecheap                                         |
| pretzel.gg    | available | $82.98    | —             | 80             | 16     | 7      | namecheap                                         |
| QandA.gg      | available | $82.98    | —             | 80             | 10     | 7      | namecheap                                         |
| retirement.gg | available | $82.98    | —             | 80             | 23     | 10     | namecheap                                         |
| grandslam.gg  | available | $82.98    | —             | 82             | 13     | 10     | namecheap                                         |
| for.gg        | resell    | —         | —             | 80             | 50     | 3      | Spaceship, Inc (https://www.spaceship.com)        |
| gay.gg        | resell    | —         | —             | 82             | 43     | 3      | West263 International Limited (http://www.363.hk) |
| she.gg        | resell    | —         | —             | 86             | 28     | 3      | Spaceship, Inc (https://www.spaceship.com)        |
| clay.gg       | resell    | —         | —             | 80             | 35     | 4      | NameCheap, Inc (https://www.namecheap.com)        |
| make.gg       | resell    | —         | —             | 82             | 45     | 4      | NETIM (http://www.netim.com)                      |
| after.gg      | resell    | —         | —             | 86             | 27     | 5      | Backorder Ltd (https://backorder.com)             |
| popup.gg      | resell    | —         | —             | 84             | 28     | 6      | Dynadot Inc. (https://www.dynadot.com)            |
| fashion.gg    | resell    | —         | —             | 80             | 41     | 7      | Dynadot Inc. (https://www.dynadot.com)            |
| Friends.gg    | resell    | —         | —             | 82             | 37     | 7      | Spaceship, Inc (https://www.spaceship.com)        |
| fanclub.gg    | resell    | —         | —             | 84             | 20     | 8      | Enrapture Limited (https://enrapture.gg)          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 77,997 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/gg?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/gg?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=related_pricing)

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

These .gg domains span several naming styles. Some are short and memorable, such as pinch.gg, laugh.gg, she.gg, and jewels.gg. Others are broad keyword terms like retirement.gg or ultra-short function words like for.gg. This mix matters because .gg buyers usually need to weigh memorability against specificity and legal risk. When comparing these domains, start with whether the term is clean and ownable, then check ask price against how strong the word is on recall and commercial use. Be cautious with names that match famous brands or products, including Adidas.gg and iPhone.gg, because trademark risk is clear even if the string looks attractive.

- 77,982 .gg domains in this selection
- Median ask across the set is 82.07
- Short words can be memorable but not always ownable
- Famous brand terms carry obvious trademark risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GG One-Word Domains*. Version 2026-05-17. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GG page](https://unique.domains/domains/tld/gg?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gg_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
