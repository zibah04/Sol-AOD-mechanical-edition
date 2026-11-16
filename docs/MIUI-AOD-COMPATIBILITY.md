# Native MIUI AOD compatibility

## What we have established

Xiaomi's theme documentation describes AOD themes as MAML-based, with an `Aod` root element in the AOD content manifest and a separate `aod_description.xml` file declaring the `maml_style` theme type and supported system switches.

The official guidance also states:
- AOD is display-only; sensor and button interactions are prohibited.
- First-display animation must finish within 4 seconds.
- Recommended maximum frame rate is 30 or 60.
- The system refreshes time about once per minute and shifts position about once every two minutes; MAML cannot override those intervals.
- AOD package size must remain below 10 MB.
- Battery and notification settings must be supported for submission.
- 12/24-hour time and date must display correctly.
- Non-black pixels should occupy no more than 15% of the display.
- Battery charging state must be designed and checked.

## Current prototype

- `aod/content/manifest.xml` — first MAML layout experiment.
- `aod/aod_description.xml` — system switch metadata.

This is source material, **not yet a validated installable AOD package**. The exact nested archive structure, editor export behavior, and compatibility with this specific Redmi Note 10 / MIUI 12.5.5 build still need validation.

## Required next tests

1. Open the source in Xiaomi's AOD Editor or a compatible current editor.
2. Resolve any parser errors and confirm all MAML attributes against the editor/runtime.
3. Export using the editor's supported package structure.
4. Import/apply on the Redmi Note 10 running MIUI 12.5.5.
5. Verify 12-hour and 24-hour time, date, battery, charging state, notification icons, screen burn-in movement, memory, and idle battery drain.
6. Keep the exported AOD module under 10 MB and inspect non-black pixel coverage.

## References

- Xiaomi official AOD grammar and review requirements:
  https://zhuti.designer.xiaomi.com/docs/grammar/
  https://zhuti.designer.xiaomi.com/docs/audit/aod.html
- English translation of Xiaomi's MAML grammar:
  https://nikiink.github.io/MAML-Grammar-en.htm
- Example AOD package structure (community reverse-engineering reference; verify before relying on it):
  https://www.cristianvicente.com/2022/12/06/temas-aod-en-miui/

Official review guidance can change. Re-check it before submission.
