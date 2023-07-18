# Unlocking single cell spatial omics analyses with `scdney`
Materials for 'Unlocking single cell spatial omics analyses with `scdney`' workshop presented at [BioInfoSummer 2022](https://bis.amsi.org.au/program/).

## Prerequisites

Before coming to the workshop, you must have the latest version of R installed 
(> version 4.3), paired with your favourite IDE (e.g. 
[RStudio](https://posit.co/download/rstudio-desktop/)) and/or git for 
downloading the workshop materials. 


The following chunk of code will install all of the R packages you need for this workshop and also the data that we'll be analysing. 

```r
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install(c("STexampleData", "imcdatasets", "scHOT", "simpleSeg", "FuseSOM", "spicyR", "lisaClust", "ClassifyR", "ggplot2", "scater", "scuttle", "batchelor", "patchwork", "plotly"))

imc <- imcdatasets::Damond_2019_Pancreas(data_type = "spe")
spe <- STexampleData::seqFISH_mouseEmbryo()
                     
```


### Workshop structure

First, download the files in this Github repository by either cloning the 
repository or by downloading the files directly into a directory on your
computer.

In the workshop, we will work through two key examples with datasets. The 
first part will involve examining the data structure and exploratory data 
analysis. The second part will involve analytical techniques.

### Contact

Shila Ghazanfar shila.ghazanfar@sydney.edu.au

Nicholas Robertson nicholas.robertson@sydney.edu.au

Ellis Patrick ellis.patrick@sydney.edu.au
