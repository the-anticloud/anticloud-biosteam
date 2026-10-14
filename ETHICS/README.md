# Ethics — BIOSTEAM

**Project:** BIOSTEAM  
**Category:** CHEMICAL_PRODUCTION  
**Upstream:** see BENCH.json  
**Pinned commit:** `b3988834106b0a31b79f9c7f01a1f4c730c58102`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5e94cd0041d0f3b32bed1d881865f9dce8f655ef661602b71e2c54699e73dcdc`  
**Date:** October 2026

## Position

BIOSTEAM is packaged for offline deployment with a verifiable audit trail. The
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
