# proportions-test-power-analysis-notebook

Plot how many PSMs you must observe in group2 with a given feature to achieve statistical
significance using the two-tailed test of proportions, given:

- the total number of PSMs in group1 and group2
- the statistical significance desired (alpha)
- (optional) the number of tests to correct for using Bonferroni correction

For each point, x1 (the number of PSMs with that feature in group1), plots both the number
of PSMs above and below x1 you need to observe in group2 to achieve statistical significance.