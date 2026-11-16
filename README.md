# Sol AOD — Mechanical Edition

A minimalist, premium mechanical Always-On Display concept for Xiaomi devices, beginning with the **Redmi Note 10 running MIUI 12.5.5**.

## Design direction

- Pure-black AMOLED background.
- Oversized mechanical dial positioned on the left, intentionally cropped by the screen edges.
- Large champagne-gold hour digits and a matching minute capsule.
- Mechanical dial rendered in restrained, subtle gray so it supports rather than competes with the time.
- Compact date, weekday, and battery information.
- Portrait AOD as the primary layout; a landscape bedside layout is a separate exploration.

## Project approach

The first milestone is to validate the native Xiaomi AOD/theme format and the installation path on the target phone. The project will keep the following deliverables separate:

1. **Design assets** — source artwork, previews, and export-ready images.
2. **AOD implementation** — Xiaomi-compatible resources and configuration, once the supported format is verified.
3. **Theme integration** — optional lock screen, icons, and other theme components after the AOD milestone.
4. **Testing notes** — device, MIUI version, installation steps, known limitations, and test results.

> Compatibility is not assumed until tested on the target device. In particular, a full MIUI AOD replacement and an Android screensaver are different implementations.

## Target device

- Xiaomi Redmi Note 10
- MIUI 12.5.5
- Android 11
- No root access intended

## Repository layout

- `docs/` — design and implementation notes
- `assets/source/` — editable source artwork
- `assets/previews/` — screenshots and exported previews
- `aod/` — native AOD implementation (format to be verified)
- `theme/` — optional full-theme integration

## Status

**Phase 0 — project setup.** Design direction recorded; native MIUI packaging and AOD compatibility validation are next.
