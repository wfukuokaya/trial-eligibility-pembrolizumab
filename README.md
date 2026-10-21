# Effectiveness of pembrolizumab in trial-ineligible patients with metastatic urothelial carcinoma

This repository contains the R code used for the analysis presented in the research paper "Effectiveness of pembrolizumab in trial-ineligible patients with metastatic urothelial carcinoma." The study assesses the effectiveness of pembrolizumab in patients with metastatic urothelial carcinoma (UC) who were ineligible for the KEYNOTE-045 trial.

## Abstract
The study evaluates the outcomes of pembrolizumab therapy in trial-ineligible patients with platinum-treated metastatic UC. A multicenter retrospective study was conducted, analyzing data from 164 patients who received pembrolizumab as second-line therapy. The analysis used inverse probability of treatment weighting (IPTW) to balance patient characteristics and examined overall survival (OS) and progression-free survival (PFS) using the IPTW-adjusted Kaplan-Meier curves. Restricted mean survival times (RMSTs) for OS and PFS were compared between ineligible and eligible patients. We did not find evidence of inferior outcomes in patients with metastatic UC who were ineligible for the KEYNOTE-045 trial, suggesting that the eligibility criteria for the trial may be too restrictive.

## Publication
The study has been published in **Cancer Immunology, Immunotherapy** and is available at the following link: [https://link.springer.com/article/10.1007/s00262-022-03291-5](https://link.springer.com/article/10.1007/s00262-022-03291-5).

## Repository contents

| File | Description |
|---|---|
| `manuscript_file.qmd` | Manuscript source (Quarto) |
| `script.qmd` | Analysis script (Quarto) |

## Requirements

R (version 4.x) with the following packages: `ggconsort`.

## Data availability

This repository contains analysis code only. The patient-level data analysed in the study are not distributed here.

## License

The code in this repository is released under the [MIT License](LICENSE).
