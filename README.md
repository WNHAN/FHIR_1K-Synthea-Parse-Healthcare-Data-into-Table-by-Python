# FHIR_1K-Synthea-Parse-Healthcare-Data-into-Table-by-Python

# Goals:

Synthea aims to create synthetic, realistic (but not real) patient data and health records for use in various non-clinical, secondary applications.

We will perform an exploratory data analysis (EDA) on a FHIR dataset,the fhir_1k dataset from Synthea,and several including key  steps, from downloading the data to parsing it into a structured format (like a table) and then performing the analysis using Python.

the following operations:
summarize the content of the dataset
explore one file, to understand the data structure
parse 1k FHIR json files into patient related tables
reformat the data, to transform it in dataframe format
generalize the transformations we performed for one file to all the files.
perform exploratory data analysis on the entire dataset
summarize our findings 

# ONE Patient may have many instances in the following tables:

Patient
Condition
Observation
Medication
Procedure
Encounter
Claim
Immunization

# Source:

https://synthea.mitre.org/downloads, (1K Sample Synthetic Patient Records,FHIR R4

https://synthetichealth.github.io/synthea-sample-data/downloads/synthea_sample_data_fhir_r4_sep2019.zip

Jason Walonoski, Mark Kramer, Joseph Nichols, Andre Quina, Chris Moesel, Dylan Hall, Carlton Duffett, Kudakwashe Dube, Thomas Gallagher, Scott McLachlan, Synthea: An approach, method, and software mechanism for generating synthetic patients and the synthetic electronic health care record, Journal of the American Medical Informatics Association, Volume 25, Issue 3, March 2018, Pages 230–238, https://doi.org/10.1093/jamia/ocx079



