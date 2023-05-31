# A/B Testing
This is a project in which we aim to conduct A/B testing on data that includes users categorized into Control and Variant groups, along with information on the generated revenue. The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/sergylog/ab-test-data?datasetId=2479030&sortBy=voteCount)

The objective is to use appropriate tests for each case, whether it is for mean differences or proportions, even if the data does not strictly meet the assumptions of some tests. This allows us to compare the results and determine when these tests can still be effective despite such conditions.

The tests used in this project were:

- Permutation test
- T-test
- Mann-Whitney U rank test
- Z-test
- Chi-Square
- Fisher's Exact Test
