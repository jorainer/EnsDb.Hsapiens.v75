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
directly from github.

```{r}
library(devtools)
install_github("jotsetung/EnsDb.Hsapiens.v75")
```

Alternatively clone the repository and use `R CMD build EnsDb.Hsapiens.v75` to
build the package and `R CMD INSTALL EnsDb.Hsapiens.v75.*` to install it.


