# PSM-EA

## A phenotype-specific framework for identifying the eye abnormalities causative nonsynonymous-variants

Here we presented a phenotype-specific framework aimed to directly point out the phenotypic significance of predicted candidates, and showed its advancing performance in eye abnormalities. By training on eye-abnormalities causative variants, our method presented 96.2% accuracy, 96.1% precision, 93.4% recall for pathogenicity identification. Inconsistent with the modeling performance, identifying the single phenotype-causative variant from various sequencing variants is challenging for all predictors. Underlying the phenotype-oriented, our method significantly promoted the precision and reduced the cost for identifying the single causative variant from thousands of candidates. These advances highlight the significance of the phenotype-specific training method for studying disease.


## Downloads

PSM-EA scores are feely available for non-commercial use.

In order to facilitate utilization by researchers and clinicians, precomputed PSM-EA scores for all nsSNVs in the human genome (hg19) are available for download ([`PSM-EA.gz`](https://github.com/danria/PSM-EA/blob/master/PSM-EA.gz)).

A file in Tab-separated values file format contains 9 fields:

1. Gene: Gene symbol
2. CHR: Chromosome
3. POS: Sequence position on the hg19 (GRCh37) human genome
4. ID: rs number from dbSNP
5. REF: Reference sequence 
6. ALT: Alternative sequence
7. Damaging_value: Predicted as damaging score
8. Tolerated_value: Predicted as tolerated score
9. Predict: Predicted result of PSM-EA

## Contact

For support or questions, please contact:

- Xiao Dang (dangxiao@genomics.cn)
- Hankui Liu (liuhankui@genomics.cn)
- Jianguo Zhang (zhangjg@genomics.cn)
