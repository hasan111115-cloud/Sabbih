# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static single-file HTML/CSS/JS served from GitHub Pages (repo hasan111115-cloud/Sabbih). An Android build is planned later.

## Users

Muslims who recite dhikr and want the count kept for them while their hands and eyes are free. Used in general daily settings: after prayer, at home, on the move. Arabic-speaking (Saudi/Gulf), RTL interface.

## Product Purpose

«سبّح» is an electronic tasbih that counts dhikr by voice: the user picks a dhikr and its target, starts listening, recites aloud, and the counter advances on its own. Success: the count matches what was recited without touching the screen.

## Positioning

Counting by the reciter's own voice rather than by tapping. Two mechanisms: speech-burst detection (each utterance between pauses = one count, on-device, offline) and speech recognition (confirms the dhikr word, needs Chrome).

## Operating Context

Phone in hand or set down nearby; mobile browsers (Chrome on Android, Safari on iPhone — Safari has no vibration). Microphone requires https. Screen kept awake while listening.

## Capabilities and Constraints

- Preset adhkar with targets (33/33/34 after prayer, 100 for istighfar, tahlil, etc.); after-prayer sequence auto-advances.
- Manual tap counting as fallback; reset; next dhikr; sensitivity control for burst mode.
- Daily total kept in the browser (localStorage).
- Everything else in the current interface may change; function must stay.

## Brand Commitments

None binding. The name «سبّح» may change; current green/gold palette is not binding.

## Evidence on Hand

No testimonials, users, or statistics. Do not invent any.

## Product Principles

- The dhikr and the count are the whole point; everything else stays out of the way.
- Worship, not a game: no points, badges, streak pressure, or celebratory noise.
- Avoid stock Islamic ornament (domes, crescents, generic arabesque patterns).
- Private by default: audio stays on the device in burst mode.
