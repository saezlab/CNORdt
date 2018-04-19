CNORdt
=========

CNORdt is an extension of CellNOptR that allows to train a Boolean model agains time-courses of data.
Please visit the package on the [Bioconductor page](http://www.bioconductor.org/packages/release/bioc/html/CNORdt.html) for
further details or check [http://www.cellnopt.org/](http://www.cellnopt.org/) for a detailed description of CellNOptR.

Related tool:  
[CNORode2017](https://github.com/saezlab/CNORode2017): train, simulate and predict with a continuous time logic based model 

## Installation:

Before starting, make sure you have installed the latest version of R. For more information and download
of R, please refer to `R project page <http://www.r-project.org/>`_ . For more information about how to 
install R packages, please refer to `Installing package <http://cran.r-project.org/doc/manuals/R-admin.html#Installing-packages>`_
These packages rely on several Bioconductor package (e.g., RBGL, graph, methods, etc.). As an example, you can
install RGBL package by typing:
```
  source("http://bioconductor.org/biocLite.R")
  biocLite("RBGL")
```

### Installation from GitHub
using the `devtools` package you can install the latest version from the GitHub repository:
```
if(!require("devtools")) install.packages('devtools’)   # installs devtools package if not already installed
devtools::install_github('saezlab/CNORdt’)
```

### Standard installation from Bioconductor
To install CNORdt, type:
```
  source("http://bioconductor.org/biocLite.R")
  biocLite("CNORdt")
```
Then, you can also install other CellNOptR related packages::
```
   biocLite("CellNOptR")
   biocLite("CNORfeeder")
   biocLite("CNORfuzzy")
   biocLite("CNORode")
```

### Install from a local copy of the package:
install CNORdt from a tar ball as follows:
```
install.packages("path_to_CNORdt/CNORdt_1.0.0.tar.gz", + repos=NULL, type="source")
```
or, using the R GUI by clicking on "Packages & Data" then "Package installer", then choosing "local source"
from the dropdown menu, clicking "install", choosing `CNORdt.1.0.0.tar.gz`
and finally clicking "open".
