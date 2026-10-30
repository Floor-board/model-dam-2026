# CAD Documentation

## Purpose

Store all CAD models, drawings, and exported design files here.

## Recommended structure

```text
cad/
├── models/
├── drawings/
├── exports/
└── README.md
```

## Naming conventions

Use clear file naming patterns, such as:

- `dam_assembly_v1_2026-10-30.sldprt`
- `spillway_section_a_a_rev02.pdf`
- `dam_plan_view_annotated.png`

## Notes

- Keep native CAD files in `models/`.
- Keep viewable exports in `drawings/` or `exports/`.
- Add revision numbers and dates to major files.
- Keep a short note for each model version if the geometry changes significantly.

## Suggested review process

- Save working files before major changes.
- Export a clean PDF or image for easy review.
- Document the reason for each revision in the changelog or design decisions file.
