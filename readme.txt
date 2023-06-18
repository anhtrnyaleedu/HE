HE prediction
This tutorial shows how to construct a testing workflow of HE prediction task.

Data: ATACH-2 + Yale
Train data: Trained 507 patients (HE=83) and validated 127 patients (HE=21).
Test data: 159 patients
AUC = 0.79
And it contains below features:

CT input with thick thickness
Pre-processing: extract brain window, skull stripping, remove boundary, resample
Segmentation and Prediction: 3D SegResNet model, DenseNet.