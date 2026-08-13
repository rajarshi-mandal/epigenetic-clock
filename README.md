# Interpretable epigenetic clock links aging pathways and disease-specific methylation profiles

Published in [npj Aging](https://www.nature.com/articles/s41514-026-00476-5), 13 August 2026. DOI: [10.1038/s41514-026-00476-5](https://doi.org/10.1038/s41514-026-00476-5)

We developed an interpretable blood-based epigenetic clock to estimate DNA methylation age and identify disease-specific DNA methylation alterations. Using 8233 Illumina methylomes from healthy controls and nine age-associated diseases, we used ridge selection to retain 4855 CpG sites and benchmarked 20 regression architectures with Bayesian hyperparameter optimization. Tree-based boosting models performed best, and a weighted ensemble achieved a mean absolute error of 2.54 years on held-out test data, outperforming established clocks evaluated under the same conditions. External validation in the independent EPIC cohort GSE132203 provided initial cross-platform support for transferability (MAE 3.04 years) and a modest but significant association with GEO-reported age acceleration (r = 0.145, p = 0.041). PaCMAP embeddings revealed structured aging trajectories and disease-enriched neighborhoods. Model interpretation highlighted loci including ELOVL2, FHL2, KLF14, CD8A, LAG3, SMAD2, and NSD1, while Enrichr identified enrichment of REST, microRNA, and histone modification programs. The clock identified departures from the healthy control methylation age model across diseases, with the greatest absolute deviation observed in stroke patients.

## Data

- [Selected CpG features](https://www.kaggle.com/datasets/rm1000/holistic-age-prediction-using-dna-methylation-data)
- [Source methylation data](https://www.kaggle.com/datasets/marquis03/age-assessment-and-disease-risk-prediction-h5)
- [External validation cohort GSE132203](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE132203)

## Citation

Mandal, R., Xie, N. & Alterovitz, G. Interpretable epigenetic clock links aging pathways and disease-specific methylation profiles. *npj Aging* (2026). https://doi.org/10.1038/s41514-026-00476-5

## License

Code is released under the [MIT License](LICENSE).
