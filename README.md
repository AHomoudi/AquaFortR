# AquaFortR

<!-- badges: start -->
[![R-CMD-check](https://github.com/AHomoudi/AquaFortR/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/AHomoudi/AquaFortR/actions/workflows/R-CMD-check.yaml)
[![Quarto Publish](https://github.com/AHomoudi/AquaFortR/workflows/Quarto%20Publish/badge.svg)](https://github.com/AHomoudi/AquaFortR/actions?query=workflow:"Quarto+Publish")
[![GitHub tag](https://img.shields.io/github/tag/AHomoudi/AquaFortR?include_prereleases=&sort=semver&color=blue)](https://github.com/AHomoudi/AquaFortR/releases/)
[![License](https://img.shields.io/badge/License-CCBY-blue)](#license)
<!-- badges: end -->

This is the official repository of the Project AquaFortR: Streamlining Atmospheric Science, Oceanography, Climate, and Water Research with Fortran-accelerated R. 

The repository is structured as follows:

 - QuartoBook  
 - RPackage  
 - SwirlCourse

The documentation of the project is rendered [here](https://ahomoudi.github.io/AquaFortR/)

## Installation 

### Package
To install the AquaFortR package, please use: 

```r
remotes::install_github("AHomoudi/AquaFortR", subdir = "RPackage")
```

### Swirl
To install the AquaFortR Swirl Course, please download the compressed course from 
<a href="AquaFortR_Swirl.zip">here</a> and use the code below. 

```r
swirl::install_course_zip("path/to/AquaFortR_Swirl.zip")
```

**_NOTE:_**  The R packages dotCall64, ggplot2, and microbenchmark are required for the course.

### Book 

Materials for the chapter 2 are available <a href="AquaFortR_Codes.zip">here</a>. Please, 
revise the path to the shared libraries files in the R-Fortran functions.

## Acknowledgment

This work has been funded by the German Research Foundation (DFG) through the project NFDI4Earth (DFG project no. 460036893, https://www.nfdi4earth.de/) within the German National Research Data Infrastructure (NFDI, https://www.nfdi.de/). 

## License

This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 
International (CC BY-NC 4.0) License (<https://creativecommons.org/licenses/by-nc/4.0/>).


<!---  setwd("C:\\Projects\\AquaFortR") --->
