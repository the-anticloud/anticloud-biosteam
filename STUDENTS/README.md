# Students — BIOSTEAM

**Project:** BIOSTEAM  
**Category:** CHEMICAL_PRODUCTION  
**Upstream:** see BENCH.json  
**Pinned commit:** `b3988834106b0a31b79f9c7f01a1f4c730c58102`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5e94cd0041d0f3b32bed1d881865f9dce8f655ef661602b71e2c54699e73dcdc`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `b3988834106b0a31b79f9c7f01a1f4c730c58102`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `5e94cd0041d0f3b32bed1d881865f9dce8f655ef661602b71e2c54699e73dcdc`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
