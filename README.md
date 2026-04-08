# Surgical-Baffle-Geometries

This repository contains patient-specific geometric models and simulation-ready meshes for intraventricular baffle design in double-outlet right ventricle (DORV). The dataset accompanies a computational framework for constructing physiologically aligned VSD-to-aorta pathways and evaluating their hemodynamic performance.

## Dataset Contents

This repository includes data for **4 retrospective DORV patients**.

### For each patient, the repository provides:
- **Individual surface meshes** (`.vtp`)
  - `aorta.vtp`
  - `RV.vtp`
  - `LV.vtp`
  - `pa.vtp`
  - `RA.vtp`
  - `LA.vtp`

- **Final combined surface mesh** (`.vtp`)
  - watertight and topologically consistent

- **Volume mesh** (`.vtu`)
  - tetrahedral mesh compatible with SimVascular

- **Final baffle surface** (`.vtp`)
  - isolated patient-specific intraventricular baffle geometry
