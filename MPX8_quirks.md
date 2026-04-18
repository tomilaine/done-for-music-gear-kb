# MPX8 Quirks

## MIDI Running Status Not Supported

**Description:**
The MPX-8 does not support MIDI Running Status, a standard optimisation used by most
hardware MIDI devices where consecutive same-type messages omit the repeated status byte.
This causes dropped or missed notes when the MPX-8 is driven by external hardware via
TRS or DIN MIDI, making it unreliable for sequenced use.

**Workarounds:**
- Route via a MIDI interface such as the U6MIDI Pro: since it processes messages
  internally and USB MIDI never uses Running Status, it will strip Running Status
  before messages reach the MPX-8
- Route via a computer, which achieves the same effect
- The third-party MPX-8 MIDI-FIX hardware mod (freshnelly.com) addresses this
  permanently at the hardware level
