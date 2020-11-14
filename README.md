# Factor-Analysis

Factor Analysis (FA) is an exploratory data analysis method used to search influential underlying factors or latent variables from a set of observed variables. It helps in data interpretations by reducing the number of variables. It extracts maximum common variance from all variables and puts them into a common score.

## Assumptions:
  There are no outliers in data.
  Sample size should be greater than the factor.
  There should not be perfect multicollinearity.
  There should not be homoscedasticity between the variables.

## Types of Factor Analysis
1. Exploratory Factor Analysis: Its basic assumption is that any observed variable is directly associated with any factor.
2. Confirmatory Factor Analysis (CFA): Its basic assumption is that each factor is associated with a particular set of observed variables. CFA confirms what is expected on the basic.

## Factor Analysis Process
The primary objective of factor analysis is to reduce the number of observed variables and find unobservable variables, This can be achived by:
1. Factor Extraction: the number of factors and approach for extraction selected using variance partitioning methods such as principal components analysis and common factor analysis.
2. Factor Rotation:  In this step, rotation tries to convert factors into uncorrelated factors — the main goal of this step to improve the overall interpretability.

## Eigenvalues:
- Eigenvalues represent variance explained each factor from the total variance. It is also known as characteristic roots.

## How to determine no of factors:
Kaiser criterion is an analytical approach, which is based on the more significant proportion of variance explained by factor will be selected. The eigenvalue is a good criterion for determining the number of factors. Generally, an eigenvalue greater than 1 will be considered as selection criteria for the feature.

## Factor Analysis Vs. Principle Component Analysis
  - PCA components explain the maximum amount of variance while factor analysis explains the covariance in data.
  - PCA components are fully orthogonal to each other whereas factor analysis does not require factors to be orthogonal.
  - PCA component is a linear combination of the observed variable while in FA, the observed variables are linear combinations of the unobserved variable or factor.
  - PCA components are uninterpretable. In FA, underlying factors are labelable and interpretable.
  - PCA is a kind of dimensionality reduction method whereas factor analysis is the latent variable method.
  - PCA is a type of factor analysis. PCA is observational whereas FA is a modeling technique.
 
Let's build the factor analysis model
