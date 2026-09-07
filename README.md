# Hello

## Note
This repo was forked from Martell0x1 original repo of the same name on September 7th 2026. 
This version will not be pushing any changes to the original repo and is meant as it's own standalone version. 
The reason for this, is because I am currently relearning basic ML concepts and learning Rust and memory management so as a result the first iterations may be insecure 

## Current Picture of this repo 

This repo currently contains the vector and martix code (versions from Martell0x1 repo from when it was forked). This will be expanded upon and other concepts will be added, as shown below. 

# The Idea behind this repo 

- the picture
```md
                    rust-ml
                       │
        ┌──────────────┴──────────────┐
        │                             │
   Mathematics                   Data system
        │                             │
 Linear Algebra                 Dataset
 Probability                   CSV
 Statistics                    Train/test split
 Optimization                 Normalization
        │                             │
        └──────────────┬──────────────┘
                       │
                Classical ML
                       │
        ┌──────────────┼──────────────┐
        │              │              │
   Regression      Classification   Clustering
        │              │              │
     Linear          Logistic         K-Means
     Ridge           KNN              DBSCAN
     Lasso           Naive Bayes      GMM
     Polynomial      Decision Tree
                    Random Forest
                    SVM
                       │
                       ▼
                Model Evaluation
                       │
          ┌────────────┼────────────┐
          │            │            │
        Metrics      CV            Tuning
          │            │            │
       Accuracy     K-Fold        Grid Search
       Precision    Stratified    Random Search
       Recall
       F1
       ROC-AUC
                       │
                       ▼
                 Neural Networks
                 (later)


 
