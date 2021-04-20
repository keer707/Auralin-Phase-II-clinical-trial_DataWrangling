# Auralin Phase II clinical trial - DataWrangling

The Auralin Phase II clinical trial dataset comes in three tables: `patients`, `treatments`, and `adverse_reactions`. 

This project focuses on **data wrangling** in order to compare the efficacy and safety of a new oral insulin to treat diabetes to injectable insulin. 

> **DISCLAIMER: This Data Isn't "Real"**
The Auralin and Novodra are not real insulin products. This clinical trial data was fabricated for the sake of this project. When assessing this data, the issues that you'll detect (and later clean) are meant to simulate real-world data quality and tidiness issues.

> That said:
> - This dataset was constructed with the consultation of real doctors to ensure plausibility by Udacity.
> - This clinical trial data for an alternative insulin was inspired and closely mimics this real [clinical trial for a new inhaled insulin called Afrezza](https://care.diabetesjournals.org/content/38/12/2266.long).
> - The data quality issues in this dataset mimic real, [common data quality issues in healthcare data](http://media.hypersites.com/clients/1446/filemanager/Articles/DocCenter_Problem_with_data.pdf). These issues impact quality of care, patient registration, and revenue.
> - The patients in this dataset were created using this [fake name generator](https://www.fakenamegenerator.com/order.php) and do not include real names, addresses, phone numbers, emails, etc.


## Required packages
- Pandas
- Numpy
- Matplotlib

## DataWrangling

## Gather
Data is readily available for assessing 

## Assess
Assess data for:
- Quality: inconsistent data, inaccurate data, non-descriptive headers, missing values (NAN)
- Tidiness: issues with structure that prevent easy analysis. Tidy data requirements: Each variable forms a column. Each observation forms a row. Each type of observational unit forms a table.

Types of assessment:
- Visual assessment
- Programmatic assessment (used Pandas)

## Clean
Programmatic data cleaning process:
- Define: convert the assessments into defined cleaning tasks.
- Code: convert those definitions to code and run that code.
- Test: test your dataset, visually or with code, to make sure cleaning operations worked.