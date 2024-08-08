# MITx: Data Analysis: Statistical Modeling and Computation in Applications
A hands-on introduction to the interplay between statistics and computation for the analysis of real data. -- Part of the MITx MicroMasters program in Statistics and Data Science.

This repo contains my written analyses and projects for the final course in MITx's MicroMasters program. In general, the analyses takes for format of question and answer, with the answers including short response, deriving equations, numerical results, visulizations and the like. A majority of the questions require the use of Python for successful completion. Grades were primarily determined via a peer-review process and are stated below. Written analyses were performed in addition to auto-graded problems, which are not recorded here.

This course consisted of four modules that focused on a particular dataset for analysis:
<ol>
  <li>Module 1: Review: Statistics, Correlation, Regression, Gradient Descent (completed; 92.8%)</li>
  <li>Module 2: Genomics and High-Dimensional Data (completed; 100%)</li>
  <li>Module 3: Network Analysis (completed; not yet graded)</li>
  <li>Module 4: Time Series (completed; not yet graded)</li>
  <li>Module 5: Environmental Data and Gaussian Processes (module in-progress)</li>
</ol>

## Summary of Analyses
### Module 1: Review: Statistics, Correlation, Regression, Gradient Descent
This analysis included questions about experimental design, interpretation of p-values, and the post-study probability of published research findings finding true relationships via hypothesis testing.

### Module 2: Genomics and High-Dimensional Data
This analysis centered around analyzing a high-dimensional genomics dataset (20,000 dimensions). It included questions about dimension reduction techniques (e.g. PCA, T-SNE), visualizing data, clustering, logistic regression, and hyper parameter tuning.

### Module 3: Network Analysis
This analysis was mostly about analyzing a criminal network/graph (i.e. the CAVIAR network), but also included questions about citation networks. Further, we were given an open ended project of our choice which involved developing a socially motivated question and then answering the question with learned methodology from the course. My question was, "Using the Facebook ego network, are low degree nodes and high degree nodes assortative (i.e. low friend count people are friends with people who also have low friend counts and vice-versa) and how do they compare to one another?"

### Module 4: Time Series
In this written report, I analyzed two datasets; the first was the "Mauna Loa $CO_2$ Concentration" and the second analyzed inflation rates over the past decade using "consumer price index" and "break even rate" datasets. There were also two intermitent questions on finding the analytical autocovariances of an MA(1) then AR(1) model. The two datasets involved extracting trends and periodic components to make the data (weakly) stationary, then trying to model the time dependencies in the data via an AR/MA model. Each involved a cross-validation set to predict on and examine the RMSE. The second of the two problems involved regressing one time series upon another and trying to find hyperparameters in a SARIMAX model to minimize the 1 month-ahead prediction RMSE.

### Module 5: Environmental Data and Gaussian Processes
...
