# Data Directory - Decoding Blockbusters Project

This directory contains the datasets used in the "Decoding Blockbusters" project. It includes both the original raw data and the cleaned, processed data used for analysis.

## Contents

* **original_data/ :**
    * This subdirectory contains the original, unprocessed datasets.
    * These files represent the raw data as it was initially obtained.
    * They might contain missing values, inconsistencies, and outliers.
* **cleaned_data/ :**
    * This subdirectory contains the cleaned and processed datasets.
    * These files have undergone data cleaning and preprocessing steps, including:
        * Handling missing values (imputation or removal).
        * Correcting inconsistencies.
        * Addressing outliers.
        * Data type conversions.
        * Feature engineering (if applicable).
    * These cleaned datasets are used for the main analysis and modeling in the project.

## File Formats

* The datasets may be in various formats, such as:
    * CSV (.csv)
    * JSON (.json)
    * Other relevant formats.

## Usage

* The `original_data/` directory is provided for transparency and reproducibility. It allows others to understand the raw data used in the project.
* The `cleaned_data/` directory contains the datasets used for the analysis and modeling in the Jupyter notebooks located in the `notebooks/` directory.
* When running the notebooks, ensure that the file paths to the cleaned data are correctly specified.

## Notes

* Detailed information about the data cleaning and preprocessing steps can be found in the "Movies Data Cleaning & EDA" notebook located in the `notebooks/` directory.
* If the original data source requires specific attribution or licensing, please ensure that this information is included here.

## Contributing

* If you find any issues with the data or have suggestions for improvements, please feel free to submit pull requests or open issues.
