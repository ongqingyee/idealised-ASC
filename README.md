# idealised-ASC
Repository with scripts and notebooks for reproducing the figures and analyses for the paper:

Ong, E. Q. Y., Doddridge, E. W., Constantinou, N. C., Hogg, A. McC., and England, M. H. (2024). Intrinsically episodic Antarctic shelf intrusions of circumpolar deep water via canyons. _J. Phys. Oceanogr._ (in press; doi:[10.1175/JPO-D-23-0067.1](https://doi.org/10.1175/JPO-D-23-0067.1))

```bibtex
@article{Ong-etal-2024,
  doi = {10.1175/JPO-D-23-0067.1},
  year = {2024},
  author = {Ong, E. Q. Y. and Doddridge, E. W. and Constantinou, N. C. and Hogg, A. McC. and England, M. H.},
  title = {Intrinsically episodic Antarctic shelf intrusions of circumpolar deep water via canyons},
  journal = {J. Phys. Oceanogr.}
  note = {in press; doi:10.1175/JPO-D-23-0067.1}
}
```

### Contents

* `analysis_notebooks`: jupyter notebooks that analyse MOM6 model output data, which reproduces all the nefCDF files included in `layeredASFpaper_ncfile`.

* `plotting_notebooks`: jupyter notebooks that use netCDF files in `layeredASFpaper_ncfile` to plot figures for the paper. 

* `input-files`: contains the directory `layer4_tau1p0e-01_example_STEEPsigmah1p0e+02` with example input files for the reference simulation, and the jupyter notebook used to generate the input files. 

* `config-files`: contains the files for configuring the MOM6 model ([github.com/mom-ocean/MOM6](https://github.com/mom-ocean/MOM6))
