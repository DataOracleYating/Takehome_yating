# Pathnostic Take Home Project

This repository contains the work for a take-home test provided by Pathnostic, aiming to perform exploratory data analysis on a dataset derived from urine test results.

## Project Overview

The task involves data visualization, writing a unit test, thorough documentation, and proper use of Git and GitHub for version control. The aim is to present the data in a clear, meaningful way, and ensure that code quality is maintained throughout the process.

## Dataset

The dataset, "urine_test_data.csv", consists of 1000 samples of urine test data. Each entry represents a single sample, with the following features:

- Cell counts for 10 different organisms (labeled as `Organism_1` to `Organism_10`)
- Resistance (R) or Sensitivity (S) for 17 different antibiotics (labeled as `Antibiotic_1` to `Antibiotic_17`)
- Presence (1) or Absence (0) of 5 different resistance genes (labeled as `Gene_1` to `Gene_5`)

## Tasks and Objectives

1. **Data Visualization**: Generate matplotlib/seaborn plots that show:
   - The percentage of samples resistant (R) and sensitive (S) to each antibiotic.
   - The presence of each resistance gene across the samples.
   - The distribution of cell counts for each organism.

   The plots are accompanied by appropriate legends and labeling for enhanced interpretability.

2. **Unit Testing**: Write a function that adds new data to the existing dataframe and a corresponding unit test that verifies whether the data has been added correctly.

3. **Documentation**: Provide clear and concise documentation for all code, which includes comments in the code, usage examples for functions, and explanations of the chosen plotting method.

4. **Version Control with Git and GitHub**: This repository is a result of rigorous version control using Git and GitHub. All significant changes and improvements are documented through commits and at least one pull request.

## Repository Contents

This repository includes Python scripts/notebooks for data processing, analysis, visualization, as well as tests to ensure the correctness of the key functionalities.

## License

This project is released under the MIT License.
