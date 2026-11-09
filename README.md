# STARS-Dataset-Repository

This repository contains the R code and data used for a PL4246 Network Analysis project at the National University of Singapore (NUS).

# Project Overview

This project examines how the network structure of the Statistics Anxiety Rating Scale (STARS) corresponds to its established six-factor structure.

Using survey responses from 182 university students, a partial-correlation network was constructed from the 51 STARS items. Network measures, nominal assortativity, and Walktrap community detection were used to examine the overall network structure and the extent to which detected communities aligned with the six established factors.

# Repository Contents

Final Report.Rmd — R Markdown file containing the code for network construction and analysis.

stars-data_182.csv — Dataset containing the STARS responses from 182 students.

$ Requirements

The analysis was conducted in R using the following packages:

igraph

tidyverse

bootnet

The rmarkdown and knitr packages are also needed to render the R Markdown file.

# Reproducing the Analysis

Download or clone this repository.

Open STARS Analysis.Rmd in RStudio.

Ensure that the required packages are installed.

Keep stars-data_182.csv in the same directory as the R Markdown file.

Run the code chunks in order or knit the R Markdown file to reproduce the analyses.

The analyses include network construction, macro-level network measures, nominal assortativity, and Walktrap community detection.

# Main Findings

The network consisted of 51 nodes and 128 edges. Nominal assortativity was 0.246, while Walktrap identified nine communities with a modularity score of 0.382. The findings suggest partial correspondence between the network structure and the established six-factor structure of STARS.
