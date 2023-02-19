This assignment aims to provide methods which can be used to solve class imbalance using various sampling techniques. Under-Sampling, Over-Sampling, SMOTE (Synthetic Minority Oversampling Technique) are also used. 

| Algorithm | Simple Random Sampling| Systematic sampling | Sratified Sampling | Cluster Sampling | Convenience Sampling |
|----------------| ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| Logistic Regression |  0.830311  | 0.841969  | 0.852332 | 0.839378  | 0.927461 | 
| SVC | 0.672280  | 0.739637  | 0.720207  | 0.683938  | 0.936508 | 
| KNN | 0.878238  | 0.696891  | 0.948187  | 0.901554  | 0.955959  | 
| Decision Tree | 0.957254	  | 0.867876  | 0.985751  | 0.984456  | 0.998705 | 
|Gaussian Naive Bayes| 0.801813  | 0.790155  | 0.718912  | 0.909326  | 0.910622 | 

- As can be seen in the above table, Decision Tree gives the best accuracy (0.998705) using convenience sampling. 