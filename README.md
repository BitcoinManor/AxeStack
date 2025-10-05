# AxeStack

STACKSWORTH’s Bitaxe UI for ESP-Miner — a clean, read-only dashboard designed for the ESP32-S3 Spark display. It reads local AxeOS miner stats over HTTP and presents them in a calm, legible layout.

## Status
**v0.1 Planning / Scaffolding** — read-only, single-miner view first. Actions (restart, tuning) come later, behind confirmations.

## Why
- Dedicated, glanceable dashboard on the Spark screen
- Minimal network usage; resilient to miner restarts
- Open-source and friendly to the Bitaxe community

## Roadmap (short)
- [ ] v0.1: read-only overview (hashrate, temp, uptime)
- [ ] Miner IP settings stored in NVS
- [ ] Mini sparkline (recent hashrate buffer)
- [ ] Loss-of-signal/backoff handling
- [ ] v0.2+: optional actions with on-device PIN

## Dev quickstart (placeholder)
Coming after we scaffold the app structure and confirm library versions.

## Credits
AxeStack interacts with [AxeOS](https://github.com/bitaxeorg/ESP-Miner) by Bitaxe.org.  
We’re grateful to the open-source Bitaxe community for creating the AxeOS platform and API that make independent dashboards like this possible.


## License
MIT © 2025 BitcoinManor
