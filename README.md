# JoVI test paper (Rmarkdown)

A test paper in the Distill format generated using Rmarkdown.

## Setup

**To install all packages needed for this paper**, run the following commands:

```r
install.packages("devtools")   # can skip this line if you already have the devtools package
devtools::install_deps()
```

This will automatically install all packages listed in the [DESCRIPTION](DESCRIPTION) file.

**To add another package to the list of dependencies**, add it to the list under `Imports:` in the [DESCRIPTION](DESCRIPTION) file.

## Contents

This repository contains the following files:

- [index.Rmd](index.Rmd): The Rmarkdown source of the paper.
- [index.html](index.html): The compiled version of the paper.
- [DESCRIPTION](DESCRIPTION): The listing of R packages needed to compile this paper, used by `devtools::install_deps()` to download all dependencies.

