# EDA-Analysis-KNNImputer
KNNImputer:
           A robust way to impute missing values is KNNImputer using Scikit-Learn. It is a widely used method to impute missing values. It is widely being observed as a replacement for traditional imputation techniques.
 Missing values in datasets can be imputed with the help of values of observations from the k-Nearest Neighbours in the dataset. Neighboring points for a dataset are identified by certain distance metrics, generally Euclidean distance.
The idea in kNN methods is to identify ‘k’ samples in the dataset that are similar or close in the space. Then we use these ‘k’ samples to estimate the value of the missing data points. Each sample’s missing values are imputed using the mean value of the ‘k’-neighbors found in the dataset.
