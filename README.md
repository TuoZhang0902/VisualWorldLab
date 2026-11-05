# VisualWorldLab

Exploring self-supervised visual representation learning and motion understanding through video.

## First study: Occlusion and Motion Continuity

**Research question:** Can a JEPA-style model learn temporally consistent representations of moving objects under partial occlusion?

This repository starts as an NNDL final project and is designed to grow into a longer-term research workspace.

## Planned workflow

1. Generate synthetic moving-object videos with controlled occlusions.
2. Visualize and validate the dataset.
3. Implement a minimal JEPA-style encoder, target encoder, and predictor.
4. Train with latent-space prediction loss.
5. Evaluate motion continuity with frozen-representation probes and occlusion-duration tests.

## Structure

- `configs/`: experiment settings
- `src/`: dataset, model, training, and evaluation code
- `experiments/occlusion/`: research notes and results
- `notebooks/`: exploratory visualization
- `docs/`: reading notes

> The Python modules are intentionally starter placeholders; no model or results are claimed yet.
