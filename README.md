# code structure
Our code is mainly divided into two parts, the first part is from the existing emotic data set, through further annotations we need, and extract the features in the picture and import to csv, the code of this part is in final_project_feature_extraction.ipynb file, you may run this part of the code for a long time due to the large dataset. 
Hence, we divided the code into two parts, you can run the final_project.ipynb file directly from the csv file in the data file, this is the data we annotated, there are around 500 pictures annotated.


The tasks we have accomplished are basically the same as those in our proposal. We use methods such as PCA, K-MEANS, SVM, and GMM. The difference is that in the code, we compare the performance of other classification models and adjust the parameters.

The last thing is the python library.
Besides basic sklearn, numpy, pandas, matplotlib, seaborn.

You may also need xgboost and LightGBM and imblearn.

But we don't think this will affect the running of the code. These extra libraries are only used when tuning model parameters.

imblearn is used to balance the data set, but it does not affect the running of the code.


The command below:

```python
pip install xgboost

pip install lightgbm

pip install imblearn
```
