

# Template Repository  

## Overview  
This repository provides a structured template for reproducible research projects. It includes directories for data, scripts, functions, tables, and documentation to maintain a well-organized workflow.  

## Structure  

```
template-repository/
├── Scripts/
│   └── 01-report-template.Rmd
├── Docs/
│   ├── Themes/
│   │   ├── preamble-pdf.tex
│   │   └── html.css
│   └── References/
│       ├── references.bib
│       └── Styles/
│           └── apa.csl
├── Output/
│   ├── Figures/
│   └── Tables/
├── R/
│   ├── utility_functions.R
│   └── load_packages.R
├── .gitignore
├── README.md
└── template-repository.Rproj
```

- **Scripts/**: Contains R scripts for data analysis and visualization.
  - `01-template-rmarkdown-pdf.Rmd` — PDF report template
  - `02-rmarkdown-template-html.Rmd` — HTML report template
  - `03-cdc-svi-analysis.Rmd` — **USEPA CDC Social Vulnerability Index (SVI) Analysis**: downloads the 2022 CDC/ATSDR county-level SVI dataset, cleans and recodes missing values, produces summary statistics, distribution plots, state-level rankings, choropleth maps for the overall SVI and each of the four SVI themes, a pairwise correlation matrix, and a table of the most vulnerable counties.
- **Docs/**: Contains documentation files, including LaTeX templates and references.
- **Output/**: Contains output files, figures, and tables generated from the analysis.
- **html.css**: CSS file for HTML output.
- **pdf.tex**: LaTeX template for PDF output.
- **references.bib**: BibTeX file for managing references.
- **apa.csl**: Citation Style Language file for APA formatting.
- **helper_functions.R**: Lcoation for functions for data analysis.
 **README.md**: This file, providing an overview of the repository.
 
## How to use  
1. Clone the repository to your local machine.
2. Add your raw data files to the `Data/Raw/` directory.
3. Write your analysis scripts in the `Scripts/` directory.
4. Save your output files, figures, and tables in the `Output/` directory.
5. Use the `Docs/Themes/` directory to customize the appearance of your reports.
6. Use the `Docs/References/` directory to manage your references and citations.

## Installation  
Clone the repository:  
```bash
git clone git@github.com:your-username/Template_Repository.git
cd Template_Repository
```
---

### **Contact Information:**
**Robert J. Dellinger**  
**Ph.D. Student, Atmospheric & Oceanic Sciences, UCLA**  
**rjdellinger[at]ucla.edu**  

[![GitHub](https://img.shields.io/badge/GitHub-rob--dellinger-181717?logo=github&logoColor=white)](https://github.com/rob-dellinger)  

---
