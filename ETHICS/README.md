# Ethics — PYTHON_SKYFIELD

**Project:** PYTHON_SKYFIELD  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/skyfielders/python-skyfield  
**Pinned commit:** `31a6ed7584cd09b6e48e07546a4b5921e1cd5bb4`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `393d442388a8df39174338f85e4fbe212e9b1c7647e1a4b3c62c9f14c18ed74d`  
**Date:** October 2026

## Position

PYTHON_SKYFIELD is packaged for offline deployment with a verifiable audit trail. The
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
