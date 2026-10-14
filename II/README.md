# Independent Insurance — BIOSTEAM

**Project:** BIOSTEAM  
**Category:** CHEMICAL_PRODUCTION  
**Upstream:** see BENCH.json  
**Pinned commit:** `b3988834106b0a31b79f9c7f01a1f4c730c58102`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5e94cd0041d0f3b32bed1d881865f9dce8f655ef661602b71e2c54699e73dcdc`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | BIOSTEAM with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `5e94cd0041d0f3b32bed1d881865f9dce8f655ef661602b71e2c54699e73dcdc`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
