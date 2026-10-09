# Educators — ASTEROID

**Project:** ASTEROID  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/asteroid-team/asteroid  
**Pinned commit:** `c15708a04d3d28e9a1cd50553c456299dbc6d236`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9cdf26b12c42579fb31733909f35b3563f73f6c468ee7c6dac4d920afcfb38e2`  
**Date:** October 2026

## Teaching with ASTEROID

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `9cdf26b12c42579fb31733909f35b3563f73f6c468ee7c6dac4d920afcfb38e2` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
