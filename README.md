# madrat data preparation for data connected to fish

R package **mrfish**, version **0.2.6**

[![CRAN status](https://www.r-pkg.org/badges/version/mrfish)](https://cran.r-project.org/package=mrfish)   [![R build status](https://github.com/pik-piam/mrfish/workflows/check/badge.svg)](https://github.com/pik-piam/mrfish/actions) [![codecov](https://codecov.io/gh/pik-piam/mrfish/branch/master/graph/badge.svg)](https://codecov.io/gh/pik-piam/mrfish)

## Purpose and Functionality

Package contains routines to prepare data for validation exercises.


## Installation

For installation of the most recent package version an additional repository has to be added in R:

```r
options(repos = c(CRAN = "@CRAN@", pik = "https://rse.pik-potsdam.de/r/packages"))
```
The additional repository can be made available permanently by adding the line above to a file called `.Rprofile` stored in the home folder of your system (`Sys.glob("~")` in R returns the home directory).

After that the most recent version of the package can be installed using `install.packages`:

```r 
install.packages("mrfish")
```

Package updates can be installed using `update.packages` (make sure that the additional repository has been added before running that command):

```r 
update.packages()
```

## Questions / Problems

In case of questions / problems please contact Benjamin Leon Bodirsky <bodirsky@pik-potsdam.de>.

## Citation

To cite package **mrfish** in publications use:

Wehner J, Bodirsky B (2021). _mrfish: madrat data preparation for data connected to fish_. R package version 0.2.6, <URL: https://github.com/pik-piam/mrfish>.

A BibTeX entry for LaTeX users is

 ```latex
@Manual{,
  title = {mrfish: madrat data preparation for data connected to fish},
  author = {Jasmin Wehner and Benjamin Leon Bodirsky},
  year = {2021},
  note = {R package version 0.2.6},
  url = {https://github.com/pik-piam/mrfish},
}
```

