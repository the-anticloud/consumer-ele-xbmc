# Technical Whitepaper — XBMC

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/XBMC/xbmc
**Category:** CONSUMER_ELECTRONICS

## Abstract

This whitepaper describes the Anticloud integration of `XBMC` (Kodi media center for smart TVs)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local product assistant replacing cloud voice/chat APIs
2. Single-binary firmware package with AIOSS-verified OTA integrity
3. AES-256 encryption for all on-device user data
4. Zero-cloud operation: full functionality without internet
5. GPU/CPU equalizer: inference scales to embedded ARM cortex or x86
6. Zero-telemetry mode: opt-in only, no passive data collection
7. AIOSS audit chain for all settings changes and firmware updates
8. Open API for third-party integrations replacing proprietary SDKs

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.