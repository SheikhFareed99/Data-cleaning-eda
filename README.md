# Data Cleaning and EDA — Assignment 2

Version: **v1.0**  
Published: **2026-10-18**

This repository publishes the exact cleaned datasets used for Assignment 2 and Assignment 3 reproducibility.

## Datasets

| Cleaned file | Original source | Cleaning summary |
|---|---|---|
| `23L_0997_A2_netflix_cleaned.csv` | [Kaggle: Netflix Shows, Shivam Bansal](https://www.kaggle.com/datasets/shivamb/netflix-shows) | Parsed `date_added`; repaired rows in which a duration had shifted into `rating`; standardized text; labelled missing metadata as `Unknown`; added year/month added, country/genre counts, movie minutes, TV seasons, and release-to-added gap. No genuine titles were removed. |
| `23L_0997_A2_supermarket_cleaned.csv` | Instructor-provided `supermarket_Sales.csv` | Parsed date/time fields; retained all complete, unique transactions; added hour, weekday, month, and time-of-day variables; documented constant and redundant financial fields. |

## Reproducibility

`23L_0997_A2.ipynb` contains the full, executed EDA and cleaning workflow. Use the datasets tagged **v1.0** for Assignment 3 so that results remain reproducible.
