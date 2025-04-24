# Fallopian-Tube-Epithelium-Reprogramming-by-OC-EVs

This R Project was created for the paper "**Modeling Fallopian Tube Epithelium Cellular Signaling Reprogramming Driven by Extracellular Vesicles to Define the Ovarian Cancer Precancerous Landscape**" to be published in [....] in 2025.

This project takes data generated on the GeoMx DSP platform and performs analysis using code produced by Nanostring. This analysis is based on the following Bioconductor vignette: [Analyzing GeoMx-NGS RNA Expression Data with GeomxTools (bioconductor.org)](https://www.bioconductor.org/packages/release/workflows/vignettes/GeoMxWorkflows/inst/doc/GeomxTools_RNA-NGS_Analysis.html#5_Normalization)

## Overview of Main Folders and Files

A brief summary of the contents of this project:


Files:
* **QC_and_normalization.Rmd** - contains preliminary QC, Filtering, and Normalization of the GeoMx Dataset
* **main_figures.Rmd** - contains the code used to generate the main figures for this paper
* **supplementary_figures.Rmd** - contains the code used to generate the supplemental figures for this paper

* **functions.R** - contains helper functions for generating graphs


Folders:

* **/data_input** - contains all input files for the GeoMx platform, including:
  * _/dccs_ - contains .DCC files with probe counts (one .dcc per segment)
  * _/pkcs_ - contains .pkc file with probe information
  * _/annotations_ - contains an excel document with annotation information
  
* **/stat_analysis** - a file containing excel files with results of statistical analyses performed by a collaborator

* **/GO_analysis** - contains files needed for generating GO plots
  * /Source Files - contains source files used to generate GO files

