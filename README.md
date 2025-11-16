# Partisan or principled? Explaining political differences in attitudes about democratic norm violations

**Author:** Paul E. Teas  
**Affiliation:** University of Chicago  
**Published in:** *Personality and Social Psychology Bulletin* (2025)  
**OSF:** https://osf.io/bgrdc/  
**DOI:** https://doi.org/10.1177/01461672251372671
**Link to readable pdf:** https://www.researchgate.net/publication/397099748_Partisan_or_Principled_Explaining_Political_Differences_in_Attitudes_About_Violations_of_Democratic_Norms

---

## Overview

This repository contains the data and analysis code for Studies 1 and 2 from:

> Teas, P. E. (2025). *Partisan or principled? Explaining political differences in attitudes about democratic norm violations*. Personality and Social Psychology Bulletin.

Across two experiments (N = 2,352), this research tests when partisan differences in tolerance for democratic norm violations reflect:

- motivated reasoning  
- asymmetric democratic commitment  
- principled disagreement about democratic values  

Each study manipulates which democratic principle was violated and whether the violation helped or harmed the participant’s political party.

---

## Repository structure

data/
study1/
Democracy_S1.csv
study2/
Democracy_S2.csv

code/
study1/
Study1_Analyses_CLEAN.Rmd
study2/
Study2_Analyses_CLEAN.Rmd

output/
study1/
figures/
study2/
figures/

paper/
Democracy_ACCEPTED.pdf

---

## Reproducibility

All analyses use:

- R version 4.4.2  
- tidyverse  
- lme4  
- lmerTest  
- modelsummary  
- flextable  

Running the analyses

The analysis scripts are written as .Rmd files for organization and readability, but they are not intended to be knitted into full documents.

To reproduce each study:
	1.	Open the .Rmd file in RStudio
	2.	Run all chunks sequentially using “Run All” or by stepping through each section
	3.	Figures and tables will be written to the output/ directory

Study 1:
code/study1/Study1_Analyses_CLEAN.Rmd

Study 2:
code/study2/Study2_Analyses_CLEAN.Rmd

---

## Key findings (brief)


### Symmetric motivated reasoning  
Both Democrats and Republicans were:
- more supportive of violations that benefited their party  
- more opposed to violations that harmed their party  
- more likely to view politically beneficial violations as more less undemocratic  

### Asymmetric commitment (Study 1 only)  
Republicans were more responsive to partisan advantage, suggesting a greater willingness to tolerate undemocratic actions when politically beneficial.

### Issue-specific principled asymmetry  
Large partisan gaps emerged for vote-by-mail restrictions, but **not** for other voter-access scenarios.  
This suggests asymmetries are **context-dependent**, not dispositional.

---

## Citation

If you use this repository, please cite: 
Teas, P. E. (2025). Partisan or principled? Explaining political differences in attitudes about democratic norm violations. Personality and Social Psychology Bulletin.

---

## License

- Code: MIT License  
- Data: CC-BY 4.0 License  

---

## Contact

**Paul E. Teas**  
University of Chicago  
Email: pteas@uchicago.edu  
ORCID: https://orcid.org/0000-0002-4253-3759 


