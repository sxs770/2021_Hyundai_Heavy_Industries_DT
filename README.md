# 2021 Hyundai Heavy Industries DT

## Abstract
This problem is to use logistic regression to detect system-specific anomalies and automatically propose maintenance alarms. Furthermore, the goal is to build an engine alarm system by integrating maintenance alarms for each system.

In the data preprocessing step, the original data were sorted in chronological order, duplicate values were processed, and data with negative values were converted to zero and processed. In addition, the standardization and normalization of the data were performed. Afterwards, Phi correlation coefficients were used to determine the correlation for each variable, and for data with large correlations, principal component analysis (PCA) was conducted to perform dimensional reduction.

After the evaluation, the importance of each feature was identified using SHAP (Shapley Additive exPlanation). SHAP is a way of explaining how much each feature affects the prediction of the model, which allows us to determine the contribution of each feature.

This approach automates maintenance alarms and integrates detected anomalies per system to build an engine alarm system.

## Contributors

### Members
`Junhyeok Choi`|`Yeonsung Jeon`|`Yeonkyung Son`|`Gayeon Choi`|`Songyi Lee`

### Advisor
`Sudong Lee`

### Contribution
`Junhyeok Choi` &nbsp;: Data preprocessing     
`Yeonsung Jeon` &nbsp;: Data preprocessing     
`Yeonkyung Son` &nbsp;: Data preprocessing, modeling     
`Gayeon Choi` 　  &nbsp;: Data preprocessing, modeling     
`Songyi Lee` 　   &nbsp;&nbsp;&nbsp;: PM, Data preprocessing
## Tools
- Anaconda
- Python 3.8
- Numpy
- Pandas
- Scikit - learn
- Matplotlib
- Seaborn
- Shap
