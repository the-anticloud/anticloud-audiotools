# Ethics — AUDIOTOOLS

**Project:** AUDIOTOOLS  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/descriptinc/audiotools  
**Pinned commit:** `348ebf2034ce24e2a91a553e3171cb00c0c71678`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a2f30ff37d910de2f8e3af96768c0822cf62099501ad7512ccf7c0ddc7a0187d`  
**Date:** October 2026

## Position

AUDIOTOOLS is packaged for offline deployment with a verifiable audit trail. The
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
