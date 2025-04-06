# Overview

Welcome to this data analysis project, which explores whether younger individuals with clinically normal cholesterol levels face an increased risk of cardiovascular disease (CVD) when secondary risk factors such as elevated blood pressure or ST depression are present. This repository is organized to ensure clarity and reproducibility. Below is an overview of the folder structure:

#### Folder Structure

#### code: 

Contains all scripts and Quarto files used for the project. This folder is further organized into the following subfolders:

#### eda-code: 

Contains scripts for Exploratory Data Analysis (EDA), including code for generating summary statistics, histograms, density plots, boxplots, violin plots, and correlation matrices.

#### analysis-code: 

Houses scripts for the main statistical and predictive modeling analyses, such as logistic regression, chi-square tests, and machine learning models (LASSO, random forest).

#### processing-code: 

Includes scripts for data cleaning, transformation, and processing. This is where the raw data is converted into a form ready for analysis.

#### data: 

Contains all data files relevant to the project, divided into:

#### raw-data: 

The original, unprocessed dataset in CSV format.

#### processed-data: 

The cleaned and processed dataset saved in RDS format, ready for further analysis. This folder also houses the codebook for the dataset.

#### products: 

-   Contains final deliverables and project outputs, including: The manuscript, provided as a Quarto file (manuscript.qmd) that contains the complete analysis and code.

-   A separate document (manuscript.docx) that provides a brief introduction to the analysis and a summary of the key findings.

#### results: 

Stores all automatically generated outputs from the analysis. This folder is organized into:

#### figures: 

Contains visualizations (e.g., histograms, bar plots, violin plots) produced during the analysis.

#### tables: 

Contains summary tables and other output tables in RDS format that support the findings presented in the manuscript.

#### README.md: 

This file, which provides an overview of the repository and guidance on how to get started.

## Getting Started

1.  Clone or Download the Repository: Begin by cloning this repository to your local machine or downloading it as a ZIP file.

2.  Open the Project: Open the project in RStudio using the provided .Rproj file to set the correct working directory.

3.  Install Required Packages: Ensure that you have all necessary R packages installed. Consider using renv or a similar package management tool for reproducibility.

4.  Run the Code:

-    Start with the scripts in the processing-code subfolder to clean and process the raw data.

-   Proceed with the scripts in eda-code to conduct exploratory data analysis.

-   Run the scripts in analysis-code to perform the main statistical and predictive analyses.

5.  View the Results: Check the results folder for generated figures and tables, and refer to the products folder for the final manuscript (manuscript.qmd) and accompanying document (manuscript.docx).

## Contributing

If you plan to extend or modify this analysis, please maintain the established folder structure for consistency. Use descriptive commit messages, and include README.md files or comments in any new folders or files to explain their purpose.
