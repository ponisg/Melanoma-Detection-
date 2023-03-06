# Melanoma Detection using Neural Networks
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* General Info:The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

* Technologies Used: A CNN model is first used, which can accurately detect 9 classes present in the dataset. While building the model images have been rescaled to normalize pixel values between (0,1)
Next, an appropriate optimiser and loss function was chosen for model training and model was trained for 20 epochs.
Model performance is checked after initial fit. Model showed signs of overfitting. 
Proper data augmentation strategies were taken to address this issue. 
Model was trained again for 20 epochs.
Class imbalance was present. 
Class imbalance was addressed with augmentator which created 500 images for each classes. 
Model was trained again, this time for 50 epochs. 
Overfitting issue was solved but the overall accracy took a hit. 
Model is able to classify the 9 classes after final fit. 

## Contact
Created by ponisg - feel free to contact me!

