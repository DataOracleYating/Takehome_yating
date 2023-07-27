# Take Home Project

Welcome to my Take Home Project! This repository contains my work for a take-home test, where the primary objective is to perform exploratory data analysis on a dataset of urine test results.

## Project Scope

This project includes elements of data visualization, unit test creation, comprehensive documentation, and effective use of Git and GitHub for version control. My main goal has been to present the data clearly and meaningfully, ensuring that the code quality remains top-notch throughout the process.

## Repository Structure

This repository is structured as follows:

- `data`: This folder contains the dataset used in this project.
- `notebooks`: This folder houses the Jupyter notebooks that contain the exploratory data analysis and unit tests. It also includes a `requirements.txt` file listing all necessary Python packages.
- `.gitignore`: This file specifies which files and directories Git should ignore.
- `README.md`: This file provides an overview of the project and instructions for running the code.

## The Dataset: "urine_test_data.csv"

The dataset, located in the `data` folder and named "urine_test_data.csv", comprises 1000 samples of urine test results. Each entry represents a single sample, with the following features:

- Cell counts for 10 different organisms (labeled Organism_1 through Organism_10)
- Resistance (R) or Sensitivity (S) to 17 different antibiotics (labeled Antibiotic_1 through Antibiotic_17)
- Presence (1) or Absence (0) of 5 different resistance genes (labeled Gene_1 through Gene_5)

## Usage

To run the Jupyter notebooks included in this repository, follow these steps:

1. Clone the repository to your local machine using `git clone https://github.com/DataOracleYating/Takehome_yating`.
2. Navigate to the `notebooks` folder in your terminal or command line interface.
3. Install the necessary Python packages by running `pip install -r requirements.txt` in your terminal/command line interface.
4. Open and run the Jupyter notebooks (`takehome_yating.ipnyb` and `unit_test.ipnyb`) in order. The `unit_test.ipnyb` notebook contains the unit test for the function that adds new data to the existing dataframe.

## Results and Findings

Based on our current results:

- The samples display the highest resistance to Antibiotic 1, with resistance decreasing gradually through to Antibiotic 17, which shows the least resistance.
- In terms of the prevalence of each resistance gene across the samples, Gene1 is the most common, gradually decreasing in prevalence through to Gene5. Further studies would be beneficial to explore the association between the presence of resistance genes and the level of antibiotic resistance.
- The cell counts for each organism present in the data are highly skewed, with many instances of zero counts and a long tail extending to the right. This suggests a high level of variability in the presence of different organisms in the samples.

## License

This project is released under the MIT License. Please refer to the `LICENSE` file in this repository for more information.
