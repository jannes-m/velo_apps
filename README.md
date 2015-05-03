<!-- README.md is generated from README.Rmd. Please edit that file -->
velo\_apps
==========

`velo_apps` provides functions of the [velo](https://github.com/jannes-m/velo)-package as RShiny Apps. This way people unfamiliar with R can now also use `velo`-functions. `spoke_app` calculates spoke lengths.

You can install the latest development version from github with

``` r
if (packageVersion("devtools") < 1.6) {
    install.packages("devtools")    
    }
if (!"lazyeval" %in% installed.packages()[, "Package"]) {
devtools::install_github("hadley/lazyeval")  
}
devtools::install_github("jannes-m/velo")
```

Still to do
===========

1.  `spoke_app`: (visual) description of the measures to take (e.g., ERD, hub to left flange, etc.)
2.  write `fixie_app` for Olli
3.  write `trail_app` together with Dirk

4.  Item 1
5.  Item 2
6.  Item 3
    -   Item 3a
    -   Item 3b
