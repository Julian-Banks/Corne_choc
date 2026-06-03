# PCB

This build uses the **Corne Chocoflan** (rev2) wireless, choc-spaced PCB — the board that was actually fabricated for this keyboard. The design files are vendored here from the upstream open-source repo.

**Credit:** PCB design by [ergomechstore — Corne-chocoflan](https://github.com/ergomechstore/Corne-chocoflan). All design files in this folder originate from that project.

## What's here — `Corne-chocoflan/`

- `gerber/rev2/corne_chocoflan_gerbers.zip` — **production Gerbers** (upload this to JLCPCB / your fab).
- `gerber/rev2/corne_chocoflan_gerbers/` — the unzipped Gerber + drill files.
- `gerber/rev2/bom_pos/` — BOM and pick-and-place (POS) CSVs for assembly.
- `gerber/rev2/ibom.html` — interactive BOM (open in a browser for placement reference).
- `gerber/rev2/corne_chocoflan.step` — 3D model of the board.
- `pcb/rev2/` — KiCad source (`.kicad_pcb`, `.kicad_sch`, `.kicad_pro`) if you need to edit the design.

KiCad auto-save backups and `.git` history from the upstream clone were dropped to keep the repo lean.
