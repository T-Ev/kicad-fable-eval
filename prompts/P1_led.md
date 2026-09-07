# P1 — LED + current-limiting resistor (3.3 V)

Design a tiny KiCad schematic for an LED indicator driven from a **3.3 V** rail with a series current-limiting resistor.

## Requirements
- Power: `+3V3` and `GND` power symbols.
- Parts: one LED (e.g. red, ~2.0 V Vf), one resistor. **Name concrete values** (e.g. R1 = 330 Ω for ~4 mA).
- Net connectivity must be electrically correct: 3V3 → R → LED anode → LED cathode → GND (or equivalent correct polarity).
- Annotate reference designators and values.

## Ki-Stack
Use the Ki-Stack skills/docs at `./Ki-Stack/skills/ki-stack/` (especially `ki-stack-schematic`, `ki-stack-file-surgery`, `ETHOS.md`). Prefer emitting a valid KiCad 8/9 `.kicad_sch` via file surgery / templates rather than inventing unsupported IPC calls.

## Deliverables (write under `./runs/p1/`)
1. `schematic.kicad_sch` — valid KiCad schematic
2. `NETLIST.md` — human-readable netlist summary (components, values, nets, connectivity)
3. `NOTES.md` — brief design rationale (current calc, assumptions)
4. `TIMING.txt` — wall-clock seconds

Do not ask questions; produce the files.
