# Educators — PYTHON_SKYFIELD

**Project:** PYTHON_SKYFIELD  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/skyfielders/python-skyfield  
**Pinned commit:** `31a6ed7584cd09b6e48e07546a4b5921e1cd5bb4`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `393d442388a8df39174338f85e4fbe212e9b1c7647e1a4b3c62c9f14c18ed74d`  
**Date:** October 2026

## Teaching with PYTHON_SKYFIELD

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `393d442388a8df39174338f85e4fbe212e9b1c7647e1a4b3c62c9f14c18ed74d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
