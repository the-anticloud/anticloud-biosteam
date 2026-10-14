# Educators — BIOSTEAM

**Project:** BIOSTEAM  
**Category:** CHEMICAL_PRODUCTION  
**Upstream:** see BENCH.json  
**Pinned commit:** `b3988834106b0a31b79f9c7f01a1f4c730c58102`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5e94cd0041d0f3b32bed1d881865f9dce8f655ef661602b71e2c54699e73dcdc`  
**Date:** October 2026

## Teaching with BIOSTEAM

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `5e94cd0041d0f3b32bed1d881865f9dce8f655ef661602b71e2c54699e73dcdc` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
