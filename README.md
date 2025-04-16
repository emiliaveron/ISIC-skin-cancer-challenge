# ISIC-skin-cancer-challenge
Training of a YOLOv11 classification model to predict whether the given skin lesions are malignant or benign. 
Other than YOLOv11, there is the ResNet152 and a custom CNN; however, of course, YOLO yielded much better results, with an F1 Score of 88%.
The data for this project was taken from the ISIC Archive and preprocessed with the methods used in `preprocessing.ipynb`. 
More preprocessing and finally training can be found in the `Ham10000_Skin_cancer_ISIC.ipynb` notebook.
