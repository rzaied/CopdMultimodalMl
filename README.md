# Integrating polygenic risk scores, quantitative CT metrics, and clinical risk factors for machine learning-based detection of chronic obstructive pulmonary disease

This repository contains scripts for the manuscript "Integrating polygenic risk scores, quantitative CT metrics, and clinical risk factors for machine learning-based detection of chronic obstructive pulmonary disease". In this study, we integrate polygenic risk, quantitative CT, and clinical risk factors into an ensemble model to test if it improves COPD prediction beyond single-modality models.

We performed machine learning on data from participants in the COPDGene cohort. Polygenic risk scores (PRSs) for lung function were derived from approximately two million imputed single-nucleotide polymorphisms (SNPs). Computed QCT metrics included Quadtree Decomposition (QtD), measuring tissue heterogeneity within low-density regions (emphysema), medium-density regions (normal-appearing lung tissue), and the lung as a whole. We built random forest sub-models using PRS, QCT features, and CRFs, and then constructed an ensemble model that integrated all predictors.

The ensemble model achieved an AUC of 0.85, surpassing the performance of the individual sub-models. 
