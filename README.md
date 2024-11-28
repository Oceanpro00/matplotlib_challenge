# matplotlib_challenge
Data Analytics Bootcamp - Module 5 - Matplotlib Visualization Challenge


Overview :
- This project explores data from a Pymaceuticals, Inc. study that tests the effectiveness of various drug regimens for treating squamous cell carcinoma (SCC), a common form of skin cancer. The dataset includes 1,893 observations from 249 mice treated over 45 days, focusing on tumor size, metastatic sites, and other key metrics. The goal of the analysis is to generate figures and insights for a technical report, comparing Pymaceuticals' promising drug, Capomulin, against other treatment regimens.


Key Insights:

- Capomulin and Ramicane were the most effective treatments, showing the lowest average tumor volumes (~40mm³) and the smallest variability in outcomes.
- A positive correlation between mouse weight and tumor size was observed for Capomulin, highlighting the need for controls or normalization when analyzing data.
- Infubinol and Ceftamin, while less effective, provided interesting insights due to their higher variability and presence of outliers.


Features - This repository includes a complete analysis pipeline for:

	Data Preparation:

	- Merging datasets on mouse metadata and study results.
	- Cleaning duplicate records to ensure accurate analysis.
	- Verifying the number of unique mice after cleaning.
	
	Summary Statistics:

	- Calculating mean, median, variance, standard deviation, and SEM for tumor volumes across drug regimens.

	Visualizations:

	- Bar charts comparing the number of timepoints for each regimen.
	- Pie charts showing the gender distribution of mice.
	- Box plots displaying tumor volume distributions for selected regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).
	- Line plots of tumor progression for individual mice.
	- Scatter plots of mouse weight vs. tumor volume, including linear regression analysis.

	Advanced Analytics:

	- Quartile calculations to identify outliers.
	- Correlation and linear regression analysis for tumor volume and mouse weight.


Repository Contents:

- mouse_metadata.csv: Metadata on mice, including sex, weight, and age.
- study_results.csv: Tumor volume and metastatic site observations for each treatment.
- analysis.ipynb: Jupyter Notebook containing the full analysis, including data cleaning, visualization, and statistical summaries.
- README.md: This file, describing the project.


Dependencies:

- Python 3.7+
- Pandas
- Matplotlib
- NumPy
- SciPy
