# SAS_Clinical_Report

Welcome to the SAS Biostatistics Analysis repository. This repository contains a SAS report used for biostatistical analyses, including data import, descriptive statistics, hypothesis testing, ANOVA, chi-square tests, and correlation analysis.

## Table of Contents
- [Introduction](#introduction)
- [File Descriptions](#file-descriptions)
- [Usage](#usage)
- [Results Summary](#results-summary)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The report provides a collection of SAS scripts that perform various biostatistical analyses on datasets related to medical and clinical research. The analyses include descriptive statistics, normality tests, ANOVA, chi-square tests, and correlation analyses.

## File Descriptions

### 1. `SAS Biostatistics Analysis.pdf`
This document contains the results and interpretations of the biostatistical analyses performed using the SAS scripts. It includes the following sections:

- **Question 1: Bone Marrow Dataset**
  - **a. Descriptive Statistics**: Provides a summary of disease-free survival time by group.
  - **b. Normality Test**: Checks the normality assumption using histograms.
  - **c. ANOVA Test**: Tests for differences in disease-free survival time among groups, including post-hoc tests.

- **Question 2: Clinic Dataset**
  - **a. 2x2 Table Creation**: Creates a contingency table for treatment and response.
  - **b. Chi-Square Test**: Tests for an association between treatment and response, including Fisher's exact test due to low counts.

- **Question 3: Hypoxia Dataset**
  - **a. Descriptive Statistics**: Provides statistics for TWA_HR, age, gender, sleeptime, and AHI.
  - **b. ANOVA Test**: Tests for differences in TWA_HR among AHI levels.
  - **c. Scatter Plots and Correlation Analysis**: Analyzes the relationships between TWA_HR, sleeptime, and Min_Sao2.

## Usage
1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/SAS_Biostatistics_Analysis.git
    ```
2. Open the SAS files in your SAS environment.
3. Modify the file paths and parameters as needed.
4. Run the scripts to perform the biostatistical analyses.

## Results Summary
### Question 1: Bone Marrow Dataset
- **Descriptive Statistics**: Significant differences in disease-free survival times among groups.
- **Normality Test**: Data do not follow a normal distribution.
- **ANOVA and Post-Hoc Tests**: Significant differences in disease-free survival times among groups, particularly between AML-High Risk and other groups.

### Question 2: Clinic Dataset
- **Chi-Square Test**: No significant association between treatment and response.

### Question 3: Hypoxia Dataset
- **Descriptive Statistics**: Summary statistics for TWA_HR, age, gender, sleeptime, and AHI.
- **ANOVA Test**: No significant differences in TWA_HR among AHI levels.
- **Correlation Analysis**: No significant correlations among TWA_HR, sleeptime, and Min_Sao2.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please create an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
