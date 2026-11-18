# FredianiEtAl_TransBehavMed_2026_HealthFidelityChecklist

Repository Description: R Code and Data for Paper: Applying and refining the 11 for Health fidelity checklist: treatment delivery of the 11 for Health programme in a US after-school setting; by J. Frediani et.al. in Translational Behavioral Medicine submitted in 2026

## README.TXT Content

### FIDELITY ANALYSIS

----

### OVERVIEW

R Markdown script that summarizes intervention fidelity and inter-rater
reliability for two session types (Football and Health Message). Two reviewers
rated whether each behavior change technique (BCT) was delivered each week.
Knitting the file produces a single HTML report.

### CONTENTS

* Fidelity checklist data.xlsx (data)
* reproducable_code.Rmd (Rmarkdown)
* reproducable_code.html (knitted document)

### DATA KEY

|-----------|-----------------------------------|
| Reviewer  | 1 or 2 |
| Session   | 1 = Football, 2 = Health Message |
| BCT number | identifier for the behavior change technique |
| Week      | study week |
| presence  | 1 = Present, 2 = Partially Present, 3 = Not Present |

### HOW TO RUN

1. Install the required packages (see below).
2. Open the .Rmd file in RStudio and click Knit

### REQUIRED R PACKAGES

`tidyverse`, `data.table`, `Hmisc`, `gtsummary`, `haven`, `readxl`, `irr`, `ggplot2`, `epiR`

### OUTPUT

HTML report (tables and figures).
