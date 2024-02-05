# eb-pism-deps

This repo contains the required easyconfigs to build the pism-deps module for the foss/2023a toolchain with EasyBuild

## Usage

```
module load Workspace
module load Easybuild
eb-install-all --robot=/path/to/this/directory/foss/2023a/ --slurm-args='--time=05:00:00' foss/2023a/pism2-deps-foss-2023a.eb
```
