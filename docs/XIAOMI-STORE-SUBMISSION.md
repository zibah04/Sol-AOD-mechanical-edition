# Sol — Mechanical Edition: Xiaomi Themes Store submission guide

## Release identity
- Theme name: **Sol Mechanical Edition**
- Designer / publisher name: **Sol Studio** (use the exact approved designer name on every submission)
- Release price: Free
- Initial target: Redmi Note 10 (sunny), MIUI 12.5.5 / Android 11, 1080 × 2400
- Visual identity: pure AMOLED black, restrained graphite mechanical dial, champagne gold (#C6A15B), quiet grey secondary text.
- Main AOD: oversized mechanical dial cropped off the left edge; large gold hour digits; gold minute capsule; curved minute numerals; live weekday/date; battery and system notification icons.

## Current status — not upload-ready yet
The repository contains an initial MAML layout prototype and AOD metadata. The prototype has **not** been parsed by Xiaomi's editor, exported as a final theme package, or validated on the Redmi Note 10. It must not be submitted as a finished theme yet.

A proper submission needs:
1. A valid native Xiaomi theme package created/exported with the supported Theme Editor workflow.
2. A valid AOD module, including battery and notification switches and a charging-state design.
3. Matching theme resources (lock screen, wallpapers, icons and supported system modules) with consistent styling.
4. Preview screenshots and complete copyright/source evidence.
5. Real-device testing and a final review pass.

## Xiaomi's published review limits and checks
Check the current official guidelines again immediately before submission. The current published AOD rules include:
- AOD module must be no larger than 10 MB.
- Theme package must be no larger than 80 MB.
- Battery and notification switches must be supported.
- A charging-state appearance must be designed.
- Correct 12-hour / 24-hour time and date.
- First-display animation, if used, must finish within 4 seconds.
- Display-only AOD: no sensor or button-triggered navigation.
- Recommended frame rate: 30 or 60 FPS.
- AOD memory use must not exceed 200 MB.
- Non-black pixels should occupy no more than 15% of the display.
- Notification icons should use the system's default icon treatment.
- Theme name, AOD name and package description must be consistent.
- Theme content must be original or properly licensed.

Official references:
- Theme Design Station: https://zhuti.designer.intl.xiaomi.com/
- International Theme Editor guide: https://zhuti.designer.intl.xiaomi.com/tutorial/guide/
- International theme review guidelines: https://in.zhuti.designer.intl.xiaomi.com/tutorial/audit/
- AOD review guidelines: https://zhuti.designer.xiaomi.com/docs/audit/aod.html
- MAML grammar: https://zhuti.designer.xiaomi.com/docs/grammar/

## Submission preparation

### 1. Designer account
1. Open the Theme Design Station.
2. Sign in with a Mi Account.
3. Complete the designer registration / qualification process shown in the portal.
4. Use the same designer/publisher name consistently in the portal, package metadata and AOD submission.
5. Select free publishing. Xiaomi's publisher agreement distinguishes registered designers (free content) from certified designers (free or paid content).

### 2. Finish and validate the theme locally
1. Download the Theme Editor from the official Theme Design Station guide.
2. Extract it to a simple Windows path with no special characters, for example C:\XiaomiThemeEditor.
3. Open the project in the editor and use its supported project/package workflow. Do not hand-invent the final archive structure.
4. Import/author the AOD using the editor's supported AOD workflow and correct any parser errors.
5. Complete the matching lock screen, wallpaper, icon and supported system resources.
6. Connect the Redmi Note 10 over USB with USB debugging enabled for editor preview/testing.
7. Test time in 12-hour and 24-hour modes, date, battery, charging state, notification icons, screen shifting, memory and idle power use.
8. Export the final theme package and verify the AOD module is under 10 MB and the full theme is under 80 MB.

### 3. Copyright evidence
Create a ZIP containing:
- Editable original source files for the clock artwork, icons, wallpaper and other original assets.
- Any original vector/source design files and working files.
- A list of fonts and their licences / commercial-use permissions.
- For any third-party material, the source URL and licence/permission evidence.
- A short asset register stating which files were created by Sol Studio.

Do not submit stock assets, fonts, icons or images without rights that permit theme-store distribution.

### 4. Upload and submit
1. Sign in at https://zhuti.designer.xiaomi.com/
2. Open the theme submission/upload area.
3. Upload the exported theme package.
4. Enter the exact theme name **Sol Mechanical Edition** and the approved designer name.
5. Add a concise, accurate description and relevant tags.
6. Upload the copyright-evidence ZIP in the copyright-material section.
7. Upload the requested preview screenshots and complete all required metadata.
8. Submit for review. Do not advertise it as available until Xiaomi approves and publishes it.

Suggested short description:
"An understated mechanical timepiece theme in deep black, graphite and champagne gold, with a precision-inspired clock face and coordinated screen styling."

Suggested tags should reflect only finished features. For the AOD, Xiaomi's AOD guidance asks for category and feature tags; suitable candidates once verified are:
- Category: 表盘时钟 / Dial clock
- Feature: 时间息屏 / Time-based AOD
- Style: 极简 / Minimal; 质感 / Premium texture

Use the tag options actually offered in the portal; do not invent unavailable tags.

## Before final submission
- [ ] AOD opens in the official editor without parser errors.
- [ ] AOD is no larger than 10 MB.
- [ ] Whole theme package is no larger than 80 MB.
- [ ] 12/24-hour clock works.
- [ ] Date and weekday are correct.
- [ ] Battery switch works.
- [ ] Charging state is designed and tested.
- [ ] Notification switch works and uses default system icons.
- [ ] AOD first animation (if any) is no longer than 4 seconds.
- [ ] Non-black pixel coverage is within Xiaomi's 15% guideline.
- [ ] AOD memory use is below 200 MB.
- [ ] Lock screen unlock and notification interactions work.
- [ ] Wallpapers and icons display correctly at target resolutions.
- [ ] Theme/AOD names and designer name match in all locations.
- [ ] Copyright/source ZIP is complete.
- [ ] Tested on a real device before upload.

## Important distribution note
The Xiaomi publisher agreement contains platform-specific intellectual-property and distribution terms. Read the agreement presented during registration before publishing the theme elsewhere or reusing the same/similar theme assets on another store. This repository guide is not legal advice.
