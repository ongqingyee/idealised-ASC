# idealised-ASC
Repository with scripts and notebooks for reproducing the figures and analyses for the manuscript "Intrinsically Episodic Intrusions of Circumpolar Deep Water via Canyons – An Idealised Study of the Antarctic Slope Current" by Ong et al (2024), [https://doi.org/10.1175/JPO-D-23-0067.1](https://doi.org/10.1175/JPO-D-23-0067.1). 

Directory `analysis_notebooks` has the jupyter notebooks that analyse MOM6 model output data, which reproduces all the nefCDF files included in `layeredASFpaper_ncfile`. 

Directory `plotting_notebooks` has the jupyter notebooks that use netCDF files in `layeredASFpaper_ncfile` to plot figures for the paper. 

Directory `input-files` contains the directory `layer4_tau1p0e-01_example_STEEPsigmah1p0e+02` with example input files for the reference simulation, and the jupyter notebook used to generate the input files. 

Directory `config-files` contains the files for configuring the MOM6 model (github.com/mom-ocean/MOM6)
