# Data Science Job Posting Data Cleaning

## Introduction

This repository contains a Jupyter notebook designed to clean raw text data from job postings and prepare it for analysis.

## Contents

- `DataScience_JobPosting_Cleaning.ipynb`: Jupyter notebook for data cleaning.
- `raw_data/`: Folder containing the input CSV with the original unprocessed job posting text.
- `cleaned_data/`: Folder to save the output cleaned CSV or parquet file.

## Data Cleaning Steps

The notebook transforms the raw job posting text into a structured dataframe suitable for analysis. Key steps include:

- Extracting salary ranges and converting them to min, max, and average numeric columns.
- Parsing programming languages and tools into boolean columns.
- Identifying degree requirements from text.
- Categorizing job rating levels.
- Standardizing company names and calculating their ages.
- Obtaining state locations from text.
- Determining seniority levels from job titles.

## Running the Notebook

To run the cleaning process:

1. Clone this repository.
2. Install the required dependencies: Pandas, Numpy, Regex.
3. Execute the notebook cells to load data, clean it, and output the final dataframe.
4. Save the cleaned data to CSV or parquet files.

The notebook is well-commented to explain the code and processing logic.

## Data Analysis

The cleaned structured data enables the analysis of trends in data science job postings over time, including:

- Salary ranges by experience level.
- Most in-demand skills.
- Company size and industry distribution.
- Geographic hiring patterns.

This repository provides a template for preparing noisy text data for statistical analysis and modeling.

## Data Sources

(https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor)


## Contact Information

email- minthawphyo03@gmail.com
