# RStudio Tasks
This repository contains a collection of R tasks and course exercises I completed using R / RStudio as part of my university courses. Each top-level folder corresponds to a task and contains the R (or rendered) outputs for that task.

Below I summarise what each directory contains and a short note about what I learned from the PDF/HTML (or the R script) in that folder.

## Repository structure (top-level folders)

- 01 intro R
- 02 intro R
- 03 TABULAR
- 04 TABULAR
- 05 TABULAR
- 06 TABULAR
- 07 CONTR
- 08 CONTR
- 09 DESCRIPTIVE 
- 10 INFERENCE 
- 11 FINAL PROJECT (PCA)

---

## 01 intro R
Files of note:
- tarea1INTROR.pdf — https://github.com/julioruizm14/Tasks-RStudio/blob/main/01%20intro%20R/tarea1INTROR.pdf
- tarea1INTROR.Rmd — https://github.com/julioruizm14/Tasks-RStudio/blob/main/01%20intro%20R/tarea1INTROR.Rmd (source)
- iris.csv, tratamiento.csv — example datasets

What I learned:
- Basic R syntax and RStudio workflow: running scripts, using R Markdown to produce reports (PDF).
- How to import CSV data into R and inspect data frames (head, str, summary).
- Basic exploratory data analysis: summary statistics, simple plots (histograms, boxplots, scatterplots).
- Simple data transformations (creating factors, subsetting rows/columns).

---

## 02 intro R
Files of note:
- tarea2INTROR.R — https://github.com/julioruizm14/Tasks-RStudio/blob/main/02%20intro%20R/tarea2INTROR.R
- biom2003.csv — dataset used in the exercise

What I learned:
- Continued practice with data import and cleaning using base R and scripts.
- Practice writing reproducible R scripts that perform a sequence of analyses (data cleaning → summaries → plots).
- Getting more comfortable with vectorized operations, indexing, and basic plotting customisations.

---

## 03 TABULAR
Files of note:
- Tarea1TABULAR.pdf — https://github.com/julioruizm14/Tasks-RStudio/blob/main/03%20TABULAR/Tarea1TABULAR.pdf
- Tarea1TABULAR.Rmd — source R Markdown
- autoevaluacion1.pdf — https://github.com/julioruizm14/Tasks-RStudio/blob/main/03%20TABULAR/autoevaluacion1.pdf
- tiendas.csv — example tabular dataset

What I learned:
- Working with tabular data at scale: reading/writing CSVs, checking data types, handling categorical variables.
- Data wrangling basics: filtering, selecting, arranging, creating new summary columns.
- Generating summary tables and visualisations to understand patterns in tabular datasets.

---

## 04 TABULAR
Files of note:
- Tarea2TABULAR.pdf — https://github.com/julioruizm14/Tasks-RStudio/blob/main/04%20TABULAR/Tarea2TABULAR.pdf
- autoevaluacion2.pdf — https://github.com/julioruizm14/Tasks-RStudio/blob/main/04%20TABULAR/autoevaluacion2.pdf
- vuelos.csv — large flights dataset for practice

What I learned:
- Handling larger tabular datasets (performance considerations, readr vs base read.csv).
- Grouped summaries and aggregations (group_by + summarize, or aggregate) to extract insights from many rows.
- Dealing with missing or inconsistent values and performing basic data cleaning before analysis.

---

## 05 TABULAR
Files of note:
- Tarea3TABULAR.pdf — https://github.com/julioruizm14/Tasks-RStudio/blob/main/05%20TABULAR/Tarea3TABULAR.pdf
- autoevaluacion3.pdf — https://github.com/julioruizm14/Tasks-RStudio/blob/main/05%20TABULAR/autoevaluacion3.pdf

What I learned:
- More advanced tabular manipulations: reshaping (wide ↔ long), joins/merges between tables.
- Creating reproducible reports combining code, results and narrative (R Markdown).
- Formulating and answering specific questions using grouped analyses and visual summaries.

---

## 06 TABULAR
Files of note:
- Tarea4TABULAR.pdf — https://github.com/julioruizm14/Tasks-RStudio/blob/main/06%20TABULAR/Tarea4TABULAR.pdf
- autoevaluacion4.Rmd / .tex / .log — sources and build artifacts

What I learned:
- Consolidation of tabular data skills: thorough data cleaning, advanced grouping and multi-table workflows.
- Exporting results and automated report generation (producing PDFs via R Markdown / LaTeX).
- Debugging reproducible builds (interpreting logs / LaTeX artifacts when rendering fails).

---

## 07 CONTR
Files of note:
- Tarea1CONTR.html — https://github.com/julioruizm14/Tasks-RStudio/blob/main/07%20CONTR/Tarea1CONTR.html
- Tarea1CONTR.Rmd — source R Markdown
- medicamentos.csv — dataset used in the exercises

What I learned:
- Statistical contrasts and hypothesis testing basics (interpreting group differences).
- Performing and interpreting t-tests, ANOVA or similar group-comparison procedures (depending on the exercise).
- Presenting statistical test results clearly in an HTML report (tables, test statistics, p-values, and conclusions).

---

## 08 CONTR
Files of note:
- Tarea2CONTR.html — https://github.com/julioruizm14/Tasks-RStudio/blob/main/08%20CONTR/Tarea2CONTR.html
- Tarea2CONTR.Rmd — source R Markdown
- dieta.csv, william.csv — example datasets

What I learned:
- More practice with contrasts and post-hoc comparisons; possibly non-parametric alternatives where assumptions are not met.
- Applying tests to real datasets and writing up concise interpretations for each result.
- Creating reproducible HTML reports showing code, outputs and discussion.

---
## 09 DESCRIPTIVE
Files of note:
- memoria.pdf — **R101. Descriptivos base de datos Galaad**
- database.csv — Dataset used (Osteopenia variables)

What I learned:
- Performing a complete descriptive analysis of a medical dataset ("Galaad"), including data preparation and cleaning.
- Analyzing categorical and numerical variables such as Sex, Gestation Week (SG), Birth Weight, and Treatment Group.
- Visualising data distributions using `ggplot2`: creating bar charts for demographic factors and boxplots to analyze Weight over time and Hospitalization days.
- Formatting professional summary tables using packages like `kableExtra`.

---

## 10 INFERENCE
Files of note:
- memoria inferencia.pdf — **R301. Inferencia base de datos Galaad**
- database.csv — Dataset used

What I learned:
- Conducting advanced statistical inference, specifically **Mixed ANOVA** to analyze weight changes over different time points and demographic groups.
- Rigorously checking statistical assumptions: Normality (Shapiro-Wilk), Homogeneity of variances (Fligner-Killeen), and Sphericity (Mauchly’s Test).
- Applying robust statistical methods (Greenhouse-Geisser correction) and non-parametric alternatives (Mann-Whitney U, Welch’s t-test, Wilcoxon) when assumptions were violated.
- Interpreting interaction plots and reporting p-values and effect sizes ($\eta^2$) according to scientific standards (APA style).

---

## 11 FINAL PROJECT (PCA)
Files of note:
- memoria final.pdf — **Felicidad en el mundo. Análisis de componentes principales**
- world-happiness-report-2021.csv — Dataset from Kaggle

What I learned:
- Executing a **Principal Component Analysis (PCA)** to reduce dimensionality and analyze the "World Happiness Report 2021".
- Data preprocessing and generating correlation matrices to identify redundancies between variables like GDP, Social Support, and Corruption.
- Validating the suitability of PCA using the **Kaiser-Meyer-Olkin (KMO)** index.
- Visualising multivariate results: Using Scree plots to decide on component retention and Biplots to interpret the relationship between variables and the positioning of countries in the new dimensions.
 
---

## Notes & how to reproduce
- Most exercises were authored as R Markdown documents (.Rmd) and rendered to PDF or HTML. The rendered outputs are included in each folder (PDF/HTML), and the corresponding .Rmd or .R scripts are the sources.
- To reproduce any report:
  1. Open the corresponding .Rmd or .R file in RStudio.
  2. Make sure required packages (tidyverse, knitr, rmarkdown, etc.) are installed.
  3. Knit the document to produce the same PDF/HTML output.

---

If you want, I can:
- Add badges, a license, or a detailed list of packages used per task.
- Generate a single index page linking directly to each rendered PDF/HTML for easier navigation.
- Expand any directory summary with more detail (for example, list the exact functions or tests used) after extracting the Rmd/R source.

Author: julioruizm14
