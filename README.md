# Available .REISE One-Word Domains (12,895)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C895%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .reise one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,895 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,895 domains · **Median ask:** $89.99 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/reise`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/reise?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./reise.csv">CSV</a> / <a href="./reise.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .REISE search](https://unique.domains/domains/tld/reise?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .REISE search](https://unique.domains/domains/tld/reise?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .REISE one-word domain catalog.

### Files

- `reise.csv` — public CSV extract (1,000 rows)
- `reise.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/reise-oneword-domains/main/reise.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Acup.reise     | available | $127.98   | —             | 80             | 5      | 5      | namecheap |
| Trex.reise     | available | $127.98   | —             | 80             | 24     | 5      | namecheap |
| finals.reise   | available | $27.89    | $97.99        | 80             | 7      | 6      | namesilo  |
| barup.reise    | available | $99.99    | —             | 82             | 2      | 6      | name.com  |
| forces.reise   | available | $99.99    | —             | 82             | 12     | 6      | name.com  |
| geton.reise    | available | $99.99    | —             | 82             | 10     | 6      | name.com  |
| getup.reise    | available | $99.99    | —             | 82             | 14     | 6      | name.com  |
| popup.reise    | available | $99.99    | —             | 84             | 29     | 6      | name.com  |
| matcha.reise   | available | $99.99    | —             | 86             | 39     | 6      | name.com  |
| playin.reise   | available | $99.99    | —             | 80             | 10     | 7      | name.com  |
| hangon.reise   | available | $99.99    | —             | 82             | 6      | 7      | name.com  |
| pierogi.reise  | available | $99.99    | —             | 82             | 7      | 7      | name.com  |
| getlife.reise  | available | $99.99    | —             | 80             | 5      | 8      | name.com  |
| agents.reise   | available | $99.99    | —             | 56             | 50     | 6      | name.com  |
| events.reise   | premium   | $250      | —             | 68             | 37     | 6      | name.com  |
| tips.reise     | premium   | $250      | —             | 80             | 26     | 4      | name.com  |
| lets.reise     | available | $99.99    | —             | 77             | 39     | 4      | name.com  |
| pictures.reise | premium   | $250      | —             | 82             | 17     | 8      | name.com  |
| aliens.reise   | available | $27.89    | $97.99        | 56             | 35     | 6      | namesilo  |
| spectra.reise  | available | $99.99    | —             | 62             | 34     | 7      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,895 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/reise?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/reise?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .reise domains. That makes it most relevant for travel-linked brands, location services, trip products, hospitality concepts, and travel content projects that want a direct semantic match in the extension itself. The sample names show a broad mix: some are highly literal, like WiFi.reise, while others are broader dictionary terms such as homes.reise or jewels.reise. When comparing these domains, focus first on whether the word gains clarity from .reise, whether the term is easy to remember and spell, and whether the asking price fits the narrow but explicit positioning of a travel-specific TLD.

- All names in this set use the .reise travel-focused extension
- Median ask across the selection is $89.99
- Literal keywords often fit .reise better than abstract words
- Check spelling clarity and trademark risk before choosing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REISE One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REISE page](https://unique.domains/domains/tld/reise?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_reise_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
