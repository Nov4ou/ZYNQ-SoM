# KiCad source

Open `ZYNQ-SoM.kicad_pro` with KiCad 10.0 or newer.

- `ZYNQ-SoM.kicad_sch` is the root schematic.
- `sheets/` contains the hierarchical schematic sheets.
- `ZYNQ-SoM.kicad_pcb` is the six-layer board layout.
- `ZYNQ-SoM.kicad_dru` contains project design rules.
- `lib/` contains the project-local KiCad symbols, `.pretty` footprint library, and 3D models.

Library tables use `${KIPRJMOD}` paths, so the project should be portable after cloning.
