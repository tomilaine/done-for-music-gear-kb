# Vocal mic setup in studio

Signal chain: sE Gemini II → Gemini II floor box (power supply) → UAD 6176 Mic input.

## UAD 6176 settings

- **+48V phantom: OFF (switch down).** The Gemini II is powered by its own floor box, not phantom. Applying +48V risks damaging the mic.
- Set +48V off before connecting or disconnecting the mic to avoid loud transients.
- Use Mic input (rear panel XLR). Pick 500 Ω or 2.0K Ω impedance to taste (Gemini II output impedance is 200 Ω, so 2.0K is the "by the book" choice).
- Engage the -15 dB pad on the 6176 only if you still get distortion at the lowest Gain setting.
- The 6176 mono output is marked in the patchbay.

## sE Gemini II

- Tube condenser, cardioid, externally powered via the included floor box and 8-pin cable.
- **Do not apply phantom voltage (+48V) from any interface or preamp.**
- Allow ~15 minutes warm-up before recording so the tubes stabilize.
- Attenuation switch: -10 dB pad on the mic body for loud sources or close-miking.
- Low-cut switch: 150 Hz, 6 dB/oct. Useful against wind, plosives, rumble, and to tame proximity effect.
- Max SPL: 135 dB (0 dB pad) / 145 dB (-10 dB pad).

## Power-on order

1. Connect IEC power, 8-pin cable (floor box to mic), and XLR (floor box to 6176 Mic input).
2. Confirm 6176 +48V is OFF.
3. Power on the Gemini II floor box.
4. Power on the 6176.
5. Wait ~15 minutes for tube warm-up before tracking.

Sources: `manuals/Microphone - SE Gemini-II-Manual.pdf` (Powering, Controls, Technical Specifications), `manuals/UAD_6176_compressor_preamp_Manual.pdf` (Front Panel controls 2, 3, 11).
