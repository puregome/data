# Data 

Data related to the Chao et al. paper:

| **File**                     | **Description**                               |
|----------------------------- | --------------------------------------------- |
| 20211207\_municipalities.csv | ids and predicted labels for 88,564 tweets used for municipality counts |
| 20211207\_provinces.csv      | ids and predicted labels for 96,864 tweets used for province counts     |
| 20211207\_readme.txt         | readme file with additional information       |

These files are used by the notebook [social-distancing-aggregate.ipynb](https://github.com/puregome/notebooks/blob/master/social-distancing-aggregate.ipynb).
All tweets used for municipality counts have also been used for province counts.
For an additional 8,300 tweets used for province counts, the municipality was unknown.

| **File**                     | **Description**                               |
|----------------------------- | --------------------------------------------- |
| data-facemasks.csv           | annotated data for wearing facemasks         |
| data-social-distancing.csv   | annotated data for social distancing         |
| data-testing.csv             | annotated data for testing                   |
| data-vaccination.csv         | annotated data for vaccination               |

These files are summaries of the files used by the notebook [ieee.ipynb](https://github.com/puregome/notebooks/blob/master/ieee.ipynb) and others.
The annotated data files contain two columns: tweet id (td\_str) and label. There are 
three labels: EENS (supports the policy), ONEENS (rejects the policy) and ANDERS
(irrelevant). Tweets labelled ANDERS (irrelevant) have not been included in the final analysis.

