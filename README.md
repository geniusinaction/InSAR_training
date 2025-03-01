# InSAR_training
Some resources for InSAR training courses that I run.

## [Things_to_do_before_the_InSAR_course.pdf](Things_to_do_before_the_InSAR_course.pdf)
- If you need to set up WSL2 for Linux emulation on a Windows 11 machine, instructions are here
- Also covers how to set up NASA EarthData and Copernicus accounts

## [InSAR_environment_setup.pdf](InSAR_environment_setup.pdf)
- How to set up the conda environments used in the training
- Includes how to make use of the [InSAR.yml](InSAR.yml) conda/mamba requirements file
   
## [simple_hyp3_setup_for_MintPy.ipynb](simple_hyp3_setup_for_MintPy.ipynb)
- A Jupyter notebook on how to prepare, ingest and analyze processed interferograms from the [HyP3 system](https://hyp3-docs.asf.alaska.edu/) operated by the [ASF](https://asf.alaska.edu/)
- Uses the [MintPy software](https://github.com/insarlab/MintPy) (installed with the conda environment) to compute InSAR time series and velocities

## [load_and_export_velocity_data_hyp3.ipynb](load_and_export_velocity_data_hyp3.ipynb)
- A Jupyter notebook that can export InSAR velocities from MintPy as GeoTIFFs so that they can be loaded into GIS software

## [load_and_extract_timeseries_hyp3.ipynb](load_and_extract_timeseries_hyp3.ipynb)
- A Jupyter notebook that shows how to extract cumulative displacements, time-slices and double-differenced pixel time series from your MintPy-format time series

## [slides](slides)
- Some pdfs of presentation slides describing some of the background theory and details of SAR, InSAR, and InSAR time series
