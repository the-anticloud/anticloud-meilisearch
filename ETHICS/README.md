# Ethics — MEILISEARCH

**Project:** MEILISEARCH  
**Category:** SEARCH_ENGINES  
**Upstream:** https://github.com/meilisearch/meilisearch  
**Pinned commit:** `fd86d197787fecf5a97221c2557422f808ea7c25`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8cdd49a7db31ed7a80e406892e07a51de6327cd1b359a04f0cceb0688d6228db`  
**Date:** October 2026

## Position

MEILISEARCH is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
