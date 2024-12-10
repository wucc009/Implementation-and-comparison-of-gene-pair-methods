# Implementation and comparison of gene pair methods
Code implementation of eight gene pair methods and performance comparison using the Pulmonary tuberculosis benchmark dataset

## 1、Code implementation of eight gene pair methods
### 1.1 Gene pair methods based on gene expression values
- [GERs](https://pubmed.ncbi.nlm.nih.gov/12208747) (R 4.2.3)
### 1.2 Gene pair methods based on gene ranking relationships
- [TSP](https://pubmed.ncbi.nlm.nih.gov/16646797) (Python 3.10.13)
- [k-TSP](https://pubmed.ncbi.nlm.nih.gov/16105897) (R 4.2.3)
- [TSPG](https://pubmed.ncbi.nlm.nih.gov/17663766) (R 4.2.3)
- [k-TSP+SVM](https://pubmed.ncbi.nlm.nih.gov/21939564) (Python 3.10.13)
- [REOs](https://pubmed.ncbi.nlm.nih.gov/25165092) (Python 3.10.13)
- [REOs+ML](https://pubmed.ncbi.nlm.nih.gov/32292778) (Python 3.10.13)
- TSP+ML (Python 3.10.13)
  
## 2、Performance comparison of eight gene pair methods using the Pulmonary tuberculosis benchmark dataset
### 2.1 Pulmonary tuberculosis benchmark dataset
|| GEO accession | Country | PTB[^1] | LTBI[^2] | HC[^3] |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Discovery data | [GSE19439](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE19439) | England | 13 | 17 | 12 |
|| [GSE19442](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE19442) | South Africa | 20 | 31 ||
|| [GSE19444](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE19444) | England |  21 | 21 | 12 |
| Validation data | [GSE83456](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE83456) | England | 45 || 61 |
[^1]: PTB: Pulmonary Tuberculosis.
[^2]: LTBI: Latent Tuberculosis Infection.
[^3]: HC: Healthy Control.
### 2.2 Performance comparison result
![Performance comparison result](https://github.com/wucc009/Implementation-and-comparison-of-gene-pair-methods/blob/main/image/Performance_comparison_result.png)

