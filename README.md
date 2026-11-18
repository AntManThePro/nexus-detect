# NEXUS // DETECT

Public-catalog threat detector. Scores a CISA KEV snapshot for recency, vendor cluster, and edge-appliance class — freshest stuff and edge boxes float to the top.

**Live:** https://antmanthepro.github.io/nexus-detect/

## How to use

1. Open the live site. It scores the built-in KEV snapshot (2026-10-02) on load.
2. Hit RUN DETECT to re-score, FIT to reset the view.
3. Hit TRY LIVE to pull the real CISA KEV feed — if it can't reach it, it falls back to the snapshot and says so.
4. Drag to pan the map, pinch to zoom. Top hits show their score, age, and why they flagged.

## Notes

- Snapshot data only by default — no keys, no account, nothing leaves your browser unless you hit TRY LIVE.
- Scores are a triage signal, not a verdict. Patch the edge boxes first.

## Links

- Live site: https://antmanthepro.github.io/nexus-detect/
- NEXUS Hub: https://nexus-world-hub.netlify.app/
- Repo: https://github.com/AntManThePro/nexus-detect

Built by DoubleA / AntManThePro. Not perfect, just real.
