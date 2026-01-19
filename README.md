# End-to-end-NLP-and-data-analytics-projects-focused-on-reproducible-ML-pipelines-and-benchmarking

=
## Overview
This repository showcases an end-to-end machine learning pipeline for benchmarking multiple NLP models on large-scale user-generated text data. 
The project emphasizes reproducibility, model evaluation under class imbalance, and multi-layer validation using both supervised learning and lexicon-based analysis.

## System Architecture
Gzipped Dataset  
→ Sampling & Reproducibility Control  
→ Text Cleaning & Label Engineering  
→ TF-IDF Vectorization  
→ Model Training (SVM, Random Forest, Naive Bayes)  
→ Performance Benchmarking (Accuracy, Balanced Accuracy, Sensitivity, Specificity, Kappa)  
→ Lexicon-Based Validation (Hu & Liu)  
→ Reporting & Visualization  

## Tech Stack
- R, RMarkdown  
- jsonlite, tidyverse, tm, caret  
- e1071, naivebayes, randomForest, nnet, irlba  

## How to Run
1. Install required packages from `requirements.txt`
2. Open `src/grouppro.Rmd` in RStudio
3. Run all cells to reproduce the pipeline and results

## Results Summary
- SVM and Random Forest achieved >80% accuracy on TF-IDF features
- Balanced accuracy and sensitivity analysis revealed the impact of class imbalance
- Lexicon-based validation aligned with supervised model predictions

## Next Steps
- Containerize the pipeline with Docker
- Add CI for automated benchmarking
- Extend to conversational AI or healthcare feedback datasets
