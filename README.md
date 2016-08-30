# Conda build recipes [Anaconda.org/basnijholt](https://anaconda.org/basnijholt/)

Install `kwant` with:
```
conda install -c basnijholt kwant
```

In order to install [Kwant](kwant-project.org/) you need some non-Python packages, therefore I created `conda-build` recipes to compile everything.

  - [MUMPS](mumps.enseeiht.fr) Sequential version, with SCOTCH and Metis (non-python)
  - [SCOTCH](https://www.labri.fr/perso/pelegrin/scotch/) (non-python)
  - [Metis](http://glaros.dtc.umn.edu/gkhome/metis/metis/overview) (non-python)
  - [Tinyarray](kwant-project.org/)
  - [Kwant](kwant-project.org/)
