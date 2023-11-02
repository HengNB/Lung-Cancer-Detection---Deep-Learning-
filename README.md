# Lung-Cancer-Detection---Deep-Learning-
Using Deep learning algorithm to detect Lung Nodules from chest CT scan image.

File Include:
FYP - Preprocessing
- FYP - Preprocessing.ipynb - Load the dataset , create mask for lung nodules (act as grond truth for Deep Learning models)
- FYP - PreprocessingPart2.ipynb - Crop the lung from CT scan images, Spliting dataset

FYP-DenseNet
- DenseNet-Train_test.ipynb - Train & test the DenseNet models 

FYP-U-Net
- U_net_train.ipynb - Train the U-net models
- U_net_test.ipynb - Test the U-net models
- HyperparameterTuning_for_Unet.ipynb - Perform hyperparameter tuning on U-net (Why only on U-net ? - the ressult of U-net models (Result_u-net_origin.png) is better than DenseNet model (Result_DenseNet.png))
- U_net_test_hyperparameter_tuning.ipynb - Test on U-net models (after HyperParameter Tuning)
