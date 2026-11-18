# MY KEF // NEXUS ARCHIVE

Commercial kitchen exhaust fan (KEF) and pollution control equipment passport — assets, diagnostics, service timeline, and technical source library. Single-file app, zero external dependencies, all records stored locally in the browser (`mykef:` localStorage keys).

Live: https://my-kef.netlify.app/

## How to use

1. Open the live site and pick **Overview** to see your assets, open findings, and recent service activity.
2. Open **Equipment passports** to register a fan or pollution control unit (make, model, serial, config) or search one you already saved.
3. Use **Diagnostics** to record what you actually saw on the unit — symptom first, then diagnosis, action, and verification, kept separate.
4. Use **Log service event** to add a visit, inspection, fault, or audit to the timeline, and **Export JSON** to take the whole registry with you.
5. Print a QR asset label from a passport — demo QR visual only; encode a stable asset URL in production.

## What it does

- **Equipment passports** — register assets with make/model/serial/config, edit metadata, print QR labels (demo QR visual only — encode a stable asset URL in production).
- **Diagnostics** — record findings per asset, update status.
- **Service timeline** — log service events, inspections, faults, audits; export events as JSON.
- **Source library** — OEM technical references (CaptiveAire, Gaylord, ASHRAE, UL 8782, NFPA 96, Halton).
- **Export** — full registry + events + findings as JSON.

## Demo data

Ships with fictional demo records, honestly labeled throughout ("LOCAL DEMO DATA", "Demo records are fictional and local-only"). Demo data lives only in the visitor's own browser and can be cleared by clearing site data.

## Install

Open `index.html` in any modern browser, or serve the folder statically. Add to Home Screen — custom icon set included (`icons/`, `manifest.json`).

## Links

- Live site: https://my-kef.netlify.app/
- NEXUS World Hub: https://nexus-world-hub.netlify.app/
- Repo: https://github.com/AntManThePro/my-kef

DoubleA @ AntManThePro · NExtended Xperimental USers
