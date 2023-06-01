[![Build Status](https://travis-ci.com/satijalab/seurat.svg?branch=master)](https://app.travis-ci.com:443/github/satijalab/seurat)
[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/satijalab/seurat?branch=master&svg=true)](https://ci.appveyor.com/project/satijalab/seurat)
[![CRAN Version](https://www.r-pkg.org/badges/version/Seurat)](https://cran.r-project.org/package=Seurat)
[![CRAN Downloads](https://cranlogs.r-pkg.org/badges/Seurat)](https://cran.r-project.org/package=Seurat)

# Gin-modified Seurat v4.3.0
## installation:
'devtools::install_github(repo = "Jwenyi/gin_seurat")'
## Modification
The original 'Seurat' did not support larget scRNA data integration via CCA as their dependent package 'Matrix' could not process a long vector over 2^31. I used 'spam' to replace 'Matrix' to fix this.
