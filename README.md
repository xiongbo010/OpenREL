# OpenREL

Research workspace built around RelBench.

## Layout

- `third_party/relbench/`: vendored RelBench source used for datasets, tasks, and evaluation.
- `environment.yml`: reproducible Conda environment for working with RelBench in this repo.

## Setup

```bash
source ~/miniforge3/etc/profile.d/conda.sh
conda activate openrel
```

If you need to recreate the environment:

```bash
conda env remove -n openrel
mamba env create -f environment.yml
conda activate openrel
```

## Notes

The `upstream` git remote still points to the official RelBench repository:
<https://github.com/snap-stanford/relbench>
