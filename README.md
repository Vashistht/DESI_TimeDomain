# DESI_Private
This is a place to dump files, to see the work in progress.
Here I tried different matrics for the keras model that classifies SN and Hosts.
The SN used here are all brighter than 50%. 
The combination of metrics tried is as follows:
  (1) Accuracy
  (2) Accuracy + AUC(PR curve)
  (3) Precision + AUC (PR Curve)
  (4) Accuracy + AUC(PR curve) + Precision
You can look at the performace of these networks using the CM, PR, and ROC curve.
There are two ways I have tested the epoch vs acc/auc/precision. One is by diving into test and train data; the other is taking a random 0.25 fraction of the x, y data and using it for training and testing. 
