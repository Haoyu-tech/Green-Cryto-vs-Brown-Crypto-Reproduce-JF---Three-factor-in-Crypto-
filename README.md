# Green vs Brown Cryptocurrency Research

[Reproduction guide](docs/REPRODUCIBILITY.md) · [Code and artifact map](docs/REPOSITORY_MAP.md)

Notebook-based cryptocurrency factor research, combining replication materials for Liu, Tsyvinski and Wu (2022) with green/brown classification experiments.

## Start here

The dated folders preserve research iterations. They are not a single automated pipeline.

| Folder | Contents |
|---|---|
| [2.1/](2.1/) | Bitcoin clustering, feature importance and exploratory materials |
| [3.10-capm/](3.10-capm/) | BTC/ETH filtering and CAPM-related notebooks |
| [3.12/](3.12/) | Green-crypto and weekly-data experiments |
| [4.13/](4.13/) | Revised replication notebook and factor-regression outputs |
| [Green vs Brown+Fulltime test/](Green%20vs%20Brown%2BFulltime%20test/) | Full-period replication and green/brown extensions |

Suggested reading begins with the full-period replication notebooks in `Green vs Brown+Fulltime test/replicate JOF/full/`, followed by `Add Green vs Brown Variable/`. This is a reading route; execution order must be confirmed from notebook inputs and outputs.

## Run the notebooks

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install jupyterlab
python -m jupyter lab
```

JupyterLab is only the notebook interface. A complete, versioned Python/R dependency environment has not been provided. Inspect each notebook's imports and data-loading cells before execution, install its required packages, and replace machine-specific input paths.

Committed CSV files, images and PDFs are research artifacts; they do not establish that all raw inputs are present. Data provenance, green/brown classification rules, notebook order and reference package versions still need to be recorded for end-to-end reproduction.

See [the reproduction guide](docs/REPRODUCIBILITY.md).

## Reference

Liu, Y., Tsyvinski, A. and Wu, X. (2022). Common Risk Factors in Cryptocurrency. *The Journal of Finance*, 77, 1133–1177. DOI: 10.1111/jofi.13119.

The green/brown extension should be evaluated separately from reproduction of the published factor model.
