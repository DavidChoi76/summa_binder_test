# Remote Approach-10: Using Binder for the reproducibility of SUMMA modeling

Try it on Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DavidChoi76/Remote_Approach_10_Using_Binder_for_the_reproducibility_of_SUMMA_modeling/master/?urlpath=lab)

A repository to build an environment in Binder that supports pySUMMA and SUMMA simulations.
Check out [pySUMMA](https://github.com/UW-Hydro/pysumma/tree/master) and [SUMMA](https://github.com/NCAR/summa).

### Configuration files
- `apt.txt` - Specifies the Debian packages to be installed using apt-get
- `environment.yml` - Lists the conda packages to be installed into the base image
- `postbuild` -  Script to be run after the environment has been build 
