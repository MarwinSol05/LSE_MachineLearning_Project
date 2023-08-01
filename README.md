# LSE_MachineLearning_Project

## Task 1 : Gene Cell Classification
The first part of the project is to apply statistical machine learning techniques on a real world dataset of RNA expression levels measurements of p = 4123 genes in n = 5471 cells. The .csv file has 5471 rows (excluding the header row) and 4124 columns. Each row represents one cell. The first column gives the cell type of the cell (TREG or CD4+T) and each of the remaining columns records the logarithmic normalised RNA expression level of a particular gene (gene name given in the column heading).

### Result: In terms of accuracy of predictions, we get the best outcome by aggregating the result (stacking) from all different models employed. Hence, we can claim that aggregation (stacking) produces the best result for the classification problem at hand. While in terms of stand-alone models, Linear Discriminant Analysis performs the best as per the accuracy standard.

## Task 2 : Graphical Models Estimation
The task of this project is to identify the conditional dependence structure among a fixed number of random variables. It helps in determining the existence of relations among the random variables involved in analysis.

### Result: When number of features and sparsity remain unchanged with the increase in number of observations, the graphical model performs better, but the model is not very sensitive to number of observations. Overall, Graphical Lasso performs the best, and Node-wise Lasso 1 performs the worst.
