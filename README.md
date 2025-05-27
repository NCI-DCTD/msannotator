# msannotator

Install using the command: devtools::install_github("nci-dctd/msannotator")

Depends on the MSnbase package from Bioconductor

if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("MSnbase")

Run the following to test:
library(msannotator)
graphMinalemine()

Will output the following file in the current working directory:
package_test.graphml
