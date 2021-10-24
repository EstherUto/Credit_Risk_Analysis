# Credit Risk Analysis

## Table of Contents

- [Overview of Analysis](#overview-of-analysis)
- [Results](#results)
  * [Oversampling Algorithms](#oversampling-algorithms)
  * [Undersampling Algorithms](#undersampling-algorithms)
  * [Combined Sampling Algorithm](#combined-sampling-algorithm)
  * [Ensemble Learners](#ensemble-learners)
- [Summary](#summary)

## Overview of Analysis

The purpose of this analysis is to identify good candidates for credit loans to reduce risk by using machine learning to accurately identify high risk candidates. The plan is to use various forms of supervised machine learning algorithms to determine which machine learning model will best achieve the goal.

## Results

From the data file, the loan status column was chosen to be the optimal target for the goal of the project. There were about 68,470 identified low risk candidates and 347 high risk candidates.

### Oversampling Algorithms

The imbalanced classification report for both the Naive Random Oversampling algorithm and the SMOTE Oversampling algorithm is provided in figures 1 and 2 respectively.

**_FIGURE 1. Naive Random Oversampling Classification Report_**

<img width="505" alt="Fig_1_Naive_Random_Oversampling" src="https://user-images.githubusercontent.com/86085601/138612574-6e612e53-a6f5-4269-aafc-fcc56b596832.png">

**_FIGURE 2. SMOTE Oversampling Classification Report_**

<img width="505" alt="Fig_2_SMOTE" src="https://user-images.githubusercontent.com/86085601/138612575-ce6fd8a6-e1bb-453d-9611-9b748526deac.png">

### Undersampling Algorithms

The imbalanced classification report for the Cluster Centroids undersampling algortithm is provided in figure 3

**_FIGURE 3. Cluster Centroids Undersampling Classification Report_**

<img width="505" alt="Fig_3_Cluster_Centroids" src="https://user-images.githubusercontent.com/86085601/138612576-564e1289-4ee0-49f0-8933-2309e31882f8.png">

### Combined Sampling Algorithm

The imbalanced classification report for the SMOTEENN sampling algorithm is provided in figure 4

**_FIGURE 4. SMOTEENN Sampling Classification Report_**

<img width="505" alt="Fig_4_SMOTEENN" src="https://user-images.githubusercontent.com/86085601/138612577-5cafab75-80e5-4ca0-b35e-8e22c8fef066.png">

### Ensemble Learners

The imbalanced classification report for the Balanced Random Forest Classifier and the Easy Ensemble Classifier algorithms is provided in figures 5 and 6 respectively.

**_FIGURE 5. Balanced Random Forest Classifier Classification Report_**

<img width="505" alt="Fig_5_Balanced_Random_Forest_Classifier" src="https://user-images.githubusercontent.com/86085601/138612578-b283c0ad-39b0-4821-81cd-f3b222b85ba6.png">

**_FIGURE 6. Easy Ensemble Classifier Classification Report_**

<img width="505" alt="Fig_6_Easy_Ensemble_Classifier" src="https://user-images.githubusercontent.com/86085601/138612579-8f6d6b77-9e4a-4880-8662-a3e73f9a5837.png">

## Summary


