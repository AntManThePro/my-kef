# MY KEF // NEXUS ARCHIVE

Commercial kitchen exhaust fan (KEF) and pollution control equipment passport — assets, diagnostics, service timeline, and technical source library. Single-file app, zero external dependencies, all records stored locally in the browser (`mykef:` localStorage keys).

Live: https://my-kef.netlify.app/

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

DoubleA @ AntManThePro · NExtended Xperimental USers
