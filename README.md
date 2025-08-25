# Endocrine-Disruptors-CHD
 Exploring associations of endocrine disruptors and coronary heart disease using machine learning.

## Overview
This project's aim is to discover the links between endocrine disruptor exposure and coronary heart disease. Coronary heart disease is the most common form of heart disease according to the CDC. Links between endocrine disruptors and other cardiovascular diseases or factors such as diabetes, obesity, and blood pressure are relatively established. Therefore, we aim to further research in this field by monitoring possible direct connections between EDCs and coronary heart disease. To do so shallow supervised and unsupervised machine learning pipelines are used.

## Data Source
We will use NHANES data (2013-2018) from the CDC. This includes demographics and laboratory datasets. The data will not be included in this repository; however, the data is publicly available here: (https://wwwn.cdc.gov/nchs/nhanes/Default.aspx)

Users should download the **Demographics, Questionnaire, and Laboratory datasets** for the relevant cycles.  
> Processed datasets used in this analysis are included in the notebooks as examples.

## Repository Structure 
- `Notebooks/` — Jupyter/Colab notebooks for analysis and modeling
- `requirements.txt` — Python dependencies
- `README.md` — Project overview (this file)
- `LICENSE` — License information

## Methods  
- **Clustering (K-Means):** Identified participant subgroups with differing CHD prevalence
- **Principal Component Analysis (PCA):** Reduced dimensionality and identified top factors driving cluster separation
- **Classification Models:** Evaluated predictive performance for CHD classification

## Results
- Clustering revealed distinct subgroups with different CHD prevalence and varying endocrine disruptor chemicals in bloodstream and urine.  
- Endocrine disruptors were major contributors to the principal components driving cluster separation.  
- Classification models showed moderate predictive performance: high recall and precision for the majority class but lower, yet still decent, recall for CHD cases.
- Permutation importance revealed EDC biomarkers to be highly valuable in model prediction

## Next steps
- Repeated studies on more structured data with a less class imbalance ideally
- Use of other machine learning methods

## Role 
In my team specifically, I operated as the team lead and main programmer. 
