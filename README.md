# Codelists for Healthcare Use by Diagnostic Routes Prior to Lung Cancer Diagnosis

This repository contains curated and adapted codelists of Read v2, SNOMED, ICD-10, and ICD-O-3 codes for variables included in a study on pre-diagnostic healthcare use before lung cancer diagnosis. These codelists were collated from multiple sources and code browsers. Original sources have been cited, and adapted versions are included only where changes were made. Users are encouraged to cite the original work where applicable.

## Included Codelists

| Code List Name                    | Description                                                                     | Source(s)        | License                                 |
|----------------------------------|---------------------------------------------------------------------------------|------------------|------------------------------------------|
| `constypes.csv`                  | Consultation types used in primary care                                         | [1], [2]         | CC BY 4.0                                |
| `chest_imaging_ncip.csv`         | Chest imaging investigations relevant to lung pathology                         | [3]              | CC BY-NC 4.0                             |
| `symptoms_readv2.csv`            | Symptom codes relevant to respiratory symptoms in primary care                  | [4], [5], [6]    | Mixed: [4] OGL v3.0, [5] CC BY-NC 4.0, [6] CC BY 4.0 |
| `copd_readv2.csv`                | COPD-related Read codes from primary care data                                  | [7], [8]         | [7] CC BY 4.0, [8] GitHub License (TBC) |
| `copd_icd10.csv`                 | COPD ICD-10 diagnosis codes from secondary care data                             | [7], [8]         | [7] CC BY 4.0, [8] GitHub License (TBC) |
| `ethnicity_ncras.csv`            | Ethnicity categories from NCRAS                                                 | [9]              | Open Government Licence v3.0            |
| `smoking_readv2.csv`             | Read codes indicating smoking status from primary care                          | [10], [11]       | [10] Standard Copyright, [11] CC BY 4.0 |
| `elixhauser_icd10.csv`           | ICD-10 codes for Elixhauser comorbidity index from secondary care               | [12], [13]       | Standard Copyright                      |
| `lung_cancer_morphology_icdo3.csv`| Morphology codes for lung cancer (ICD-O-3)                                      | [14]             | CC BY-NC 4.0                             |

## Referencing

If using or adapting any of these codelists, please cite the original sources as appropriate. Where codelists were created or significantly adapted for this study, they have been cited accordingly or provided under an open license.

## References

1. Price, S., et al. (2023). Examining methodology to identify patterns of consulting in primary care for different groups of patients before a diagnosis of cancer. *Cancer Epidemiology, 82*, 102310. https://doi.org/10.1016/j.canep.2023.102310  
2. Zhang, C. X., et al. (2022). Migrants’ primary care utilisation before and during the COVID-19 pandemic in England. *Lancet Regional Health – Europe, 20*, 100455. https://doi.org/10.1016/j.lanepe.2022.100455  
3. Koo, M. M., et al. (2024). Guideline concordance for timely chest imaging. *Thorax, 79*, 236–244. https://doi.org/10.1136/thorax-2023-220003  
4. NICE guideline (2019). NG122: Lung cancer: diagnosis and management. https://www.nice.org.uk/guidance/ng122  
5. Hamilton, W., et al. (2015). Suspected cancer (part 2—adults). *BMJ, 350*, h3044. https://doi.org/10.1136/bmj.h3044  
6. Moore, S. F., et al. (2021). Impact of changing risk thresholds for urgent investigation. *British Journal of Cancer, 125*, 1593–1597. https://doi.org/10.1038/s41416-021-01465-y  
7. Wickramasinghe, B., et al. (2023). Pre-diagnostic prescribing patterns in dyspnoea patients. *Cancer Epidemiology, 86*, 102429. https://doi.org/10.1016/j.canep.2023.102429  
8. Whitfield, E. COPD Phenotypes. GitHub Repository. https://github.com/ekw26/Atlas-phenotypes/Codelists/COPD.csv  
9. NHS Data Dictionary. Ethnic Category. https://v2.datadictionary.nhs.uk/data_dictionary/classes/e/ethnic_category_de.asp@shownav=0.html  
10. Booth, H. P., et al. (2013). Validity of smoking prevalence estimates. *Pharmacoepidemiology and Drug Safety, 22*, 1357–1361. https://doi.org/10.1002/pds.3497 [CC BY-NC-ND 3.0]  
11. Marston, L., et al. (2014). Validity of routinely recorded smoking status. *BMJ Open, 4*, e004958. https://doi.org/10.1136/bmjopen-2014-004958  
12. Elixhauser, A., et al. (1998). Comorbidity measures for use with administrative data. *Medical Care, 36*, 8–27. https://doi.org/10.1097/00005650-199801000-00004  
13. Quan, H., et al. (2005). Coding algorithms for defining comorbidities. *Medical Care, 43*, 1130–1139. https://doi.org/10.1097/01.mlr.0000182534.19832.83  
14. Khakwani, A., et al. (2019). Outcomes of small-cell lung cancer patients. *Thorax, 74*, 466–472. https://doi.org/10.1136/thoraxjnl-2018-212744

## License

All original and adapted code lists in this repository are shared under the license indicated per file in the table above. Users are responsible for ensuring compliance with licensing terms of any third-party sources.


---

### Disclaimer on `elixhauser_icd10.csv`

This codelist is based on the following publications:

> Elixhauser, A., et al. (1998). Comorbidity measures for use with administrative data. *Medical Care, 36*, 8–27. https://doi.org/10.1097/00005650-199801000-00004  

> Quan, H., Sundararajan, V., Halfon, P., et al. (2005). *Coding Algorithms for Defining Comorbidities in ICD-9-CM and ICD-10 Administrative Data*. Medical Care, 43(11), 1130–1139. https://doi.org/10.1097/01.mlr.0000182534.19832.83

These articles are © 2005 Lippincott Williams and is published under **standard copyright** by **Wolters Kluwer Health, Inc.** It is **not open access**, and permission is required for any reuse beyond fair use.

Please refer to the original publication for the official coding algorithms.
