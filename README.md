# rblogapps <img src="man/figures/logo.png" align="right" height="120" alt="" />


<!-- badges: start -->

[![R-CMD-check](https://github.com/r-data-science/rblogapps/actions/workflows/R-CMD-check.yaml/badge.svg?branch=main)](https://github.com/r-data-science/rblogapps/actions/workflows/R-CMD-check.yaml)
[![test-coverage](https://github.com/r-data-science/rblogapps/actions/workflows/test-coverage.yaml/badge.svg?branch=main)](https://github.com/r-data-science/rblogapps/actions/workflows/test-coverage.yaml)
[![codecov](https://codecov.io/gh/r-data-science/rnnblogapps/graph/badge.svg?token=4gg0ETS2w5)](https://codecov.io/gh/r-data-science/rblogapps)
[![shiny-apps](https://github.com/r-data-science/rblogapps/actions/workflows/shiny-apps.yaml/badge.svg?branch=main)](https://github.com/r-data-science/rblogapps/actions/workflows/shiny-apps.yaml)
<!-- badges: end -->

------------------------------------------------------------------------

## About

This package includes all apps assiocated with the r-data-science blog. Additionally, package includes the primary app datasets.

The three functions exported by this package are as follows:

`listBlogApps()`: Retrieves names of all apps included in this package

`runBlogApp(name)`: Run an app included in this package given it's name

`getBlogData(name)`: Returns an apps primary dataset given it's name

------------------------------------------------------------------------

## Examples

#### Install Package

```
remotes::install_github("r-data-science/rblogapps")
```

#### List Package Apps and Datasets

```
rblogapps::listBlogApps()
rblogapps::listBlogData()
```

#### Launch Package App

``` r
rblogapps::runBlogApp("employee_sales_kpis")
rblogapps::runBlogApp("house_brands_kpis")
rblogapps::runBlogApp("stockout_sales_impact")
rblogapps::runBlogApp("event_impact_kpis")
``` 

#### See App Dataset

``` r
rblogapps::getBlogData("employee_sales_kpis")
rblogapps::getBlogData("house_brands_kpis")
rblogapps::getBlogData("stockout_sales_impact")
rblogapps::getBlogData("event_impact_kpis")
```

## Deployment

To run this as a docker container, perform the following bash commands:

```{bash}

```

------------------------------------------------------------------------

Proprietary - Do Not Distribute
