# Project Notes

## Milestone 1 — verify the platform

Before implementing the clock, establish which AOD package format and resource structure are accepted by MIUI 12.5.5 on the Redmi Note 10. Do not treat an Android DreamService/screensaver as a native MIUI AOD.

Validation checklist:
- Identify the supported Xiaomi AOD authoring format and package structure.
- Confirm whether AOD resources can be imported independently through the Themes/AOD interface.
- Confirm whether a third-party or user-created AOD can be applied without root.
- Record regional/account restrictions that affect Theme Store distribution.
- Build a minimal test package before producing the full design.

## Milestone 2 — mechanical clock design

The reference composition is the source of truth:
- black AMOLED canvas;
- large mechanical dial on the left, cropped at the edges;
- large hour display;
- minute display inside a capsule;
- date, weekday, and battery indicator.

Color treatment:
- digits and minute capsule: champagne gold;
- dial: low-contrast gray;
- background: pure black.

Keep the clock readable and avoid unnecessary decoration.

## Milestone 3 — device testing

Test on the Redmi Note 10 / MIUI 12.5.5:
- package import;
- AOD activation and persistence;
- screen wake/sleep behavior;
- burn-in mitigation or element movement, if supported;
- battery impact;
- lock-screen/AOD transitions.

Record actual results. Do not claim Theme Store approval or device compatibility before verification.

## Milestone 4 — optional theme expansion

Only after the AOD works reliably, consider matching lock-screen styling, icons, wallpapers, and a separate landscape bedside concept. Landscape support may not be available in the native MIUI AOD system and must be tested independently.
