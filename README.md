# Model Dam 2026

A documentation repository for the design, analysis, build, and testing of a model dam project.

## Project purpose

This repository captures the engineering process behind a model dam design, including CAD work, hydraulic calculations, electrical schematics, and operational testing notes. The goal is to provide a clear record of the design decisions, assumptions, calculations, and iterations involved in creating the dam.

## Project goals

- Document the design rationale and engineering assumptions.
- Track drawings, calculations, and revisions over time.
- Store CAD files and exported design views in a structured way.
- Maintain a clear record of water flow analysis and hydraulic estimates.
- Record electrical and control system design for pumps, sensors, or automation.
- Preserve build and testing notes to support future improvements.

## Repository structure

```text
model-dam-2026/
├── README.md
├── docs/
│   ├── project-overview.md
│   ├── requirements.md
│   ├── design-decisions.md
│   └── changelog.md
├── cad/
│   ├── README.md
│   ├── models/
│   ├── drawings/
│   └── exports/
├── calculations/
│   ├── README.md
│   ├── hydrology/
│   └── flow-rate/
├── water-dynamics/
│   └── README.md
├── electrical/
│   ├── README.md
│   ├── schematics/
│   └── wiring/
├── fabrication/
│   └── README.md
├── testing/
│   └── README.md
├── photos/
│   └── README.md
├── .gitignore
└── LICENSE
```

## Recommended documentation workflow

1. Start in `docs/` with the design intent and requirements.
2. Add CAD files under `cad/` with revision numbers and dates.
3. Document calculations under `calculations/`.
4. Record fluid behaviour and model testing in `water-dynamics/`.
5. Add electrical layouts and control logic in `electrical/`.
6. Log build and testing updates in `docs/changelog.md`.
7. Keep progress photos in `photos/` with clear labels.

## Documentation standards

- Use consistent units throughout all calculations.
- Label drawings with revision numbers and dates.
- Record assumptions explicitly in each calculation file.
- Keep a clean distinction between design intent, calculated values, and tested results.
- Use dated files or changelog entries for modifications.

## Suggested file naming convention

- `dam_assembly_v1_2026-10-30.sldprt`
- `dam_plan_view_rev03.pdf`
- `flow_rate_calculation_01.md`
- `spillway_analysis_v2.xlsx`
- `electrical_control_diagram_rev01.pdf`

## Status

This repository is currently a project scaffold intended for ongoing documentation and engineering records.

## Notes

This is a model dam project, so the documentation should include engineering assumptions, design trade-offs, safety factors, and real observed performance. If the design evolves, update the revision history and reflect it in the relevant calculation and drawing files.

## Next steps

- Add project overview and requirements.
- Add initial CAD concepts.
- Record initial hydraulic assumptions.
- Build out the electrical and testing sections.

---

For a detailed project overview, see [docs/project-overview.md](docs/project-overview.md).

