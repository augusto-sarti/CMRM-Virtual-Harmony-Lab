# CMRM Harmony Lab — Module 1: Voice Leading

Complete first teaching module for Chapter 5, built on the pitch-verified local piano-WAV engine.

## Run locally

1. Extract the entire ZIP.
2. Keep `index.html`, `samples/`, and `assets/` together.
3. Open `index.html` in a current browser.

## Included teaching functions

- fixed Dm7 → G7 → Cmaj7 harmonic identity
- four curated voicings
- constrained random voicing generation
- exact-note sampled piano playback
- guide-tone highlighting and isolated playback
- ordered voice trajectories
- total voice movement and maximum leap descriptors
- A/B storage and listening comparison
- reset control
- hidden exact pitch/MIDI/WAV diagnostics
- “what changed / what remained invariant?” reflection
- course-material connection to the supplied ’Round Midnight excerpt

## Audio integrity

The app never pitch-shifts audio at runtime. Every sounding note maps directly to `samples/<MIDI>.wav`. Random voicings can only use MIDI notes for which a verified local WAV is present, and every realization is revalidated against the intended pitch classes before playback.
