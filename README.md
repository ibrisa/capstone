# Capstone Code

This folder contains various Python code files that analyze research on a rare blood disorder, Hereditary Angioedema, on PubMed and the global awareness of HAE and medicine availability using the PubMed API and NLTK.

## File Descriptions
HAE Medicine Availabile.ipynb: This file analyzes the availability of HAE medicine globally. It uses data from various sources to identify which countries have access to HAE medication and the types of medication available.

PubMed Data.ipynb: This file uses the PubMed API to download data from medical journals from 1947-2022 that contain the keyword "hereditary angioedema". This data is used for further analysis of HAE-related keywords.

Cleaned NLP Pub Med Results.ipynb: This file uses the Natural Language Toolkit (NLTK) to analyze the frequency of HAE-related keywords in the downloaded PubMed data. It identifies the most common scientific terms, medicine, symptoms, triggers and other relevant concepts/keywords related to HAE.

## Intention
The intention of this code is to examine the global awareness of HAE and identify which countries have access to HAE medication. By using the PubMed API and NLTK, we can gain a better understanding of the frequency of HAE-related keywords in medical literature and identify potential areas for further research and intervention.

## Data Sources
The availability of HAE medication is sourced from various official and unofficial databases, namely the Hereditary Angioedema International organization's website. Because this is from a website, the data might change. This data was accessed and compiled on September 20, 2022 and updated on February 14, 2023.
The PubMed API is used to download data from medical journals that contain the keyword "hereditary angioedema" and other variations of these words. The data used in the visualizations created as part of this capstone project was downloaded in November of 2022.

## Requirements
Python 3.6 or higher

## Instructions
1. Run HAE Medicine Availabile.ipynb to analyze the availability of HAE medication globally.
2. Run PubMed Data.ipynb to download data from medical journals that contain the keyword "hereditary angioedema".
3. Run Cleaned NLP Pub Med Results.ipynb to analyze the frequency of HAE-related keywords in the downloaded PubMed data.

