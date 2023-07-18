# Unlocking single cell spatial omics analyses with `scdney`
Materials for 'Unlocking single cell spatial omics analyses with `scdney`' workshop presented at [BioInfoSummer 2022](https://bis.amsi.org.au/program/).

## Prerequisites

Before coming to the workshop, you must have the latest version of R installed 
(or at least version 4.2), paired with your favourite IDE (e.g. 
[RStudio](https://posit.co/download/rstudio-desktop/)) and/or git for 
downloading the workshop materials. You will also need the latest version of
Bioconductor installed, you can do this by running:

```r
# if BiocManager not installed
install.packages("BiocManager")
BiocManager::install(version = "3.17")
```

### Installing `scdney`

`scdney` is a collection of packages developed by researchers at the Sydney 
Precision Data Science Centre. As a result of the many packages contained in 
this collection, `scdney` contains several dependencies and can take a while to 
install, attendees should have installed it prior to the beginning of the 
workshop.

`scdney` can be installed as follows.

```r
# if BiocManager or remotes packages are not installed
install.packages(c("BiocManager","remotes"))

# install scdney
BiocManager::install("SydneyBioX/scdney")
# test the installation by loading scdney
library(scdney)
```

### Workshop structure

First, download the files in this Github repository by either cloning the 
repository or by downloading the files directly into a directory on your
computer.

In the workshop, we will worth through two key examples with datasets. The 
first part will involve examining the data structure and exploratory data 
analysis. The second part will involve analytical techniques.

### Contact

Shila Ghazanfar shila.ghazanfar@sydney.edu.au

Nicholas Robertson nicholas.robertson@sydney.edu.au

Ellis Patrick ellis.patrick@sydney.edu.au
