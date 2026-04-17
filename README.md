# OMDS-ModB2 - Dustin Nguyen

## 📁 Repository Contents

### Data Files

| File | Description |
|------|-------------|
| `epcg23.zip` | Main dataset from the National Survey of College Graduates (NSCG). Contains 548 columns of survey responses including education, employment, earnings, and demographic information. |
| `Dpcg23.csv` | Data dictionary for the main dataset. Maps variable names (SAS_NAME) to full descriptions and survey questions. |
| `N2BAMED.csv` | Field of study mapping. Translates numeric field codes to actual field names. |
| `Ppcg23.pdf` | PDF codebook with additional documentation and field descriptions. |
| `2023-NSCG-21_annotated_7Aug25.pdf` | Annotated codebook for the NSCG dataset. |
| `df_clean_99.csv.zip` | Cleaned dataset after removing top-coded earnings and capping at 99th percentile. Used as the base for all subsequent analysis. |
| `df_final.csv.zip` | Final cleaned dataset with STEM classification, debt mapping, and calculated total debt. Contains 82,977 rows and 552 columns. |
| `df_recent.csv.zip` | Subset of `df_final` containing only recent graduates (last 10 years of valid bachelor's degrees). Used for correlation matrix and PCA analysis. |

### Coverage Data Files (Week 2 HW)
| File | Description |
|------|-------------|
| `03-21_COVERAGE.csv` | NSC coverage percentages by institution type and region (2003-2023). |
| `03-21_MULTI_STATE.csv` | Coverage data for multi-state institutions. |
| `03-21_NSC_COVERAGE.csv` | Actual enrollment counts comparing NSC to IPEDS universe. |

### Homework Notebooks
| File | Description |
|------|-------------|
| `OMDS-ModB2-Week1-Nguyen-Dustin.ipynb` | HW1 |
| `OMDS-ModB2-Week2-Nguyen-Dustin.ipynb` | HW2 |
| `OMDS-ModB2-Week3-Nguyen-Dustin.ipynb` | HW3 |
| `OMDS-ModB2-Week4-Nguyen-Dustin.ipynb` | HW4 |
| `OMDS-ModB2-Week5-Nguyen-Dustin.ipynb` | HW5 |
| `OMDS-ModB2-Week6-Nguyen-Dustin.ipynb` | HW6 |
| `OMDS-ModB2-Week7-Nguyen-Dustin.ipynb` | HW7 |
| `OMDS-ModB2-Week8-Nguyen-Dustin.ipynb` | HW8 |
| `OMDS-ModB2-Week9-Nguyen-Dustin.ipynb` | HW9 |
| `OMDS-ModB2-Week10-Nguyen-Dustin.ipynb` | HW10 |
| `OMDS-ModB2-Week11-Nguyen-Dustin.ipynb` | HW11 |
| `OMDS-ModB2-Week12-Nguyen-Dustin.ipynb` | HW12 |

### Other Files
| File | Description |
|------|-------------|
| `bank_customers.csv` | Dataset for Week 1 HW |
| `README.md` | This file. |

## 📊 Project Overview

This project examines the education-to-employment pipeline for STEM graduates, focusing on:
- NSC data coverage quality across institutions, regions, and time
- How many STEM graduates actually work in STEM fields
- The earnings gap between those who stay in STEM and those who leave
- Whether STEM leavers earn enough to justify their educational investment
- Debt burden patterns across different graduate groups
