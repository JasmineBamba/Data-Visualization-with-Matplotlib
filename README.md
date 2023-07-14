# Data-Visualization-with-Matplotlib

## Mouse Study Analysis
This project involved the analysis of a mouse study dataset to investigate the effects of different drug regimens on tumor growth in mice. The analysis was performed using Python and various data analysis libraries such as Pandas, Matplotlib, and SciPy.

## Dataset
The dataset used in this project consists of two CSV files: Mouse_metadata.csv and Study_results.csv.

## Requirements
To run the code in the Jupyter Notebook, the following libraries are required:

- pandas
- matplotlib
- scipy
- numpy

## Analysis
- The data provides information on different drug regimens and their effects on tumor volume in mice. By comparing the mean, median, variance, standard deviation, and standard error of each drug regimen, we can observe differences in their efficacy. For example, Capomulin and Ramicane have lower mean and median tumor volumes compared to other drugs like Ketapril, Naftisol, and Placebo. This suggests that Capomulin and Ramicane might be more effective in reducing tumor size.

- The data includes information about potential outliers in tumor volume for each drug regimen. By identifying potential outliers, we can understand the variability in response to treatment. For instance, Infubinol has one potential outlier with a tumor volume of 36.321346. This finding suggests that Infubinol may not consistently reduce tumor volume as expected.

- The data includes individual measurements for mice, such as their ID, timepoint, tumor volume, metastatic sites, drug regimen, sex, age, and weight. This allows for more detailed analysis at the mouse level. Researchers can analyze specific mice and their response to different drug regimens. For example, mouse a411 treated with Ramicane showed a significant reduction in tumor volume (38.407618), indicating the potential effectiveness of Ramicane in that particular case.
