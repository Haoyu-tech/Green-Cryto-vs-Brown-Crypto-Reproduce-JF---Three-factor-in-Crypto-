# Reproduction guide

## Notebook archive

See the [README](../README.md) for the dated-folder map. This repository preserves multiple iterations and does not contain a single orchestrator or a validated dependency lock.

## Reading and execution

Open the notebooks with JupyterLab. Start by inspecting inputs, imports and outputs in the full-period replication folder; then inspect the green/brown extensions. Directory chronology alone does not establish execution dependencies.

Before using “Restart Kernel and Run All”, replace local paths and confirm required raw data are available. Some notebooks or preprocessing steps may rely on R; a Python notebook interface does not supply the R environment.

## Reproduction record

Record the source and retrieval date of price, market-cap and classification data, weekly aggregation conventions, sample filters, factor construction and green/brown labels. Keep replication of the published factor model separate from the extension. CSV/PDF artifacts can be inspected without rerunning notebooks, but their presence does not prove full reproduction.

Notebook package requirements and input schemas still need a cell-by-cell audit.

## Run record

For every result you intend to compare or share, retain the repository commit, exact command/configuration, input-data identity, environment versions and output location. Save a dependency snapshot after a successful reference run; newly added requirements lists are intentionally unpinned until that validation exists.

## Validation status

Cleanup review: 14 October 2026. File paths and documented entry points were checked against the checkout. Full empirical results were not regenerated. Project-specific external prerequisites and known blockers are listed above.
