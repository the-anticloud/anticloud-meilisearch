# MEILISEARCH

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-search_engines-lightgrey)

> Anticloud-hardened packaging of the upstream project `MEILISEARCH` in category **SEARCH ENGINES**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SEARCH ENGINES · **Upstream:** https://github.com/meilisearch/meilisearch · **Upstream pin:** `88d7d634143dff3cbef4969af519b5bbcd96e7f3` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<p align="center">
  <a href="https://www.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=logo#gh-light-mode-only" target="_blank">
    <img src="assets/meilisearch-logo-light.svg?sanitize=true#gh-light-mode-only">
  </a>
  <a href="https://www.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=logo#gh-dark-mode-only" target="_blank">
    <img src="assets/meilisearch-logo-dark.svg?sanitize=true#gh-dark-mode-only">
  </a>
</p>

<h4 align="center">
  <a href="https://www.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=nav">Website</a> |
  <a href="https://roadmap.meilisearch.com/tabs/1-under-consideration">Roadmap</a> |
  <a href="https://www.meilisearch.com/pricing?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=nav">Meilisearch Cloud</a> |
  <a href="https://blog.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=nav">Blog</a> |
  <a href="https://www.meilisearch.com/docs?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=nav">Documentation</a> |
  <a href="https://www.meilisearch.com/docs/faq?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=nav">FAQ</a> |
  <a href="https://discord.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=nav">Discord</a>
</h4>

<p align="center">
  <a href="https://deps.rs/project/github/meilisearch/meilisearch"><img src="https://deps.rs/project/github/meilisearch/meilisearch/status.svg" alt="Dependency status"></a>
  <a href="https://github.com/meilisearch/meilisearch/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-informational" alt="License"></a>
  <a href="https://github.com/meilisearch/meilisearch/queue"><img alt="Merge Queues enabled" src="https://img.shields.io/badge/Merge_Queues-enabled-%2357cf60?logo=github"></a>
</p>

<p align="center">⚡ A lightning-fast search engine that fits effortlessly into your apps, websites, and workflow 🔍</p>

[Meilisearch](https://www.meilisearch.com?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=intro) helps you shape a delightful search experience in a snap, offering features that work out of the box to speed up your workflow.

<p align="center" name="demo">
  <a href="https://where2watch.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demo-gif#gh-light-mode-only" target="_blank">
    <img src="assets/demo-light.gif#gh-light-mode-only" alt="A bright colored application for finding movies screening near the user">
  </a>
  <a href="https://where2watch.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demo-gif#gh-dark-mode-only" target="_blank">
    <img src="assets/demo-dark.gif#gh-dark-mode-only" alt="A dark colored application for finding movies screening near the user">
  </a>
</p>

## 🖥 Examples

- [**Movies**](https://where2watch.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=organization) — An application to help you find streaming platforms to watch movies using [hybrid search](https://www.meilisearch.com/solutions/hybrid-search?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos).
- [**Flickr**](https://flickr.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=organization) — Search and explore one hundred million Flickr images with semantic search.
- [**Ecommerce**](https://ecommerce.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos) — Ecommerce website using disjunctive [facets](https://www.meilisearch.com/docs/learn/fine_tuning_results/faceted_search?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos), range and rating filtering, and pagination.
- [**Home Booking**](https://www.meilisearch.com/docs/resources/demos/home_booking) - A conversational search demo for finding holiday rentals using natural language.
- [**Search Playground**](https://www.meilisearch.com/docs/resources/demos/playground) — An interactive playground to explore Meilisearch search features.
- [**Personalization**](https://www.meilisearch.com/docs/resources/demos/personalized_search) — A demo showcasing personalized search results tailored to individual users.
- [**SaaS**](https://saas.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos) — Search for contacts, deals, and companies in this [multi-tenant](https://www.meilisearch.com/docs/learn/security/multitenancy_tenant_tokens?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos) CRM application.

See the list of all our example apps in our [demos project](https://github.com/meilisearch/demos).

## ✨ Features
- **Hybrid search:** Combine the best of both [semantic](https://www.meilisearch.com/docs/learn/experimental/vector_search?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features) & full-text search to get the most relevant results
- **Search-as-you-type:** Find & display results in less than 50 milliseconds to provide an intuitive experience
- **[Typo tolerance](https://www.meilisearch.com/docs/learn/relevancy/typo_tolerance_settings?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** get relevant matches even when queries contain typos and misspellings
- **[Filtering](https://www.meilisearch.com/docs/learn/fine_tuning_results/filtering?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features) and [faceted search](https://www.meilisearch.com/docs/learn/fine_tuning_results/faceted_search?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** enhance your users' search experience with custom filters and build a faceted search interface in a few lines of code
- **[Sorting](https://www.meilisearch.com/docs/learn/fine_tuning_results/sorting?utm_camp

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Rust / Cargo** (manifests: Cargo.toml, Cargo.lock; scanned in UPSTREAM_CLONE)
- Top-level source layout: `assets/`, `crates/`, `documentation/`, `external-crates/`, `workloads/`
- Snapshot size: **1192 files**, **183127 lines of code** (measured; see Benchmarks)
- Primary languages: `.rs` (597), `.snap` (430), `(none)` (52), `.toml` (32), `.md` (23), `.json` (21)
- Upstream commit pinned for this packaging: `88d7d634143dff3cbef4969af519b5bbcd96e7f3`

---

## Installation

- **[Sorting](https://www.meilisearch.com/docs/learn/fine_tuning_results/sorting?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** sort results based on price, date, or pretty much anything else your users need
- **[Synonym support](https://www.meilisearch.com/docs/learn/relevancy/synonyms?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** configure synonyms to include more relevant content in your search results
- **[Geosearch](https://www.meilisearch.com/docs/learn/fine_tuning_results/geosearch?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** filter and sort documents based on geographic data
- **[Extensive language support](https://www.meilisearch.com/docs/learn/what_is_meilisearch/language?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** search datasets in any language, with optimized support for Chinese, Japanese, Hebrew, and languages using the Latin alphabet
- **[Security management](https://www.meilisearch.com/docs/learn/security/master_api_keys?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** control which users can access what data with API keys that allow fine-grained permissions handling
- **[Multi-Tenancy](https://www.meilisearch.com/docs/learn/security/multitenancy_tenant_tokens?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** personalize search results for any number of application tenants
- **Highly Customizable:** customize Meilisearch to your specific needs or use our out-of-the-box and hassle-free presets
- **[RESTful API](https://www.meilisearch.com/docs/reference/api/overview?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** integrate Meilisearch in your technical stack with our plugins and SDKs
- **[Conversational search](https://www.meilisearch.com/docs/capabilities/conversational_search/overview):** let users ask questions in natural language and get AI-generated answers grounded in your search results
- **[Personalization](https://www.meilisearch.com/docs/capabilities/personalization/overview):** tailor search results to individual users based on their preferences and behavior
- **Search rules:** define custom rules to dynamically adjust search behavior based on context
- **[Document relations](https://www.meilisearch.com/docs/capabilities/indexing/how_to/document_relations):** link documents across indexes to enrich search results with related data
- **[Replication & sharding](https://www.meilisearch.com/docs/resources/self_hosting/sharding/overview):** scale horizontally by distributing your data across multiple nodes
- **AI-ready:** works out of the box with [LangChain](https://www.meilisearch.com/with/LangChain) and the [Model Context Protocol (MCP)](https://github.com/meilisearch/meilisearch-mcp)
- **Easy to install, deploy, and maintain**

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

- [**Movies**](https://where2watch.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=organization) — An application to help you find streaming platforms to watch movies using [hybrid search](https://www.meilisearch.com/solutions/hybrid-search?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos).
- [**Flickr**](https://flickr.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=organization) — Search and explore one hundred million Flickr images with semantic search.
- [**Ecommerce**](https://ecommerce.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos) — Ecommerce website using disjunctive [facets](https://www.meilisearch.com/docs/learn/fine_tuning_results/faceted_search?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos), range and rating filtering, and pagination.
- [**Home Booking**](https://www.meilisearch.com/docs/resources/demos/home_booking) - A conversational search demo for finding holiday rentals using natural language.
- [**Search Playground**](https://www.meilisearch.com/docs/resources/demos/playground) — An interactive playground to explore Meilisearch search features.
- [**Personalization**](https://www.meilisearch.com/docs/resources/demos/personalized_search) — A demo showcasing personalized search results tailored to individual users.
- [**SaaS**](https://saas.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos) — Search for contacts, deals, and companies in this [multi-tenant](https://www.meilisearch.com/docs/learn/security/multitenancy_tenant_tokens?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demos) CRM application.

See the list of all our example apps in our [demos project](https://github.com/meilisearch/demos).

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

<a href="https://www.meilisearch.com/docs/faq?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=nav">FAQ</a> |
  <a href="https://discord.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=nav">Discord</a>
</h4>

<p align="center">
  <a href="https://deps.rs/project/github/meilisearch/meilisearch"><img src="https://deps.rs/project/github/meilisearch/meilisearch/status.svg" alt="Dependency status"></a>
  <a href="https://github.com/meilisearch/meilisearch/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-informational" alt="License"></a>
  <a href="https://github.com/meilisearch/meilisearch/queue"><img alt="Merge Queues enabled" src="https://img.shields.io/badge/Merge_Queues-enabled-%2357cf60?logo=github"></a>
</p>

<p align="center">⚡ A lightning-fast search engine that fits effortlessly into your apps, websites, and workflow 🔍</p>

[Meilisearch](https://www.meilisearch.com?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=intro) helps you shape a delightful search experience in a snap, offering features that work out of the box to speed up your workflow.

<p align="center" name="demo">
  <a href="https://where2watch.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demo-gif#gh-light-mode-only" target="_blank">
    <img src="assets/demo-light.gif#gh-light-mode-only" alt="A bright colored application for finding movies screening near the user">
  </a>
  <a href="https://where2watch.meilisearch.com/?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=demo-gif#gh-dark-mode-only" target="_blank">
    <img src="assets/demo-dark.gif#gh-dark-mode-only" alt="A dark colored application for finding movies screening near the user">
  </a>
</p>

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Rust / Cargo |
| Manifests detected | Cargo.toml, Cargo.lock |
| Files in snapshot | 1192 |
| Lines of code | 183127 |
| Dependency references | 459 |
| Dependencies by ecosystem | cargo: 459 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| cargo | resolver | 2 | Cargo.toml |
| cargo | version | 1.54.2 | Cargo.toml |
| cargo | description | Meilisearch HTTP server | Cargo.toml |
| cargo | homepage | https://meilisearch.com | Cargo.toml |
| cargo | readme | README.md | Cargo.toml |
| cargo | edition | 2021 | Cargo.toml |
| cargo | license | MIT | Cargo.toml |
| cargo | mimalloc | 0.1.52 | Cargo.toml |
| cargo | inherits | release | Cargo.toml |
| cargo | name | build-info | crates/build-info/Cargo.toml |
| cargo | time | 0.3.55 | crates/build-info/Cargo.toml |
| cargo | anyhow | 1.0.104 | crates/build-info/Cargo.toml |
| cargo | vergen-gitcl | 1.0.8 | crates/build-info/Cargo.toml |
| cargo | name | dump | crates/dump/Cargo.toml |
| cargo | flate2 | 1.1.9 | crates/dump/Cargo.toml |
| ... | (444 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

- **[Filtering](https://www.meilisearch.com/docs/learn/fine_tuning_results/filtering?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features) and [faceted search](https://www.meilisearch.com/docs/learn/fine_tuning_results/faceted_search?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** enhance your users' search experience with custom filters and build a faceted search interface in a few lines of code
- **[Sorting](https://www.meilisearch.com/docs/learn/fine_tuning_results/sorting?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** sort results based on price, date, or pretty much anything else your users need
- **[Synonym support](https://www.meilisearch.com/docs/learn/relevancy/synonyms?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** configure synonyms to include more relevant content in your search results
- **[Geosearch](https://www.meilisearch.com/docs/learn/fine_tuning_results/geosearch?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** filter and sort documents based on geographic data
- **[Extensive language support](https://www.meilisearch.com/docs/learn/what_is_meilisearch/language?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** search datasets in any language, with optimized support for Chinese, Japanese, Hebrew, and languages using the Latin alphabet
- **[Security management](https://www.meilisearch.com/docs/learn/security/master_api_keys?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** control which users can access what data with API keys that allow fine-grained permissions handling
- **[Multi-Tenancy](https://www.meilisearch.com/docs/learn/security/multitenancy_tenant_tokens?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** personalize search results for any number of application tenants
- **Highly Customizable:** customize Meilisearch to your specific needs or use our out-of-the-box and hassle-free presets
- **[RESTful API](https://www.meilisearch.com/docs/reference/api/overview?utm_campaign=oss&utm_source=github&utm_medium=meilisearch&utm_content=features):** integrate Meilisearch in your technical stack with our plugins and SDKs
- **[Conversational search](https://www.meilisearch.com/docs/capabilities/conversational_search/overview):** let users ask questions in natural language and get AI-generated answers grounded in your search results
- **[Personalization](https://www.meilisearch.com/docs/capabilities/personalization/overview):** tailor search results to individual users based on their preferences and behavior
- **Search rules:** define custom rules to dynamically adjust search behavior based on context
- **[Document relations](https://www.meilisearch.com/docs/capabilities/indexing/how_to/document_relations):** link documents across indexes to enrich search results with related data
- **[Replication & sharding](https://www.meilisearch.com/docs/resources/self_hosting/sharding/overview):** scale horizontally by distributing your data across multiple nodes
- **AI-ready:** works out of the box with [LangChain](https://www.meilisearch.com/with/LangChain) and the [Model Context Protocol (MCP)](https://github.com/meilisearch/meilisearch-mcp)
- **Easy to install, deploy, and maintain**

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing

First, thank you for contributing to Meilisearch! The goal of this document is to provide everything you need to start contributing to Meilisearch.

Remember that there are many ways to contribute other than writing code: writing [tutorials or blog posts](https://github.com/meilisearch/awesome-meilisearch), improving [the documentation](https://github.com/meilisearch/documentation), submitting [bug reports](https://github.com/meilisearch/meilisearch/issues/new?assignees=&labels=&template=bug_report.md&title=) and [feature requests](https://github.com/meilisearch/product/discussions/categories/feedback-feature-proposal)...

Meilisearch can manage multiple indexes, handle the update store, and expose an HTTP API. Search and indexation are the domain of our core engine, [`milli`](https://github.com/meilisearch/meilisearch/tree/main/milli), while tokenization is handled by [our `charabia` library](https://github.com/meilisearch/charabia/).

If Meilisearch does not offer optimized support for your language, please consider contributing to `charabia` by following the [CONTRIBUTING.md file](https://github.com/meilisearch/charabia/blob/main/CONTRIBUTING.md) and integrating your intended normalizer/segmenter.

## Table of Contents

- [Use of generative AI tools](#use-of-generative-ai-tools)
- [Assumptions](#assumptions)
- [How to Contribute](#how-to-contribute)
- [Development Workflow](#development-workflow)
- [Git Guidelines](#git-guidelines)
- [Release Process (for internal team only)](#publish-process-for-internal-team-only)

## Use of generative AI tools

We require that you transparently disclose any usage of generative AI tooling (GitHub Copilot, ChatGPT, Claude Code, Cursor, etc.) in contributions, if it was used to generate code (including test code) or documentation.

We stress that you need to own any contribution you make to Meilisearch even if it was generated.

In particular, in generated contributions:

- Please check that any generated claim is true.
- Please limit the scope of the change in your contribution.
  - Avoid drive-by contribution not related to the core of your contribution (adding a Changelog.md to Meilisearch, upgrading all dependencies when it is not necessary, introducing a new testing convention alongside your feature).
  - If your contribution contains architectural changes to the engine, it might not be the best-suited to an external contribution. Please check the implementation strategy beforehand with a maintainer

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
# License

Copyright (c) 2019-2025 Meili SAS

Part of this work fall under the Meilisearch Enterprise Edition (EE) and are licensed under the Business Source License 1.1, please refer to [LICENSE-EE](./LICENSE-EE) for details.

The other parts of this work are licensed under the [MIT license](./LICENSE-MIT).

`SPDX-License-Identifier: MIT AND BUSL-1.1`
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `MEILISEARCH` (category: SEARCH ENGINES)
- **Upstream URL:** https://github.com/meilisearch/meilisearch
- **Pinned commit (SHA):** `88d7d634143dff3cbef4969af519b5bbcd96e7f3`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`e0ff6a8ca34df01eddc06cf2c3a8b2470876aa718608d1c6d8d88f4cf83f35d6`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

