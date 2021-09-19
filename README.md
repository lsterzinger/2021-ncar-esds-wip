# FSSPEC Reference Maker Talk
### NCAR Earth System Data Science WIP - 2021-09-20
***
## Running locally
The best option to run this notebook is locally, since generating the references can be easily parallelized with Dask

```
git clone https://github.com/lsterzinger/2021-ncar-earth-system-data-science-wip.git
cd 2021-ncar-earth-system-data-science-wip

conda create -f environment.yml
conda activate fsspec-reference-maker

jupyter lab
```
_Tip: use mamba instead of conda for a faster environment solve_

## Interactive Notebook Links
If desired, the notebook can be run online using Binder/Pangeo. These will probably be much slower than running on a local machine.

| Name | Link | Info |
|------|------|------|
| Binder | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lsterzinger/2021-ncar-earth-system-data-science-wip/HEAD?filepath=workshop.ipynb) | Faster to load, but with less computational resources |
| Pangeo | [![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/lsterzinger/2021-ncar-earth-system-data-science-wip/master) | Can be slower to load/build but with more computational resources available |