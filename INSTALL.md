# Installing the R packages

The R packages are provided as source archives (`.tar.gz`) in `software/`. From within an R
session:

The Aim 1 methods are in the **hierNest** package:

```r
install.packages("path/to/hierNest_1.0.0.tar.gz", repos = NULL, type = "source")
```

The Aim 2 methods are in the **swjm** (stagewise joint models) package:

```r
install.packages("path/to/swjm_0.1.0.tar.gz", repos = NULL, type = "source")
```

Both packages are also maintained as open-source software with documentation and worked
examples:

- hierNest: <https://github.com/ZirenJiang/hierNest>, documentation at
  <https://zirenjiang.github.io/hierNest/> (vignette:
  <https://zirenjiang.github.io/hierNest/articles/hierNest_vignette.html>)
- swjm: <https://github.com/jaredhuling/swjm>, documentation at
  <https://jaredhuling.org/swjm/> (vignette: <https://jaredhuling.org/swjm/articles/swjm.html>)

Current versions can be installed directly from GitHub, e.g.
`remotes::install_github("jaredhuling/swjm")`. The archives in this repository are the exact
versions described in the Final Research Report.
