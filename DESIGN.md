# Design — سبّح

## World
The courtyard of the Prophet's Mosque: cool marble, the umbrellas' fabric, bronze columns. Night theme is the courtyard after isha: blue-black sky, lit fabric, warm bronze. No stock ornament (domes, crescents, arabesque fills).

## Tokens
| Token | Light | Dark | Role |
|---|---|---|---|
| --ground | #F2F4F3 | #0D1420 | page (marble / night sky) |
| --vein | #E2E6E5 | #1A2534 | empty canopy, segmented track |
| --surface | #FAFBFA | #141E2C | secondary buttons, chips |
| --raised | #FFFFFF | #2B3A4E | selected segment |
| --membrane / --membrane-2 | #FFFDF6 / #F4EEE1 | #ECE6D8 / #D9D0BD | canopy fabric panels (alternating) |
| --bronze | #86633A | #C9A06A | primary action, ribs, wordmark, focus |
| --on-bronze | #FFFFFF | #0D1420 | text on bronze |
| --ink / --muted | #1B2838 / #556476 | #EDF0F3 / #9BA8B8 | text |
| --line | #D6D2C8 | #26313F | hairlines, borders |
| --ok | #2F6B4F | #7FC8A0 | completion status |

## Type
- UI: Almarai (400/700/800)
- Dhikr text: Noto Naskh Arabic 600, fully vocalized, clamp(28px, 8.4vw, 38px)
- Numerals and wordmark: Reem Kufi (500/700); count at 64px, Arabic-Indic digits, tabular

## Signature move
The count is a top-down umbrella canopy (16 ribs, square plan, sides bowing inward), drawn on canvas. Fabric fills panel by panel as the count rises; the canopy is partly folded when idle and opens fully while listening or when the target is reached, with a brief bloom on completion. Tapping it counts by hand.

## Layout
One screen, nothing else: the vocalized dhikr, the canopy, the count in Western digits ("19 / 33"). Tap canopy = start/stop voice counting; long-press canopy = reset; tap dhikr = next dhikr. A one-line hint fades out after first visit; errors reuse it. A three-dot button (top-left, RTL end) opens a bottom sheet (dialog) with: dhikr list with targets, counting method (burst / speech recognition) as a segmented control, sensitivity (burst only), switches for after-prayer sequence and vibration, and a reset button.

## Motion
Exponential ease toward targets (fill ~90ms, open ~160ms time constants). Reduced motion: instant.
