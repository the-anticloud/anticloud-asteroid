# Ethics — ASTEROID

**Project:** ASTEROID  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/asteroid-team/asteroid  
**Pinned commit:** `c15708a04d3d28e9a1cd50553c456299dbc6d236`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9cdf26b12c42579fb31733909f35b3563f73f6c468ee7c6dac4d920afcfb38e2`  
**Date:** October 2026

## Position

ASTEROID is packaged for offline deployment with a verifiable audit trail. The
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
