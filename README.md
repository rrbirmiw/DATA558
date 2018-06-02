# A Multiclass & Binary Linear Support Vector Machine Implementation 

`linearsvm.py` contains two classes, `LinearSVM` for binary classification; `Weighted_Multiclass_SVM` for multiclassification problems. The latter uses the weighted-one-v-rest approach (see docstrings/documentation for references)
## Getting Started
On a Mac terminal / appropriate Windows UNIX shell: 

` >>> python3 demo.py ` compares this multiclass linear SVM with the scikit-learn analog -- `sklearn.svm.LinearSVC` on the famous _iris_ dataset, with the same hyperparameters for both classifiers. 

### Prerequisites

Requires `numpy` and `scikit-learn`
### Installing
If necessary, install the aforementioned libraries: i.e.

`pip install sklearn 
 pip install numpy 
`

## Authors

* **Rahul Birmiwal** 
As part of Statistical Machine Learning For Data Scientists at the University of Washington, under Professor Zaid Harchaoui and Assistant Corinne Jones, 2018

## Acknowledgments

* Papers of reference listed in the module documentation

