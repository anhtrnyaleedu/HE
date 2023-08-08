HE prediction
This tutorial shows how to construct a testing workflow of HE prediction task.

Data: ATACH-2 + Yale
Train data: Trained 634 patients.
Test data: 159 patients
AUC = 0.81 with MC

CT input with thick thickness
Pre-processing: extract brain window, skull stripping, remove boundary, resample
Segmentation and Prediction: 3D SegResNet model, DenseNet.