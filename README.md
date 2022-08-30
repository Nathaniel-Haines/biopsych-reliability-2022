# Installation

## R libraries

This repository was developed under `R 4.1.0`. `renv` is used as a package manager. To run the notebook yourself, open the `*.Rproj` project file in a new instance of `R/Rstudio`. Upon opening the project, `renv` should automatically download the required `R` libraries.

## cmdstan

Once `renv` is finished with installation, if you do not already have `cmdstan` installed, the simplest way to install it is by running `cmdstanr::install_cmdstan()` in `R`. If this method does not work, follow the OS-specific instructions [here](https://mc-stan.org/cmdstanr/articles/cmdstanr.html). 

# Usage

Once all dependencies are installed, navigate to the `*.Rmd` notebook file. There, you can run code chunks interactively. 

