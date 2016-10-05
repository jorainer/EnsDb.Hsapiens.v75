# EnsDb.Hsapiens.v75

Package providing the `EnsDb` database for human gene and protein annotations
defined in Ensembl version 75. This package depends on Bioconductor's
`ensembldb` package (official version at
http://www.bioconductor.org/packages/ensembldb, development version at
https://github.com/jotsetung/ensembldb). See
https://github.com/jotsetung/ensembldb/blob/master/vignettes/ensembldb.Rmd for a
detailed description how to use the package.

## Installation

Ideally, this package should be installed from Bioconductor:

```{r}
library(BiocInstaller)
biocLite("EnsDb.Hsapiens.v75")
```

In addition it is possible to install the development version of the package
directly from github by first cloning the repository (`git-lfs`, i.e. git large
file storage should be installed on the system in order to fetch the SQLite
database file). The package can then be build with `R CMD build
EnsDb.Hsapiens.v75` and finally installed with `R CMD INSTALL
EnsDb.Hsapiens.v75_*`.
