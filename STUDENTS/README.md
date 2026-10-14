# Students — AUDIOTOOLS

**Project:** AUDIOTOOLS  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/descriptinc/audiotools  
**Pinned commit:** `348ebf2034ce24e2a91a553e3171cb00c0c71678`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a2f30ff37d910de2f8e3af96768c0822cf62099501ad7512ccf7c0ddc7a0187d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `348ebf2034ce24e2a91a553e3171cb00c0c71678`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `a2f30ff37d910de2f8e3af96768c0822cf62099501ad7512ccf7c0ddc7a0187d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
