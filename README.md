# SUMMA_Binder
Try it on Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DavidChoi76/SUMMA_Binder_Test/master)

A repository to build an environment in Binder that supports pySUMMA and SUMMA simulations.
Check out [pySUMMA](https://github.com/UW-Hydro/pysumma/tree/master) and [SUMMA](https://github.com/NCAR/summa).

### Configuration files
- `apt.txt` - Specifies the Debian packages to be installed using apt-get
- `environment.yml` - Lists the conda packages to be installed into the base image
- `postbuild` -  Script to be run after the environment has been build 
