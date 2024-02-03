# FieldSimR #

**FieldSimR** is an R package for simulating realistic plot data in multi-environment field trials with one or more traits. Its core function generates plot errors that capture:

- **spatial trend**,
- **random error** (noise), and 
- **extraneous variation**. 

Spatial trend is simulated using bivariate interpolation or a separable first order autoregressive (AR1) process. The three error terms are combined at a user-defined ratio. 

Plot phenotypes can be generated by combining the simulated plot errors with genetic values (e.g. true, simulated or predicted). **FieldSimR** provides wrapper functions to simulate genetic values for multiple traits in multiple environments using the R package [AlphaSimR](https://CRAN.R-project.org/package=AlphaSimR).

<br/>

### Installation ###

[FieldSimR](https://cran.r-project.org/package=FieldSimR) is available on CRAN.

To install use:

    install.packages('FieldSimR')

<br/>

### Vignettes ###

- [Simulation of genetic values using a compound symmetry model for GxE interaction](https://crwerner.github.io/fieldsimr/articles/compound_symmetry_GxE_demo.html)
- [Simulation of genetic values using an unstructured model for GxE interaction](https://crwerner.github.io/fieldsimr/articles/unstructured_GxE_demo.html)
- [Simulation of plot errors and phenotypes for a multi-environment field trial](https://crwerner.github.io/fieldsimr/articles/spatial_error_demo.html)

