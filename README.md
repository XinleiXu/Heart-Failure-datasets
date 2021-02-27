# Heart-Failure-datasets
Heart Failure datasets

The classification target is binary, using the label from the set {Death, Survival}. 

In this task, the number of Death cases is obviously less than that of Survival ones. 

Hence, the Death cases are regarded as the positive ones, while the other cases are negative, implying that it is a typical imbalanced problem.

Each entry (row) is a record from one patient, while the columns present various clinical features for patients. In detail, the first three of the features are numeric and the rest are nominal. To transform the original data, the three numeric features are normalized at first, and then the dummy encoding is utilized for the rest ones. By doing so, the data matrix preserves 1302 columns, whose detailed meanings are described as follows: The 1st, 2nd, and 3rd column is The 1st, 2nd, and 3rd column is the value of Age, Gender, and Heart ratio of the patient, respectively. Then, the Diagnoses are recorded from the 4th to 1225th columns. The next 10 columns present the Medications taken by the patient, while the last 66 columns show the Laboratory tests for the patient.

HA includes the all data

MA includes the data with one month

YA includes the data with one year
