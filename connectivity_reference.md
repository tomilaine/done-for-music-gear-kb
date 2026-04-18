# Gear Connectivity Reference

---

## TR-09 (Roland)

**Audio**

| Port | Type | Notes |
|---|---|---|
| MIX IN | 3.5mm TRS | Stereo line level input, passed through to OUTPUT and PHONES |
| OUTPUT | 3.5mm TRS | Stereo line level output. Can be split L/R for two parallel mono outs |
| PHONES | 3.5mm TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | |
| MIDI OUT / THRU | 5-pin DIN | Soft Thru on by default (retransmits MIDI IN). Clock only transmitted while sequencer is running |
| USB | Micro USB | USB MIDI + USB audio to computer. 5 audio outputs over USB (1 mix + 4 parallel). Data-capable cable required |
| TRIGGER OUT | 3.5mm TS | Trigger pulse output. Steps at which trigger fires are programmable. Use mono cable only |

---

## TB-03 (Roland)

**Audio**

| Port | Type | Notes |
|---|---|---|
| MIX IN | 3.5mm TRS | Stereo line level input, passed through to OUTPUT and PHONES |
| OUTPUT | 3.5mm TRS | Stereo line level output |
| PHONES | 3.5mm TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | |
| MIDI OUT / THRU | 5-pin DIN | Soft Thru on by default (retransmits MIDI IN). Clock only transmitted while sequencer is running |
| USB | Micro USB | USB MIDI + USB audio to computer. Data-capable cable required |
| CV OUTPUT | 3.5mm TS | Pitch CV output. 1V/Oct only, range -1V to +7V. Hz/V not supported |
| GATE OUTPUT | 3.5mm TS | Note on/off signal. +12V during note-on (V-trig) |
| TRIGGER IN | 3.5mm TS | Accepts trigger pulses to advance steps. Disconnects internal clock when plugged in |

> **Note:** Use mono TS cables only on CV, GATE and TRIGGER jacks — stereo plugs will not work correctly.

---

## JX-03 (Roland)

**Audio**

| Port | Type | Notes |
|---|---|---|
| INPUT | 3.5mm TRS | Stereo line level input |
| OUTPUT | 3.5mm TRS | Stereo line level output |
| PHONES | 3.5mm TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | |
| MIDI OUT / THRU | 5-pin DIN | Chain mode available: 5th voice and beyond passed thru via MIDI OUT to a second JX-03 unit |
| USB | Micro USB | USB MIDI + USB audio to computer. Data-capable cable required |

> **Note:** No CV or trigger connections. Polyphony can be expanded by chaining two JX-03 units via MIDI.

---

## VT-4 (Roland)

**Audio**

| Port | Type | Notes |
|---|---|---|
| MIC IN (front) | 3.5mm TRS | Mic level input. Plug-in power compatible mics only |
| MIC IN (rear) | XLR | Mic level input. Phantom power (+48V) available for condenser mics. TRS plug on same jack does not receive phantom power |
| LINE OUT L/R | 1/4" TRS | Stereo line level output. Switchable between stereo or L/MONO (processed) + R/BYPASS (dry) |
| PHONES | 3.5mm TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | Receives note messages to trigger robot voice and other effects |
| USB | Micro USB | USB MIDI + 6-channel USB audio interface to computer. Playback routes: OUT (1–2) dry, TO MIC IN (3–4), TO CARRIER (5–6). Record routes: MIX (1–2), WET (3–4), DRY (5–6). Data-capable cable required |

---

## KeyStep (Arturia)

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | |
| MIDI OUT | 5-pin DIN | |
| SYNC IN | 3.5mm TS/TRS | Accepts analog sync clock. TS carries clock pulse only; TRS carries clock + start/stop |
| SYNC OUT | 3.5mm TS/TRS | Outputs analog sync clock. TS carries clock pulse only; TRS carries clock + start/stop |
| PITCH (CV OUT) | 3.5mm TS | Pitch CV output. Configurable: 1V/Oct (0-10V) or Hz/V (max ~12V) |
| GATE OUT | 3.5mm TS | Gate output. Configurable: V-trig 5V, V-trig 12V, or S-trig |
| MOD OUT | 3.5mm TS | Modulation CV output. Configurable source (mod strip, velocity, aftertouch) and voltage range 0-12V |
| SUSTAIN | 3.5mm TS | Momentary footswitch input |
| USB | USB Type-B | USB MIDI to computer. Also powers the unit |

> **Note:** Sync source (Internal / USB / MIDI / Sync In) selected via rear panel slider switches.

---

## MicroBrute (Arturia)

**Audio**

| Port | Type | Notes |
|---|---|---|
| AUDIO IN | 1/4" TS | Mono line level input. Routes into filter and amplifier. Can trigger envelopes |
| LINE OUT | 1/4" TS | Mono line level output |
| PHONES | 3.5mm TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | |
| PITCH OUT | 3.5mm TS | Keyboard pitch CV output. 1V/Oct standard |
| GATE OUT | 1/4" TS | Keyboard gate output. 0-10V positive V-trig |
| GATE IN | 3.5mm TS | Gate input from external devices to trigger envelopes |
| USB | USB Type-B | USB MIDI to computer. Also used for MicroBrute Connection software |

**Patch Points**

| Port | Type | Notes |
|---|---|---|
| ENV OUT | 3.5mm TS | Envelope CV output |
| LFO OUT | 3.5mm TS | LFO CV output |
| METAL IN | 3.5mm TS | CV input to Metalizer (triangle wave shape) |
| SAW IN | 3.5mm TS | CV input to Ultrasaw animator rate |
| PITCH IN | 3.5mm TS | CV input to oscillator pitch |
| FILTER IN | 3.5mm TS | CV input to filter cutoff |

> **Note:** All patch point jacks are 3.5mm TS, 1V/Oct standard. CV output can drive up to 4 inputs. Patching into a source jack breaks the default internal routing.

---

## Model D (Behringer)

**Audio**

| Port | Type | Notes |
|---|---|---|
| EXT IN | 3.5mm TS | Mono audio input into the mixer section |
| MAIN OUT LOW | 1/4" TS | Mono instrument level output. For guitar amps or instrument-level mixer inputs |
| MAIN OUT HIGH | 1/4" TS | Mono line level output. For line-level mixer inputs, keyboard amps, powered speakers |
| MAIN OUT (front) | 3.5mm TRS | Mono output used when installed in Eurorack. Replaces rear outputs in that configuration |
| PHONES | 3.5mm TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | |
| MIDI THRU | 5-pin DIN | Hardware MIDI Thru (not software-switchable) |
| USB | USB Type-B | USB MIDI in/out to computer. Used for SysEx configuration only — knob movements not transmitted. Class compliant, no driver required |

**Patch Points**

| Port | Type | Notes |
|---|---|---|
| OSC 1 V/OCT | 3.5mm TS | Pitch CV input for oscillator 1. 1V/Oct |
| LFO CV | 3.5mm TS | LFO CV output. ±2V |
| FC GATE | 3.5mm TS | Filter contour gate input. +5V triggers |
| LG GATE | 3.5mm TS | Loudness contour gate input. +5V triggers |
| CUT CV | 3.5mm TS | CV input to filter cutoff frequency. 0 to +5V |
| FILT CONT | 3.5mm TS | Filter contour CV output. 0 to +4V |
| LOUD CONT | 3.5mm TS | Loudness contour CV output. 0 to +4.6V |

> **Note:** No MIDI OUT on DIN. MIDI channel set via 4 rear panel DIP switches. Multiple units can be Poly Chained via MIDI for up to 16-voice polyphony.

---

## LiveTrak L6 (Zoom)

**Audio**

| Port | Type | Notes |
|---|---|---|
| INPUT 1 | XLR/TRS combo | Mono mic or line level input. Phantom power (+48V) available. Dual A/D converter — no gain adjustment needed |
| INPUT 2 | XLR/TRS combo | Mono mic or line level input. Phantom power (+48V) available. Dual A/D converter — no gain adjustment needed |
| INPUT 3 L | 1/4" TS | Left input of stereo channel 3. Line level |
| INPUT 3 R | 1/4" TS | Right input of stereo channel 3. Line level. Channel switchable to two independent mono inputs |
| INPUT 4 L | 1/4" TS | Left input of stereo channel 4. Line level |
| INPUT 4 R | 1/4" TS | Right input of stereo channel 4. Line level. Channel switchable to two independent mono inputs |
| INPUT 5 L (MONO) | 1/4" TS | Left/mono input of stereo channel 5. Line level. Can be switched to receive USB audio from computer instead |
| INPUT 5 R | 1/4" TS | Right input of stereo channel 5. Line level |
| INPUT 6 L (MONO) | 1/4" TS | Left/mono input of stereo channel 6. Line level. Can be switched to receive USB audio from computer instead |
| INPUT 6 R | 1/4" TS | Right input of stereo channel 6. Line level |
| AUX SEND 1 | 1/4" TRS | Mono send output for external effect 1 |
| AUX SEND 2 | 1/4" TRS | Mono send output for external effect 2 |
| MASTER L | 1/4" TRS | Left stereo line level output. Main mix |
| MASTER R | 1/4" TRS | Right stereo line level output. Main mix |
| MONITOR | 1/4" TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 3.5mm TRS | Type-A TRS MIDI. Requires DIN-to-TRS adapter for standard MIDI cables |
| MIDI OUT | 3.5mm TRS | Type-A TRS MIDI. Requires DIN-to-TRS adapter for standard MIDI cables |
| USB | USB Type-C | USB MIDI + USB audio interface to computer/smartphone. Also powers the unit |

> **Note:** Passive guitar/bass not supported on any input — use a DI box or effects unit first.

---

## MPX8 (Akai)

**Audio**

| Port | Type | Notes |
|---|---|---|
| MAIN OUT L | 1/4" TS | Main mix, left channel. Use left only for mono |
| MAIN OUT R | 1/4" TS | Main mix, right channel |
| PHONES | 3.5mm TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 3.5mm TRS | Receives note messages to trigger pads. Fixed to channel 10 — cannot be changed. Requires 3.5mm-to-DIN adapter for standard MIDI cables |
| MIDI OUT | 3.5mm TRS | Sends note on and polyphonic aftertouch. Requires 3.5mm-to-DIN adapter for standard MIDI cables |
| USB | USB Type-B | USB MIDI to computer. Also powers the unit |

> **Note:** No audio input. Samples loaded via SD card only.

---

## SR16 (Alesis)

**Audio**

| Port | Type | Notes |
|---|---|---|
| MAIN LEFT | 1/4" TS | Main mix, left channel |
| MAIN RIGHT | 1/4" TS | Main mix, right channel |
| AUX L/R | 1/4" TRS | Single stereo aux mix output. Individual voices can be assigned here |
| HEADPHONES | 1/4" TRS | Headphone output |
| TAPE IN/OUT | 3.5mm TRS | Data backup/restore to tape recorder or computer |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | Receives note and clock messages |
| MIDI OUT / THRU | 5-pin DIN | Transmits SR-16 note and clock data. Switchable to merge mode which combines MIDI IN data with SR-16 output |
| START/STOP | 1/4" TS | Footswitch input. Starts and stops the sequencer |
| COUNT/A/B/FILL | 1/4" TS | Footswitch input. Selects pattern variations during playback |

---

## SV130 Electric Violin (Yamaha)

**Audio**

| Port | Type | Notes |
|---|---|---|
| AUX IN | 3.5mm TRS | Stereo line level input. For playing along with external audio source. Level controlled by AUX VOL knob |
| LINE OUT | 1/4" TRS | Stereo line level output. Instrument signal with onboard reverb/processing |
| PHONES | 3.5mm TRS | Headphone output |

> **Note:** No MIDI or USB. Do not return the LINE OUT signal back to the AUX IN — this will cause feedback and may damage the internal electronics. Use only the specific cable type supplied, as some 3.5mm plugs with wider bases may not make proper contact.

---

## MDCB2 (CHD Elektroservis — Juno-60 MIDI/DCB Interface)

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | Receives MIDI data and converts to DCB and control signals for the Juno-60 |
| MIDI OUT | 5-pin DIN | Can retransmit DCB data from the Juno-60 as MIDI |
| DCB IN/OUT | DIN-7 | Connects to Juno-60 DCB port. Requires a special DIN-7 cable — standard DIN cables will not work |
| VCF CV OUT | 1/4" TS | CV output for Juno-60 VCF CONTROL input. Carries velocity, aftertouch and modulation data |
| HOLD OUT | 1/4" TS | Connects to Juno-60 PEDAL HOLD input. Controlled by MIDI CC 64 |
| PATCH OUT | 1/4" TS | Connects to Juno-60 PATCH SHIFT input. Triggered by MIDI Program Change |
| ARPG OUT | 1/4" TS | Connects to Juno-60 ARPEGGIO CLOCK IN. Carries converted MIDI clock |

> **Note:** No audio connectivity. Pure MIDI-to-DCB protocol converter. Not all cables need to be connected — only those for the features you want to use.

## JD-08 (Roland)

**Audio**

| Port | Type | Notes |
|---|---|---|
| MIX IN | 3.5mm TRS | Stereo line level input, passed through to OUTPUT and PHONES |
| OUTPUT | 3.5mm TRS | Stereo line level output. Connect to amp or monitor speakers |
| PHONES | 3.5mm TRS | Headphone output |

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN | 5-pin DIN | Do not send on channels 4 or 5 — see JD-08_quirks.md |
| MIDI OUT | 5-pin DIN | |
| USB | USB Type-C | USB MIDI + USB audio to computer. Driver required (download from roland.com/global/support). Data-capable cable required |
| EXT CLK IN | 3.5mm TS | Analog clock input on front panel. Syncs the step sequencer to an external pulse |

---

## U6MIDI Pro (CME)

**MIDI / Sync**

| Port | Type | Notes |
|---|---|---|
| MIDI IN 1 | 5-pin DIN | |
| MIDI IN 2 | 5-pin DIN | |
| MIDI IN 3 | 5-pin DIN | |
| MIDI OUT 1 | 5-pin DIN | |
| MIDI OUT 2 | 5-pin DIN | |
| MIDI OUT 3 | 5-pin DIN | |
| USB | USB-C | USB MIDI to computer. Also powers the unit. Class compliant, no driver required |

> **Note:** No audio connectivity. Can operate standalone as a MIDI merger, splitter and router without a computer — powered by USB charger or power bank. Routing, remapping and filtering configurable via free UxMIDI Tools software. The USB port is not a USB host — cannot connect MIDI controllers via USB directly.
