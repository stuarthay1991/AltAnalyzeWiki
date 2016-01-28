## Linear Regression Isoform Reciprocity Algorithm ##

When working with the same type of reciprocal junction data as ASPIRE, a linear regression based approach can be used to analyze reciprocal differences in junction expression. This method is based on previously described approach (1). This algorithm uses the same input ASPIRE (junction comparisons, constitutive adjusted expression ratios). To derive the slope for each of the two biological conditions (baseline and experimental), the constitutive corrected expression of all samples for both reciprocal junctions is plotted against each other to calculate a slope for each of the two biological groups using the least squared method. In each case, the slope is forced through the origin of the graph (model = y ~ x - 1 as opposed to y ~ x). The final linear regression score is the log2 ratio of the slope of the experimental group divided by the baseline group. This ratio is analogous to a fold change, where 1 is equivalent to a 2-fold change. When establishing cut-offs, select 2 to designate a minimum 2-fold change. The same permutation analysis used for ASPIRE is also available for this algorithm.

1. Sugnet CW, et al. (2006) Unusual intron conservation near tissue-regulated exons found by splicing microarrays. PLoS Comput Biol 2(1):e4.