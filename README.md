# Weighted-p-value-combination
It is a weighted p-value combination approach that incorporates fold change directionality before applying Fisher's method for combining p-values.


From multiple differential expression (DE) results, the common proteins are extracted. The analysis then proceeds in two steps:
  1) Conversion to one-tailed p-values: The p-values are adjusted according to the direction of fold change (positive or negative) across the cohorts.
  2) Combining p-values using Fisher's method: After the directionality adjustment, Fisher's method is applied to aggregate the independent p-values into a single combined statistic.

The overall workflow is provided.
