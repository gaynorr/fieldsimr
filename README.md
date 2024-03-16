# FieldSimR

<!-- badges: start -->

[![R-CMD-check](https://github.com/crWerner/fieldsimr/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/crWerner/fieldsimr/actions/workflows/R-CMD-check.yaml)

<!-- badges: end -->

**FieldSimR** is an R package for simulating plot data in multi-environment field trials with one or more traits. Its core function generates plot errors that capture:

-   **spatial trend**,
-   **random error (noise)**, and
-   **extraneous variation**.

Spatial trend is simulated using bivariate interpolation or a separable first order autoregressive (AR1) process. Random error is simulated using an independent process. Extraneous variation is simulated using random or zig-zag ordering between neighbouring columns and/or rows. The three error components are combined at a user-defined ratio.

Phenotypes can be generated by combining the plot errors with genetic values (e.g., true, simulated, or predicted). **FieldSimR** provides wrapper functions to simulate correlated genetic values that capture genotype-by-environment (GxE) interaction with the R package [AlphaSimR](https://CRAN.R-project.org/package=AlphaSimR).

<br/>

### Installation

[FieldSimR](https://cran.r-project.org/package=FieldSimR) is available on CRAN.

To install use:

```         
install.packages("FieldSimR")
```

<br/>

### Vignettes

-   [Simulation of genetic values based on a compound symmetry model for GxE interaction](https://crwerner.github.io/fieldsimr/articles/compound_symmetry_GxE_demo.html)
-   [Simulation of genetic values based on an unstructured model for GxE interaction](https://crwerner.github.io/fieldsimr/articles/unstructured_GxE_demo.html)
-   [Simulation of plot errors and phenotypes in a plant breeding field trial](https://crwerner.github.io/fieldsimr/articles/spatial_variation_demo.html)
