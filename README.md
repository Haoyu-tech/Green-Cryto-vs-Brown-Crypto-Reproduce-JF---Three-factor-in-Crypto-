<div align="center">

# Green & Brown Crypto

Cryptocurrency factor replication and green/brown classification experiments.

![Format: Research notebooks](https://img.shields.io/badge/Format-Research%20notebooks-3776AB?style=flat-square) ![Market: Cryptocurrency](https://img.shields.io/badge/Market-Cryptocurrency-0F766E?style=flat-square) ![Stage: Research archive](https://img.shields.io/badge/Stage-Research%20archive-64748B?style=flat-square)

[Quick start](#quick-start) · [Project map](#project-map) · [Reproduction guide](docs/REPRODUCIBILITY.md)

</div>

---

## Overview

Notebook-based research combining replication materials for Liu, Tsyvinski and Wu (2022) with green/brown cryptocurrency extensions. Dated folders preserve successive research iterations.

## Project map

| Folder | Research area |
|---|---|
| [2.1/](2.1/) | Bitcoin clustering and feature-importance analysis |
| [3.10-capm/](3.10-capm/) | BTC/ETH filtering and CAPM-related experiments |
| [3.12/](3.12/) | Green-crypto and weekly-data studies |
| [4.13/](4.13/) | Revised factor replication and regression outputs |
| [Full-period studies](Green%20vs%20Brown%2BFulltime%20test/) | Extended replication and green/brown comparisons |

## Quick start

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install jupyterlab
python -m jupyter lab
```

JupyterLab provides the notebook interface. A complete Python/R dependency environment has not yet been specified. Inspect imports and data-loading cells, install the required packages, and replace local input paths before execution.

## Suggested reading route

1. Inspect the full-period replication notebooks under `Green vs Brown+Fulltime test/replicate JOF/full/`.
2. Review the green/brown extension under `Add Green vs Brown Variable/`.
3. Compare the CSV tables and PDF figures with the corresponding notebook outputs.

This is a reading route; execution order must be confirmed from each notebook's inputs and outputs.

## Reproduction boundary

The repository contains selected research artifacts, not a validated one-command pipeline. Raw-data provenance, weekly aggregation, classification rules, notebook order and package versions remain essential reproduction details.

## Reference

Liu, Y., Tsyvinski, A. and Wu, X. (2022). *Common Risk Factors in Cryptocurrency*. The Journal of Finance, 77, 1133–1177. DOI: 10.1111/jofi.13119.

## Documentation

- [Reproduction guide](docs/REPRODUCIBILITY.md): inputs, execution order and validation limits.
- [Code and artifact map](docs/REPOSITORY_MAP.md): source and configuration paths.

<sub>Research artifacts reflect the recorded experiment settings. Full results were not regenerated during documentation cleanup.</sub>
