# P3 — Simple RC low-pass filter for audio (~1 kHz cutoff)

Design a tiny KiCad schematic: first-order passive **RC low-pass filter** for audio with cutoff **≈ 1 kHz**.

## Requirements
- Signal path: `AUDIO_IN` → series R → node `AUDIO_OUT` with C to `GND`.
- Choose **named values** so fc = 1/(2πRC) ≈ 1 kHz (state the exact fc).
- Label nets clearly; include GND.
- Keep it a simple single-pole LPF (no active filter).

## Ki-Stack
Use `./Ki-Stack/skills/ki-stack/` skills/docs. Emit a real `.kicad_sch`.

## Deliverables (write under `./runs/p3/`)
1. `schematic.kicad_sch`
2. `NETLIST.md` — components, values, fc calculation, connectivity
3. `NOTES.md` — design notes (impedance, audio suitability caveats)
4. `TIMING.txt` — wall-clock seconds

Do not ask questions; produce the files.
