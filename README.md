# Titanic Survival: Exploratory Data Analysis

**Adetola Ridwat Odulaja** · Academic analytics project

An exploration of survival patterns in Titanic passenger data, combining data preparation, feature engineering, grouped analysis, and visual communication.

**Focus:** Data quality · Exploratory analysis · Interpreting patterns

## Question

How do survival rates vary by passenger sex and class, and what do age, fare, and family-size distributions reveal about the dataset?

## Approach

- Load passenger data and inspect its structure.
- Fill missing ages with the mean where required.
- Create passenger-class categories and a family-size feature.
- Handle the absence of cabin information explicitly.
- Compare survival rates and visualize distributions, correlations, and outliers.
- Export a cleaned CSV for reuse.

## Recorded results

The saved notebook output reports:

| Group | Survival rate |
|---|---:|
| Female | 74.2% |
| Male | 19.0% |
| First class | 63.0% |
| Second class | 47.3% |
| Third class | 24.4% |

These are descriptive associations within the dataset. They do not establish causation.

## Why it matters

The project demonstrates how to turn raw records into interpretable comparisons, while keeping data preparation decisions visible—skills applicable to KPI validation and business reporting.

## Explore the work

- [Analysis notebook](Lesson_5_Titanic_EDA.ipynb)
- [Cleaned dataset](titanic_cleaned.csv)

## Run

Open the notebook in Google Colab and run the cells in sequence. It uses Python, Pandas, NumPy, Matplotlib, and Seaborn and downloads the source data from the URL embedded in the notebook.

## Limitations

The source has a different schema from some Titanic datasets. Cabin categories default to “Unknown” when no cabin column exists. Mean imputation can affect age distributions. Recorded results are from the saved run; this documentation update did not rerun the notebook.

[Explore my portfolio](https://github.com/Ridwat/Ethical-AI-Analysis/blob/main/PORTFOLIO.md)
