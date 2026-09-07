# kicad-fable-eval

Overnight eval: Claude Fable 5.1 as a KiCad text→circuit compiler using [Ki-Stack](https://github.com/Milind220/Ki-Stack).

Source claim: [@i2cjak](https://x.com/i2cjak/status/2095216197327298759).

## Layout
- `prompts/` — P1 LED, P2 divider, P3 RC LPF
- `runs/pN/` — schematic + netlist + notes + timing
- `EVAL_SHEET.md` — scored keep/kill (filled by parent after run)
