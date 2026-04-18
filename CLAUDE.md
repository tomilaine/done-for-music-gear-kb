**Rules:**
- Connectivity questions (audio, MIDI, patch points): check `connectivity_reference.md` first, then device manuals.
- If a device has an **(errata)** file, read it alongside the main manual.
- If a device has a **(quirks)** file, read it alongside the main manual and proactively flag any relevant caveats, bugs, or limitations.
- Never delete any files.
- Never modify the main manual files as those as from the manufacturer and the source of truth.
- Before editing any file, show the exact proposed changes to the user and wait for explicit approval. Never write to a file based on a general "yes, go ahead" — confirmation must be given after seeing the specific content. This rule includes the CLAUDE.md file.

**When a quirk is discovered:**
Step 1. Run this when user talks about a bug, problem or other weird thing about a particular and the quirk is not documented in the manual files of the device.
Step 2. Confirm from the user before moving forward that "Is this a new quirk that we should save for later reference?"
Step 3. Create `<DeviceName>_quirks.md` if it doesn't exist.
Step 4. Document the quirk with a short title, description, and workaround if known.
Step 5. Add the file to the device table with the `(quirks)` tag if it doesn't exist yet.

**When a new device is added:**
- Add a row to the device table with manufacturer and all available manual files, tagged appropriately.
- Add the device's connectivity info to `connectivity_reference.md` while keeping the existing formatting of the file.

| Device | Manufacturer | Manual File(s) |
|---|---|---|
| TR-09 | Roland | `TR-09_eng03_W.pdf` (main), `TR-09_MIDI_Imple_e01_W.pdf` (MIDI ref), `TR-09_AddFunc_Errata_e01_W.pdf` (errata) |
| TB-03 | Roland | `TB-03_eng03_W.pdf` (main), `TB-03_MIDI_Imple_e01_W.pdf` (MIDI ref) |
| JX-03 | Roland | `JX-03_e02_W.pdf` (main), `JX-03_MIDI_Imple_e02_W.pdf` (MIDI ref) |
| VT-4 | Roland | `VT-4_manual_eng04_W.pdf` (main), `VT-4_MIDI_Implementation_eng02_W.pdf` (MIDI ref), `VT-4_BlockDiagram_for_Audio_Chain_eng02_W.pdf` (audio chain) |
| JD-08 | Roland | `JD-08_reference_eng01_W.pdf` (main) |
| KeyStep | Arturia | `KeyStep_Manual_1_1_2_EN.pdf` (main) |
| MicroBrute | Arturia | `MicroBrute_Manual_1_1_0_EN.pdf` (main) |
| Model D | Behringer | `Manual_Behringer_Model_D.pdf` (main) |
| LiveTrak L6 | Zoom | `Zoom_livetrak_L6_mixer.pdf` (main) |
| Central Station Plus | PreSonus | `Presonus_Central-Station-PLUS_OM_2777400201_EN.pdf` (main) |
| 6176 | UAD | `UAD_6176_compressor_preamp_Manual.pdf` (main) |
| MPX8 | Akai | `Akai_MPX-8_manual.pdf` (main) |
| SR16 | Alesis | `SR16 Reference Rev C.pdf` (main) |
| SV130 Electric Violin | Yamaha | `Yamaha_Electric_Violin_SV130_WN46910_R2_en.pdf` (main) |
| MDCB2 (Juno-60 MIDI/DCB) | — | `MDCB-2_Juno60_MIDI_to_DCB_interface.pdf` (main) |
| U6MIDI Pro | CME | `U6MIDI-Pro-user-manual_English_v06.pdf` (main) |
