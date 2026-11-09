# STARS-Dataset-Repository

This repository contains the R code and data used for a PL4246 Network Analysis project at the National University of Singapore (NUS).

# Project Overview

This project examines how the network structure of the Statistics Anxiety Rating Scale (STARS) corresponds to its established six-factor structure.

Using survey responses from 182 university students, a partial-correlation network was constructed from the 51 STARS items. Network measures, nominal assortativity, and Walktrap community detection were used to examine the overall network structure and the extent to which detected communities aligned with the six established factors.

# Repository Contents

- `STARS Analysis.Rmd` — R Markdown file containing the code for network construction and analysis.
  
- `STARS Analysis.html` — Rendered HTML version of the R Markdown file, displaying the analysis code, results, and visualisations.

- `stars-data_182.csv` — Dataset containing the STARS responses from 182 students.

- `stars-item.md` — Reference document describing the 51 STARS items and their corresponding six factors.

# Requirements

The analysis was conducted in R using the following packages:

- `igraph`

- `tidyverse`

- `bootnet`

The rmarkdown and knitr packages are also needed to render the R Markdown file.

# Reproducing the Analysis

1. Download the repository as a ZIP file and extract its contents.

2. Open `STARS Analysis.Rmd` in RStudio.

3. Install any missing R packages listed above.

4. Ensure that `STARS Analysis.Rmd` and `stars-data_182.csv` are located in the same folder.

5.  Knit in RStudio to run the analysis and generate an HTML report.

The R Markdown file contains the complete analysis, including:

- Construction of a partial-correlation network using the 51 STARS items, retaining statistically significant associations.

- Calculation of macro-level network measures, including average degree, density, clustering coefficient, average shortest-path length, and diameter.

- Calculation of nominal assortativity using the six STARS factor classifications.

- Walktrap community detection and modularity calculation.

- Comparison of detected community membership with the established STARS factors.

# Main Findings

The network consisted of 51 nodes and 128 edges. Nominal assortativity was 0.246, while Walktrap identified nine communities with a modularity score of 0.382. The findings suggest partial correspondence between the network structure and the established six-factor structure of STARS.
