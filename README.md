# DESI_Private
This is a place to dump files, to see the work in progress.<br />
Here I tried different matrics for the keras model that classifies SN and Hosts.<br />
The SN used here are all brighter than 50%. <br />
The combination of metrics tried is as follows:<br />
  (1) Accuracy<br />
  (2) Accuracy + AUC(PR curve)<br />
  (3) Precision + AUC (PR Curve)<br />
  (4) Accuracy + AUC(PR curve) + Precision<br />
You can look at the performace of these networks using the CM, PR, and ROC curve.<br />
There are two ways I have tested the epoch vs acc/auc/precision. One is by diving into test and train data; the other is taking a random 0.25 fraction of the x, y data and using it for training and testing. <br />
