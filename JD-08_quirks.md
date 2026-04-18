# JD-08 Quirks

## Hardcoded Init Sound on MIDI Channels 4 and 5

**Description:**
The JD-08 responds to MIDI note messages on channels 4 and 5 with a hardcoded init
patch — a saw lead with portamento — regardless of the active patch or MIDI channel
settings. These channels cannot be disabled or reassigned. The issue stems from the
Jupiter-X engine the JD-08 is based on, which uses channels 4 and 5 internally.
Roland has acknowledged the bug but has not issued a fix as of 2026.

**Workaround:**
Do not send MIDI data on channels 4 and 5 to the JD-08.
