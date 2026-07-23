# Crash Remix 0.1.2-phase0

Phase 0 graybox update for Android device testing.

## Fixed

- Pressing SPIN now visibly rotates the player for the authored 0.45-second
  active window.
- The spin visual returns to its forward pose when the action ends or the
  player respawns.
- The existing 360-degree attack hitbox and airborne gravity stall remain
  connected to the same action.

This build includes the exported-tuning loading correction from `0.1.1`.

The environment remains deliberately monochrome because this phase tests
movement, camera, controls, and tuning in a graybox toybox.

## Requirements

- Android 10 or newer
- 64-bit ARM device
- About 81 MiB free for the APK, plus additional space for installation

## Verification

SHA-256:

`3e0e53e24afbf0199cf1f1dd362855ccd8a526533f5b4cd64d29135636cb164b`

The APK is a development build and is not distributed through Google Play.
