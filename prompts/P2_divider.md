# P2 — Resistive voltage divider 12 V → 5 V (MCU ADC)

Design a tiny KiCad schematic: resistive voltage divider that scales **12 V** down to **~5 V** suitable as an MCU ADC input (assume ADC max ≈ 5.0 V, high-Z).

## Requirements
- Input: `VIN_12V` (or `+12V`) and `GND`.
- Output: `ADC_5V` net at ~5 V when VIN=12 V.
- Two resistors with **named values** chosen so Vout = Vin * Rbot/(Rtop+Rbot) ≈ 5 V. Prefer standard E24 values and total divider current in a sensible range (~0.1–1 mA).
- Optional but good: note input impedance / loading; keep it simple (no op-amp).
- Power symbols / hierarchical labels as appropriate.

## Ki-Stack
Use `./Ki-Stack/skills/ki-stack/` (schematic + file surgery + ethos). Emit a real `.kicad_sch`.

## Deliverables (write under `./runs/p2/`)
1. `schematic.kicad_sch`
2. `NETLIST.md` — components, values, expected voltages, connectivity
3. `NOTES.md` — divider math and why values are ADC-safe
4. `TIMING.txt` — wall-clock seconds

Do not ask questions; produce the files.
