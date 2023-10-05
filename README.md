# Appointment Dataset Analysis

## Introduction
This data analysis project focuses on examining the 'noshowappointments-kagglev2-may-2016.csv' dataset, which contains information about patients and whether or not they attended their scheduled appointments.

## Questions
The project aims to answer several key questions:
1. How many females and males are represented in the dataset?
2. What is the attendance percentage for males and females?
3. How many females received SMS reminders and attended appointments compared to those who did not receive SMS but still attended?
4. What is the percentage of females with diabetes?
5. Are there female children with diabetes, and if so, how many?
6. How many individuals with diabetes and alcoholism attended their appointments, and how many missed them?

## Data Wrangling
The initial phase of the analysis involves data wrangling tasks to prepare the dataset for examination. This includes:
- Loading the dataset
- Validating data types
- Identifying missing or null values
- Eliminating duplicate entries
- Cleaning and transforming the data as necessary


To conduct this analysis, we've utilized the following Python packages:

- [Pandas](https://pandas.pydata.org/): A powerful data manipulation library for working with structured data.
- [Matplotlib](https://matplotlib.org/): A popular data visualization library for creating a wide range of plots and charts.
- [NumPy](https://numpy.org/): A fundamental package for scientific computing with support for arrays and matrices.


Here's how these packages are imported in the Python code:

```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
```


## Conclusion

The analysis has yielded the following key findings:

- There are 70,118 females and 36,869 males in the dataset, indicating a significant gender imbalance, with more females than males.
- Approximately 52% of females showed up for their appointments, while only around 28% of males attended.
- Overall, approximately 80% of both males and females showed up for their appointments, with 20% being no-shows.
- Among those who didn't show up, about 7% were males, while 13% were females.
- Approximately 8% of females in the dataset have diabetes, with the majority being non-diabetic adults. Only 38 female children were found to be diabetic.
- Among the females, 92% are not diabetic, representing the majority, while 8% are diabetic. This includes 38 female children and 5,568 female adults.

These findings provide valuable insights into appointment attendance and diabetes prevalence within the dataset. It's essential to consider these results as a starting point for further analysis and research.


For any questions or suggestions, please contact Som Patrick at [somsompatrick17@gmail.com](mailto:somsompatrick17@gmail.com).
