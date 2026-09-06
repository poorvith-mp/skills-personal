---
name: 3d-printing
group: Hobby
description: >-
  Tune filament profiles: temperature, flow, retraction and cooling against material and printer.
  Use when troubleshooting FDM/resin slicing, print bed adhesion, or layer lines.
---

# 3D Printing

Diagnose 3D print quality problems that trace back to material and thermal settings.

## Process
1. **Identify the symptom precisely** — stringing, layer separation, warping, under-extrusion, elephant foot and poor overhangs each point at different settings.
2. **Change one variable at a time.** Print a calibration tower rather than adjusting four settings and printing one part.
3. **Start with temperature.** Run a temperature tower for the specific filament and spool; published ranges are a starting point, not a value.
4. **Then flow and extrusion multiplier**, measured against a single-wall cube's actual wall thickness.
5. **Then retraction** — distance and speed, tuned on a stringing test, and different for direct drive versus bowden.
6. **Then cooling**, which trades overhang quality against layer adhesion. PLA and ABS want opposite answers.
7. **Record the working profile per filament and printer**, including ambient conditions. Humidity in the filament explains a surprising share of unexplained failures.

## Deliverables
- Symptom-to-cause diagnosis
- Calibration sequence with one variable per test
- Saved profile per material and printer with conditions noted

## Verification & Quality Checklist

- [ ] Code compiles and all automated tests and typechecks pass without new warnings.
- [ ] Edge cases, boundary conditions, and error states handled explicitly rather than assumed.
- [ ] No hardcoded secrets, credentials, or insecure defaults introduced.
- [ ] Changes are covered by a test that fails without them.

## Anti-Patterns & Constraints

- NEVER weaken or skip a failing test to make a change land.
- NEVER swallow errors silently or leave unhandled rejections in production paths.
- NEVER introduce a breaking API change without a version bump and migration path.
