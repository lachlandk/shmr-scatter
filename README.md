# SHMR Scatter
These are notebooks from an astrophysics summer research project in 2023 which was investigating the origin of scatter in the galaxy stellar mass-halo mass relationship (SHMR), specifically in the [IllustrisTNG](https://www.tng-project.org/) hydrodynamical simulation.
The project was undertaken at the [University of St Andrews](https://astronomy.wp.st-andrews.ac.uk/research/galaxies-evolution/) under the supervision of [Dr Rita Tojeiro](https://www.st-andrews.ac.uk/physics-astronomy/people/rmftr).

The code was created an ran on the [JuptyterLab server](https://www.tng-project.org/data/) to avoid having to download the simulation data.
Therefore, it will not run on a local machine without some small modifications which can be found in the [Getting started guide](https://www.tng-project.org/data/docs/scripts/).

## Notebooks
- `data_collection.ipynb` - Contains all code necessary to pull and process relevant data from the simulation.
- `shmr.ipynb` - Plots of the stellar/halo mass relation, as well as the gas/halo and baryon/halo mass relations.
- `halo_properties.ipynb` - Plots of the evolution of some halo properties over time as a function of halo mass - the main focus of this project.
- `mass-history.ipynb` -Investigating how the different mass components evolve over time as a function of halo formation time.

## Dependencies
- [h5py](https://pypi.org/project/h5py/)
- [loess](https://pypi.org/project/loess/)

## To-Do
- Change basic `tqdm` loops to widgets
- Helper files for downloading the simulation data
