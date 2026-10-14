# Educators — AUDIOTOOLS

**Project:** AUDIOTOOLS  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/descriptinc/audiotools  
**Pinned commit:** `348ebf2034ce24e2a91a553e3171cb00c0c71678`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a2f30ff37d910de2f8e3af96768c0822cf62099501ad7512ccf7c0ddc7a0187d`  
**Date:** October 2026

## Teaching with AUDIOTOOLS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `a2f30ff37d910de2f8e3af96768c0822cf62099501ad7512ccf7c0ddc7a0187d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
