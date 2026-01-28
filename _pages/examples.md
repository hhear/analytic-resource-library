---
title: "Programming Code"
permalink: /examples/
---

## Common Cleaning workflows

The following were developed to facilitate analysis of harmonized data files generated from the HHEAR Data Repository. They are R Markdown files, unless otherwise specified. They are not meant for the study investigator-supplied data files or original HHEAR lab files that can also be downloaded from the Repository.

- **Phenotype Cleaning:** In the HHEAR Knowledge Graph, outcomes are represented as phenotypes, and harmonized datasets often store multiple phenotype codes for an individual in a single “Phenotype” column, with codes defined in the accompanying codebook. The provided code expands this column into separate indicator variables for each phenotype (1 = present, blank = absent) while retaining the original column; users can combine related indicators (e.g., has vs. does not have asthma) to create binary variables as needed. — [Download Source R Markdown](https://github.com/hhear/analytic-resource-library/blob/main/assets/files/Parse_Phenotype.Rmd)

- **Column Header Cleaning:** Within HHEAR harmonized datasets, column headers contain critical metadata including time period and units. We have created "cleaned" versions of all column headers that can be used as labels in visualizations. We provide both the file containing labels and sample code that will replace column headers with the clean versions. — [Download the R Markdown](../assets/files/Column_Header.Rmd) — [Download the File Containing Clean Labels]({{ "/assets/files/Clean_Column_Headers.RMD" | relative_url}})




## Suggested citation text

HHEAR Data Center (2026).<<Name of Program (Version No.).>> https://github.com/hhear/analytic-resource-library

Example: HHEAR Data Center (2026). Phenotype Cleaning (Version 1.0). https://github.com/hhear/analytic-resource-library


