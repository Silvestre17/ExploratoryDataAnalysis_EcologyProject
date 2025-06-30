# 🌿 Ecology Perspectives: An Exploratory Data Analysis Project 🌍

<p align="center">
    <!-- Project Links -->
    <a href="https://github.com/Silvestre17/ExploratoryDataAnalysis_EcologyProject"><img src="https://img.shields.io/badge/Project_Repo-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
</p>

## 📝 Description

This project performs an in-depth **Exploratory Data Analysis (EDA)** on a survey dataset centered around **ecology**. The study investigates public perception of environmental issues, the level of concern for the destruction of natural resources, and how these views relate to the demographic profiles of residents in Portugal. The analysis leverages a multi-tool approach, using **Excel** for data preparation, **Jamovi** for initial statistical summaries, and **R** with **R Markdown** for comprehensive analysis and final reporting.

## ✨ Objective

The primary objective of this project is to analyze survey data to:
*   👤 **Profile the survey respondents** based on demographic characteristics (age, gender, education, etc.).
*   📊 **Assess public perception** of the severity of environmental problems like pollution and pesticide use.
*   🌡️ **Measure the level of concern** for the destruction of natural resources.
*   🤔 **Investigate the relationship** between a respondent's profile (e.g., education level) and their environmental perspectives.

## 🎓 Project Context

This group project was developed for the **Análise Exploratória de Dados** (*Exploratory Data Analysis*) course as part of the **[Licenciatura em Ciência de Dados](https://www.iscte-iul.pt/degree/code/0322/bachelor-degree-in-data-science)** (*Bachelor Degree in Data Science*) at **ISCTE-IUL** during the 2021/2022 academic year (1st year of bachelor's) in the 2nd semester.

## ⚙️ Technologies & Workflow

This project followed a structured, multi-stage workflow, utilizing the best features of each tool for a specific purpose.

1.  **Data Preparation in `Microsoft Excel`** 📋
    *   **Data Cleaning:** Initial data cleanup, including removing contextual information, renaming variables, and handling duplicates.
    *   **Data Validation:** Set up validation rules to prevent incorrect data entry (e.g., ensuring "Age" is a positive number).
    *   **Data Transformation:** Used `VLOOKUP` and `HLOOKUP` to decode categorical variables from numeric codes to descriptive text (e.g., transforming `1` to `"Married"`).
    *   **Frequency Tables:** Created initial frequency and pivot tables to get a first look at the data distribution.

<p align="center">
    <a href="https://www.microsoft.com/en-us/microsoft-365/excel">
        <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel" />
    </a>
</p>

2.  **Initial Analysis in `Jamovi`** 📈
    *   **Descriptive Statistics:** Generated detailed descriptive statistics tables (mean, median, standard deviation) for key quantitative variables like "Age" and "Level of Concern".
    *   **Cross-Tabulation & Visualization:** Created violin plots and other charts to explore relationships between variables, such as how "Level of Concern" varies across different education levels.

<p align="center">
    <a href="https://www.jamovi.org/">
        <img src="https://img.shields.io/badge/Jamovi-5D6D7E?style=for-the-badge&logo=jamovi&logoColor=white" alt="Jamovi" />
    </a>
</p>

3.  **In-Depth Analysis and Reporting in `R` & `R Markdown`** 📊
    *   **Data Import & Manipulation:** Imported the cleaned Excel file into R. Used libraries like `tidyverse` for advanced data wrangling.
    *   **Univariate & Bivariate Analysis:**
        *   Generated detailed frequency tables.
        *   Calculated descriptive statistics.
        *   Created advanced visualizations (histograms, boxplots, bar charts) with `ggplot2`.
    *   **Correlation Analysis:** Used **Pearson's R** and **Spearman's Rho** to test for linear and monotonic relationships between variables (e.g., "Age" and "Level of Concern").
    *   **Final Report:** Produced a final, polished HTML report using **R Markdown**, integrating code, visualizations, and narrative interpretation of the results.

<p align="center">
    <a href="https://www.r-project.org/">
        <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />
    </a>
    <a href="https://www.rstudio.com/">
        <img src="https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=rstudio&logoColor=white" alt="RStudio" />
    </a>
    <a href="https://rmarkdown.rstudio.com/">
        <img src="https://img.shields.io/badge/R_Markdown-5178B8?style=for-the-badge&logo=r&logoColor=white" alt="R Markdown" />
    </a>
</p>

> The final report is available in the `Grupo10_AED_Ecologia.html` file (or printed version as a PDF file `Grupo10_AED_Ecologia.pdf`), which includes all code, visualizations, and interpretations.

## 🔎 Key Findings from the Analysis

*   **Demographic Profile:** The sample consisted of **696 respondents** with a diverse range of ages (18-83 years, mean ≈ 40) and educational backgrounds.
*   **High Environmental Concern:** Overall, respondents showed a high level of concern for the destruction of natural resources, with an average score of **85.4 out of 100**.
*   **Global vs. National Perception:** Respondents perceived the environmental situation at a **global level as more severe** than at the national (Portuguese) level.
*   **Key Issues:** The "poor quality of the air we breathe" was identified as the most pressing environmental issue among the options provided.
*   **No Strong Correlation:** The analysis revealed **no significant linear correlation** between a person's age or education level and their level of concern for the environment. This suggests a widespread awareness of ecological issues across different demographic groups.

## 👥 Team Members (Group 10)

*   **André Silvestre** (Nº104532)
*   **Diogo Catarino** (Nº104745)
*   **Eduardo Silva** (Nº104943)
*   **Francisco Gomes** (Nº104944)

## 🇵🇹 Note

This project was developed using Portuguese from Portugal 🇵🇹.