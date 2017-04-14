# PheWAS
The PheWAS R package is designed to provide an accessible interface to the phenome wide association study. 
For a description of the methods available and some simple examples, please see the
[package vignette](https://github.com/PheWAS/PheWAS/blob/master/inst/doc/PheWAS-package.pdf?raw=true) or the R documentation. 
For installation help, see below.
##Installing the PheWAS Package
The PheWAS package can be installed using the devtools package. The following code when executed in R will get you started:
```
install.packages("devtools")
#It may be necessary to install required as not all package dependencies are installed by devtools:
install.packages(c("dplyr","tidyr","ggplot2","MASS","meta","ggrepel","DT"))
devtools::install_github("PheWAS/PheWAS")
library(PheWAS)
```
Note that some versions of devtools do not install all dependencies, so one may need to install those using install.packages() first if there is an error.

You can additionally view the package help or vignette in R:
- `?PheWAS`
- `vignette("PheWAS-package")`
