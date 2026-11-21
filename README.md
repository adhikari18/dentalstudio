# Dental Procedure Visualization Studio

An offline browser-based tool for creating educational 2D and 3D
visualizations of fictional dental conditions and procedures.

The studio will let an author build a synthetic dental case, choose a procedure
to illustrate, and walk through the change using an interactive model,
cross-sections, measurements, and before-and-after views. The same scenario
will drive the 3D scene, 2D diagrams, timeline, and exported report.

## Project goals

- Generate synthetic teeth, roots, gums, and upper and lower dental arches.
- Apply configurable condition modifiers to one or more teeth.
- Show user-selected procedures as clear, inspectable stages.
- Keep the 2D view, 3D model, timeline, and report in sync.
- Save, reload, and replay scenarios deterministically.
- Export clearly labeled SVG and PDF educational summaries.
- Run completely offline without cloud services or real patient data.

The first version will cover at least six conditions and six procedure
demonstrations. It will be tested with at least 100 generated scenarios,
geometry checks, save-and-load tests, export tests, and an end-to-end browser
test.

## Planned sessions

1. Define the scenario format, tooth numbering, procedure stages, validation,
   and test fixtures.
2. Generate synthetic teeth, roots, dental arches, and gums, with checks for
   repeatable and valid geometry.
3. Build the interactive 3D viewer with selection, camera controls,
   transparency, measurements, and cross-sections.
4. Add the first conditions and procedure demonstrations, plus a timeline and
   side-by-side comparison.
5. Build the authoring interface and matching 2D diagrams, with local storage,
   history, annotations, and educational disclaimers.
6. Add SVG and PDF export, run the generated scenario and browser test suites,
   fix geometry edge cases, and complete the offline demo.

## Safety and privacy

This project is an educational visualization system, not a medical device.

- It uses only procedurally generated fictional anatomy and scenarios.
- It does not use real or de-identified patient records, images, X-rays, scans,
  impressions, or treatment plans.
- It does not diagnose conditions, recommend or rank treatments, determine
  clinical suitability, or predict patient-specific outcomes.
- The author selects the condition and procedure independently; the software
  only visualizes that choice.
- It does not train, evaluate, serve, or create datasets for AI or machine
  learning models.

All output will be labeled as an illustrative educational simulation.

## Planned technology

- TypeScript and React
- WebGL for interactive 3D rendering
- SVG and Canvas for diagrams and overlays
- IndexedDB or local files for offline scenarios
- Vitest for unit and geometry tests
- Playwright for browser tests

The exact libraries will be chosen after a small offline technical prototype.

## Status

The project is currently in the planning stage. Implementation will begin
after the project proposal is approved.

## License

Licensed under the [MIT License](LICENSE).
