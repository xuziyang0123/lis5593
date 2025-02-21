# Activity 3: Creating Metadata with dataspice

## Project Description
This project demonstrates how to document and publish a dataset using the `dataspice` package in R. The dataset contains climate data for 2023, including temperature, precipitation, and wind speed. The project includes the following steps:
1. Creating metadata templates using `dataspice`.
2. Populating metadata files (`access.csv`, `biblio.csv`, `creators.csv`, `attributes.csv`).
3. Generating a JSON-LD metadata file (`dataspice.json`).
4. Building a website to display the dataset metadata.
5. Publishing the website on GitHub Pages.

## File Structure
- **data/**: Contains the dataset and metadata files.
  - `climate_data_2023.csv`: The primary dataset.
  - `metadata/`: Contains metadata files.
    - `access.csv`: Data access information.
    - `biblio.csv`: Dataset-level metadata.
    - `creators.csv`: Creator information.
    - `attributes.csv`: Variable descriptions.
    - `dataspice.json`: Compiled metadata in JSON-LD format.
- **docs/**: Contains the generated website files.
  - `index.html`: The main webpage for the dataset.
- **activity-3.qmd**: The Quarto document describing the dataset and workflow.
- **README.md**: This file.
