# Crash Remix 0.1.1-phase0

Corrected Phase 0 graybox build for Android device testing.

## Fixed

- Authored tuning resources now load from the exported Android package.
- The live-tuning HUD now shows the tuning fingerprint and all five resource
  paths instead of remaining at `Tuning not loaded`.
- Added an exported-pack startup smoke test so editor-only tests cannot miss
  this resource-loader difference again.

The environment remains deliberately monochrome because this phase tests
movement, camera, controls, and tuning in a graybox toybox.

## Requirements

- Android 10 or newer
- 64-bit ARM device
- About 81 MiB free for the APK, plus additional space for installation

## Verification

SHA-256:

`3a57f7d1d0e1bcaa17c9ab0e11059116f1ddf285ab236481ecf2cf1279814156`

The APK is a development build and is not distributed through Google Play.
