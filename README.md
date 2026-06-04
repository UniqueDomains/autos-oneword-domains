# Available .AUTOS One-Word Domains (12,345)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C345%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .autos one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,345 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,345 domains · **Median ask:** $161.25 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
**Canonical page:** `https://unique.domains/domains/tld/autos`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/autos?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./autos.csv">CSV</a> / <a href="./autos.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .AUTOS search](https://unique.domains/domains/tld/autos?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .AUTOS search](https://unique.domains/domains/tld/autos?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .AUTOS one-word domain catalog.

### Files

- `autos.csv` — public CSV extract (1,000 rows)
- `autos.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/autos-oneword-domains/main/autos.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| motive.autos    | available | $1.99     | —             | 112            | 62     | 6      | name.com                                     |
| leader.autos    | resell    | $1.99     | —             | 72             | 28     | 6      | Spaceship, Inc.                              |
| WhatsApp.autos  | premium   | $2,500    | —             | 114            | 96     | 8      | name.com                                     |
| warp.autos      | available | $1.99     | —             | 90             | 44     | 4      | name.com                                     |
| highway.autos   | resell    | $1.99     | —             | 68             | 21     | 7      | Dynadot LLC                                  |
| universal.autos | premium   | $2,500    | —             | 96             | 80     | 9      | name.com                                     |
| humans.autos    | available | $1.99     | —             | 76             | 43     | 6      | name.com                                     |
| superb.autos    | resell    | $1.99     | —             | 78             | 18     | 6      | Dynadot LLC                                  |
| jetpack.autos   | premium   | $2,500    | —             | 96             | 75     | 8      | name.com                                     |
| conscious.autos | available | $1.99     | $20.99        | 89             | 39     | 9      | name.com                                     |
| flow.autos      | resell    | —         | —             | 96             | 68     | 4      | Xiamen ChinaSource Internet Service Co., Ltd |
| impact.autos    | premium   | $2,500    | —             | 92             | 74     | 6      | name.com                                     |
| label.autos     | available | $1.99     | —             | 70             | 39     | 5      | name.com                                     |
| arm.autos       | resell    | —         | —             | 76             | 52     | 3      | Dynadot LLC                                  |
| Siri.autos      | premium   | $2,500    | —             | 76             | 70     | 4      | name.com                                     |
| emoji.autos     | available | $1.99     | $15.75        | 88             | 38     | 5      | namesilo                                     |
| share.autos     | resell    | —         | —             | 72             | 49     | 5      | Spaceship, Inc.                              |
| aladdin.autos   | premium   | $2,500    | —             | 76             | 67     | 7      | name.com                                     |
| unify.autos     | available | $1.99     | $20.99        | 72             | 38     | 5      | name.com                                     |
| join.autos      | resell    | —         | —             | 96             | 44     | 4      | Namecheap                                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,345 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/autos?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/autos?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .autos domains. The defining trait is the extension: every name ends in .autos, which makes automotive relevance explicit but also puts more weight on the word itself. In this set, examples range from broad dictionary terms such as identity.autos and regular.autos to more unusual options like amiss.autos or highlighting.autos. When comparing these domains, focus on whether the word strengthens an automotive use case, how easily it can be remembered and repeated aloud, and whether the asking price fits the level of brand clarity you get. The median ask is 92.16.

- All names in this selection use the .autos extension
- Count: 12,340 domains with a median ask of 92.16
- Short, clear words usually carry stronger recall
- Check word-to-extension fit before paying a premium

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .AUTOS One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .AUTOS page](https://unique.domains/domains/tld/autos?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_autos_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
