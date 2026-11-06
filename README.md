<div align="center">
  <img src="branding/corredo-wordmark.png" alt="Corredo" width="460">

  <p><strong>Your kit, ready for the trail.</strong></p>

  <img src="https://img.shields.io/badge/status-Feature--complete%20v1%20%28pre--release%29-1F4D3A?style=flat-square" alt="status"> <img src="https://img.shields.io/badge/platform-iOS%2017%2B-1F4D3A?style=flat-square" alt="platform"> <img src="https://img.shields.io/badge/license-proprietary-555555?style=flat-square" alt="license"> <img src="https://img.shields.io/badge/by-Aquila%20Digital%20LLC-14213D?style=flat-square" alt="Aquila Digital LLC">
</div>

> **Showcase repository.** The source code for Corredo is not published. This page presents what the product is and how it works.

## Overview

A native iPhone/iPad app for keeping a gear inventory, building reusable packing kits, and getting an on-device pack guide for a trip, including trips sent from Stellata.

## How it works

```mermaid
flowchart LR
  A["Add the gear you own"] --> B["Create a trip (nights, season, elevation, party size)"] --> C["Rules engine matches the checklist against your gear"] --> D["'You have' vs 'Still need', each missing item rated 1-5"] --> E["Build a kit, pack with a progress ring, share the shopping list"]
```

## Features

- My Gear: category, brand, condition, cost, warranty, maintenance intervals
- Kits: reusable packing lists with checklist and progress ring
- Trips + deterministic pack guide with Essential / Recommended / Nice-to-have ratings
- Weight totals, party-size scaling, trip countdowns, merged shopping list
- Stellata link (corredo://trip) that always asks before saving
- JSON backup/restore, formula-safe CSV export, four color themes, dark mode

## Tech stack

| Layer | Choice |
|---|---|
| Language / UI | Swift, SwiftUI, SwiftData, iOS 17+ |
| Dependencies | None (no packages, no network) |
| Docs | ARCHITECTURE, SECURITY, PRIVACY, TESTING, CHANGELOG |
| Tests | CorredoTests (unit) |

## Privacy & security

No network, no accounts, no analytics. Everything is on-device; URL-scheme input is treated as untrusted.

## Brand

| | Name | Hex | Role |
|---|---|---|---|
| <img src="https://placehold.co/44x22/1F4D3A/1F4D3A.png" alt="#1F4D3A" /> | Forest | `#1F4D3A` | Primary |
| <img src="https://placehold.co/44x22/97A88F/97A88F.png" alt="#97A88F" /> | Sage | `#97A88F` | Secondary |
| <img src="https://placehold.co/44x22/F4A261/F4A261.png" alt="#F4A261" /> | Sun | `#F4A261` | Accent |
| <img src="https://placehold.co/44x22/8B5E3C/8B5E3C.png" alt="#8B5E3C" /> | Earth | `#8B5E3C` | Warm neutral |
| <img src="https://placehold.co/44x22/EDE8DF/EDE8DF.png" alt="#EDE8DF" /> | Sand | `#EDE8DF` | Light surface |

**Mark.** A "C" formed by mountains and a sun, set in a lowercase rounded wordmark.

**Voice.** Confident and friendly: "pack well".

## Roadmap

- Photos
- iCloud sync
- Maintenance notifications
- Widgets and barcode scanning
- Review of guide rules by a backpacking expert

## Notes

Companion app: [Stellata](https://github.com/Steven6Brown/Stellata). Formerly GearGrid / Kitwise.

## License

Proprietary. Shared publicly for portfolio and demonstration purposes only. See [LICENSE](LICENSE).

---

<div align="center">

Built by [Aquila Digital LLC](https://github.com/Steven6Brown) · *Per Aspera Ad Astra*

</div>
