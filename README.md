# Global Cross-Section: Alabaster & Obsidian Split 28-Story Broadsheet

Deterministic `1024x1024` JPEG generator (`cross_section.jpg` -> `/output/entry.png`) presenting **28 verified news dispatches from Friday, 13 November 2026** across all six inhabited continents.

## Architecture & Visual Design

- **Edition Style**: Alabaster & Obsidian Split Edition (`1024x1024`, `269328` bytes, SHA-256 `acd7d5711e0e795d...`)
- **Cartography**: Equirectangular high-contrast coordinate strip, 1-to-1 pin-numbered against every story badge (`#1–#28`), with simultaneous repulsion relaxation preventing overlap across Europe, the Middle East, North America, and East Asia.
- **Featured Coverage**: US FAA nationwide air-traffic ground stop, Nvidia drop under \$4T & Senate summons, APEC Shenzhen Trump-Xi-Putin talks, Kyiv hospital drone strike & EU E5 talks, disputed Iran-Bahrain radar claims (with explicit US denial), FBI N. Korea \$400m fake-video crypto theft warning, Harry Kane's 126th England cap record, US 6.5% PPI surprise, Microsoft 74-country outage, Starship Flight 15 orbit, Pope Leo XIV Chiclayo Mass, Hormuz unverified mine alert, Assam crash, Nigeria/DRC Ebola watch, and Victoria/NSW emergency bushfires.
- **Verification**: Enforces JPEG SOI/EOI bounds, SOF0/SOF2 exact `1024x1024` dimensions, 1 MiB ceiling, and SHA-256 checksum on every deterministic run without network access.

## Quick Verification

```bash
MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [`LICENSE`](LICENSE).
