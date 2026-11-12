# Highlighter-Snap-Release-Study
A reproducible Monte Carlo study of middle-highlighter motion under alternative snap-release impulse assumptions.

## Research question

When three highlighters are connected side by side and the
bottom ends of the two outer highlighters are pulled downward
until the connections release, what determines the initial
direction of the middle highlighter?

## Overview

This project uses Monte Carlo simulation to compare three
hypothetical connector-release mechanisms:

- Downward drag
- Upward recoil
- Nearly balanced release

The model represents connector disengagement through impulses
applied to the middle highlighter. It examines initial motion
separately from later displacement under gravity.

## Important scientific limitation

All simulated datasets are synthetic.

The connector impulses are illustrative assumptions, not
measurements of the actual highlighters. The reported
probabilities are conditional on those assumptions.

The study does not establish which release mechanism occurs
in a real highlighter assembly.

## Included materials

- Executed Python notebook
- Trial-level synthetic data
- Conditional direction probabilities
- Monte Carlo sampling intervals
- Verification checks
- Sensitivity analysis
- Figures
- Model assumptions
- Research report
- Blank experimental measurement template

## Running the study

1. Open the notebook in a compatible Jupyter environment.
2. For browser execution, select Python (Pyodide).
3. Restart the kernel and run all cells from top to bottom.
4. Wait for package loading, simulation, and plotting to finish.

The notebook loads NumPy, pandas, and Matplotlib in Pyodide.
In a local Python environment, those packages and IPython must
already be installed.

## Reproducibility

The notebook records its random seed, model configuration,
software versions, verification results, and output-file hashes.

The baseline simulation contains 30,000 synthetic trials:
10,000 for each assumed release mechanism.

Verification checks test the implementation. They do not
establish physical validity.

## Next step

Record repeated physical releases, estimate pre-release and
post-release velocities, and use those measurements to
calibrate and evaluate the model.
