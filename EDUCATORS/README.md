# Educators — MEILISEARCH

**Project:** MEILISEARCH  
**Category:** SEARCH_ENGINES  
**Upstream:** https://github.com/meilisearch/meilisearch  
**Pinned commit:** `fd86d197787fecf5a97221c2557422f808ea7c25`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8cdd49a7db31ed7a80e406892e07a51de6327cd1b359a04f0cceb0688d6228db`  
**Date:** October 2026

## Teaching with MEILISEARCH

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `8cdd49a7db31ed7a80e406892e07a51de6327cd1b359a04f0cceb0688d6228db` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
