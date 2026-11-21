# Interactive 3D Dice — consolidated standalone package

Open **index.html**. The background is transparent and the canvas has no scenery, board, encounter UI, character sheets, mathematics reference, gameplay rules, or server integration.

## Included dice
d4, d6, d8, d10, d12, d20, and d100. The **d100** is presented using the source renderer's percentile tens die plus the d10 units die; it is not a 100-faced physical mesh. **All 7** displays the complete family (eight physical pieces because percentile uses two).

## Use
Click a size to throw that die, select a design to change its CSS-powered finish, or click **Roll**. Drag/swipe across the blank canvas to toss the current selection. On initial load the dice animate silently; subsequent gestures use the selected original sound. Auto sound chooses the matching source sound; **Muted** plays nothing.

## Files
- css/designs/*.css: **one separate CSS file for each of ten distinct designs**, not per die size.
- css/base.css: only basic layout, transparent stage and minimal controls.
- js/vendor/dice.js: one consolidated source renderer, with small presentation-only tweaks to allow unique color sequencing and truly muted audio.
- js/vendor/{three.min.js,cannon.min.js,teal.js}: supporting 3D and physics runtime.
- js/app.js: controls and resizing only; no tabletop rules or game-specific calculations.
- audio: original TableGate dice roll MP3 and original KillerInTheKeep role-specific dice WAVs.
- docs/LICENSES.md and docs/SOURCES.md: attribution and provenance.

## Original styles
TableGate Cyan; Daltu Yellow-Green; Noldrack Yellow-Gold; Eilvyre Navy; Korbin Lava Red; Jock Hot Pink; Xun Amethyst; Gunnus Black and Cyan; Monk Aged Copper; Monster Brown.

No duplicate renderer, no unrelated card assets, audio ambience, loot rules, characters, combat, scripts or supporting games.
