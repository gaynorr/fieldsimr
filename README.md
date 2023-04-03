# FieldSimR #

**FieldSimR** is an R package to enable simulation of plot data in field trials for multiple traits across multiple environments. Its core function generates plot errors comprising 

- a **spatially correlated error** term,
- a **random error** term, and 
- an **extraneous error** term. 

Spatially correlated errors are simulated using either bivariate interpolation or a two-dimensional autoregressive process of order one (AR1:AR1). The three error terms are combined at a user-defined ratio. 

Plot phenotypes can be generated by combinating the simulated errors with genetic values (e.g. true, simulated or predicted). **FieldSimR** provides wrapper functions to simulate genetic values for multiple traits across multiple environments using the **R** package [AlphaSimR](https://CRAN.R-project.org/package=AlphaSimR).

<br/>

### Vignettes ###

- [Simulation of genetic values using a compound symmetry GxE interaction model](https://crwerner.github.io/fieldsimr/articles/compound_symmetry_GxE_demo.html)
- [Simulation of genetic values using an unstructured GxE interaction model](https://crwerner.github.io/fieldsimr/articles/unstructured_GxE_demo.html)
- [Simulation of plot errors and phenotypes for a multi-environment plant breeding trial](https://crwerner.github.io/fieldsimr/articles/spatial_error_demo.html)


