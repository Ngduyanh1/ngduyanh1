# Data science portfolio by Nguyen Duy Anh
This repo is a compilation of notebooks that I have done on data analysis and machine learning.

## Classification
### Taobao's click-through-rate prediction
A common problem in online advertising field. I used logistic regression, XGBoost, decision tree and MLP in this project to predict a probability that each user will click on an advertisement. In summary, the XGBoost yields the best result with an AUC of 0.64 and log-loss of 0.19. [Link to notebook](https://github.com/Ngduyanh1/ngduyanh1/blob/main/taobao_ctr_pred.ipynb)

### Telecom churn prediction
In this notebook, I compared the performance (AUC, log-loss) between logistic regression and cross-validated KNN models in predicting if a user will churn and performed grid-search to find cost-optimal threshold for final predictions. In summary, KNN yields the best result with an AUC of 0.61 and log-loss of 0.31. [Link to notebook](https://github.com/Ngduyanh1/ngduyanh1/blob/main/telecom_churn_prediction.ipynb)

## Principal component analysis and clustering
### Reducing dimension for plotting and clustering countries' indicators
Performing PCA on countries' indicators dataset, then plotting data over the first two component space. K-mean clustering for grouping countries. [Link to notebook](https://github.com/Ngduyanh1/ngduyanh1/blob/main/countries_pca_cluster.ipynb)
