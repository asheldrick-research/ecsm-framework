# ECSM Framework

**Emergent Condensate Superfluid Medium (ECSM)** is a theoretical framework in which
gravitational, optical, and cosmological phenomena arise from the collective dynamics
of a coherent cosmic medium, rather than from fundamental spacetime curvature or
dark-sector components.

In ECSM:
- Spacetime geometry is an **effective description** of condensate deformation.
- Gravity and inertia emerge from **universal coupling** to the medium.
- Electromagnetic propagation reflects **phase dynamics**, not quantized particles.
- Late-time cosmological observables can be reproduced **without dark matter or dark energy**.

The framework is developed through a sequence of analytical and phenomenological papers
that address ultraviolet completion, gravity, spacetime optics, and late-time structure
formation.

---

## Publications

The following papers develop and test the ECSM framework:

- **Coherence-Gated Ultraviolet Completion and Light-Element Constraints in Emergent Condensate–Superfluid Cosmology**  
  *(UV completion, early-universe consistency)*

- **ECSM Dynamics Without Curvature: Gravity, Inertia, and Emergent Geometry in a Superfluid Cosmology**  
  *(gravity and equivalence from medium dynamics)*

- **Emergent Spacetime Optics from a Superfluid ECSM: Non-Metric Light Propagation, Weak Lensing Suppression, and CMB Phase-Transition Signatures**  
  *(light propagation and observational signatures)*

- **Separating Geometry, Growth, and Amplitude in Late-Time Cosmology: A Joint Analysis of BAO, RSD, Weak Lensing, and CMB Consistency**  
  *(late-time cosmological constraints without expansion)*

All papers are authored by **Adam Sheldrick** and are publicly available.

---

## Author

**Adam Sheldrick**  
ORCID: https://orcid.org/0009-0004-3145-757X

---

## Scope and Status

ECSM is an active research program.
It does **not** claim to replace ΛCDM phenomenology in all regimes at present, but provides
a unified physical ontology that reproduces key gravitational, optical, and cosmological
observations without invoking additional dark components.

Feedback, critique, and independent analysis are welcome.

## RESULTS

ECSM Late-Time Consistency Test

This repository contains a reproducible implementation of a late-time cosmological consistency test within the Emergent Condensate Superfluid Medium (ECSM) framework.

Overview

The notebook performs a sequential bootstrap test:

1. A canonical ECSM geometry shape is fixed using supernova-derived parameters
2. The absolute propagation scale is anchored using baryon acoustic oscillation (BAO) constraints
3. The resulting geometry is used to predict the late-time growth observable f\sigma_8(z)
4. The prediction is compared against redshift-space distortion (RSD) measurements

Result

Using the canonical configuration:

- χ²/dof ≈ 0.94
- p-value ≈ 0.51
- No residual exceeds 2σ

This demonstrates that the ECSM late-time pipeline can produce an observationally viable growth history without additional tuning beyond the canonical geometry and BAO anchor.

Files

- "ECSM_Late_Time_Consistency_Test.ipynb" — main reproducible notebook
- "data/" — input datasets (RSD, BAO if included)
- "outputs/" — generated results (fits, plots, summary)

Reproducibility

To reproduce the results:

1. Open the notebook in Google Colab or Jupyter
2. Set the correct data paths
3. Run all cells from top to bottom

Citation

If referencing this work, please cite the associated ECSM framework paper and link to this repository.

---

This notebook is intended as a minimal, transparent demonstration of late-time ECSM consistency, rather than a full parameter exploration.
