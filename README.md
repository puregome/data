# Data 

Data related to the Chao et al. paper:

|----------------------------- | --------------------------------------------- |
| **File**                     | **Description**                               |
|----------------------------- | --------------------------------------------- |
| 20211207\_municipalities.csv | 88,564 tweet ids used for municipality counts |
| 20211207\_provinces.csv      | 96,864 tweet ids used for province counts     |
| 20211207\_readme.txt         | readme file with additional information       |
|----------------------------- | --------------------------------------------- |

All tweets used for municipality counts have also been used for province counts.
For an additional 8,300 tweets used for province counts, the municipality was unknown.

|----------------------------- | --------------------------------------------- |
| **File**                     | **Description**                               |
|----------------------------- | --------------------------------------------- |
| data-facemasks.csv           | annootated data for wearing facemask          |
| data-social-distancing.csv   | annootated data for social distancing         |
| data-testing.csv             | annootated data for testing                   |
| data-vaccination.csv         | annootated data for vaccination               |
|----------------------------- | --------------------------------------------- |

The annotated data files contain two columns: tweet id (td\_str) and label. There are 
three labels: EENS (agrees with the policy), ONEENS (rejects the policy) and ANDERS
(other). Tweets labelled ANDERS (other) have not been included in the final analysis.

