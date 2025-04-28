# Building-Neural-Network-Using-only-Numpy

Introduction:
The dataset contains 278848 rows and 11 columns including the target feature('Corona').

It has 9 categorical features, 1 datetime feature classified as categorical feature and 1 numerical feature.

It is an unbalanced dataset(5% Minority, 95% Majority).


The following list describes each of the dataset's features used by the model:

A. Basic information:

ID (Individual ID)

Sex (male/female).

Age ≥60 above years (true/false)

Test date (date when tested for COVID)

B. Symptoms:

Cough (true/false).

Fever (true/false).

Sore throat (true/false).

Shortness of breath (true/false).

Headache (true/false).

C. Other information:

Known contact with an individual confirmed to have COVID-19 (true/false).
D. Covid report

Corona positive or negative


Challenges and solutions approaches while using this dataset:
The dataset is unbalanced and it will create a bias model if an algorithm is trained using this raw dataset.

APPROACHES: 
-Feature selection is done before handling the unbalanced data.

-The unbalanced dataset is handled using imbalanced-learn library.

-Since the dataset is very large, there is sufficient records to perform undersampling technique is used.

Techniques and tools used in building the model:
Numpy library
