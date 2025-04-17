# Data Processing Code

This folder contains scripts responsible for importing, inspecting, and cleaning the raw dataset. The output of this step is a cleaned dataset saved in RDS format, which serves as the foundation for all subsequent analysis steps.

## Files Included

-   **01_data_cleaning.qmd**\
    This script:
    -   Loads the raw cardiovascular dataset (`Cardiovascular_Disease_Dataset.csv`)
    -   Checks structure, dimensions, and summary statistics
    -   Visualizes missing values
    -   Converts numeric codes to labeled factors (e.g., gender, chest pain types)
    -   Saves the cleaned dataset to `data/processed-data/cleaned_df.rds`
