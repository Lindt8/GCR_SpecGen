## [View online at the Binder build of this repository.](https://mybinder.org/v2/gh/Lindt8/GCR_SpecGen/master)

# GCR SpecGen
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2573359.svg)](https://doi.org/10.5281/zenodo.2573359)
### Galactic Cosmic Ray Spectra Generator

Automatically generate GCR spectra for Z=1-28 for any level of solar modulation (or date / range of dates).

This is a Jupyter notebook for conveniently generating GCR spectra using the [GCR model developed by Dr. Daniel Matthiä](https://www.sciencedirect.com/science/article/pii/S0273117712005947?via%3Dihub).  The notebook allows for selection of which source ions are of interest and the desired level of solar modulation, either set manually or calculated automatically from a date or range of dates.  It yields a brief summary of the GCR spectra, text files containing each ion's full spectrum (formatted in a "raw" tabular form and as source cards ready for use in MCNP and PHITS simulations), and a plot showing the selected spectra under the specified level of solar modulation.

Either download the contents of this repository and launch the Jupyter notebook file locally or visit this notebook online at https://mybinder.org/v2/gh/Lindt8/GCR_SpecGen/master.  Note that this site can be quite slow to load (sometimes taking 2+ minutes) or occasionally not working at all.  Once it has loaded, click the ``GCR SpecGen.ipynb`` file/link, which will open the notebook in a new tab, follow the instructions at the top of the page, and enjoy generating GCR spectra with GCR SpecGen!

###### GCR SpecGen was written and developed by Hunter Ratliff at The University of Tennessee, Knoxville, Department of Nuclear Engineering 
###### Copyright &#169; 2018 Hunter Ratliff (Lindt8) 
