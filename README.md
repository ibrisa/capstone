# Capstone

This folder contains various Python code files that analyze research on a rare blood disorder, Hereditary Angioedema, on PubMed and the global awareness of HAE and medicine availability using the PubMed API and NLTK.

File Descriptions
hae_medicine_availability.py: This file analyzes the availability of HAE medicine globally. It uses data from various sources to identify which countries have access to HAE medication and the types of medication available.

pubmed_data_download.py: This file uses the PubMed API to download data from medical journals from 1947-2022 that contain the keyword "hereditary angioedema". This data is used for further analysis of HAE-related keywords.

nltk_analysis.py: This file uses the Natural Language Toolkit (NLTK) to analyze the frequency of HAE-related keywords in the downloaded PubMed data. It identifies the most common scientific terms, medicine, symptoms, and triggers related to HAE.

Intention
The intention of this code is to examine the global awareness of HAE and identify which countries have access to HAE medication. By using the PubMed API and NLTK, we can gain a better understanding of the frequency of HAE-related keywords in medical literature and identify potential areas for further research and intervention.

Data Sources
The availability of HAE medication is sourced from various official and unofficial databases.
The PubMed API is used to download data from medical journals that contain the keyword "hereditary angioedema".
Requirements
Python 3.6 or higher
Libraries: pandas, requests, xml.etree.ElementTree, nltk
Instructions
Run hae_medicine_availability.py to analyze the availability of HAE medication globally.
Run pubmed_data_download.py to download data from medical journals that contain the keyword "hereditary angioedema".
Run nltk_analysis.py to analyze the frequency of HAE-related keywords in the downloaded PubMed data.
Note: Please ensure that you have the required libraries installed before running the code.
