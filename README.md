# Skin-cancer-ISIC-The-International-Skin-Cancer-Imaging-Collaboration.

**Problem statement: **

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

**Data Reading/Data Understanding**

Defined the path for both train and test images from dataset.

**Dataset creation**

Created train & validation dataset from the train directory with a batch size of 32 .
Resized images to 180*180.(10%)

**Dataset visualisation**

Created a code to visualize one instance of all the nine classes present in the dataset 

**Model Building & training**

Created a CNN model, which can accurately detect 9 classes present in the dataset.
Defined appropriate optimiser and loss function for model training.
Trained the model for ~20 epochs.
Explained the findings after the model fit with evidence if the model overfits or underfits.

**Data augmentation**

Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 

**Class distribution**

Examined the current class distribution in the training dataset & explained the following:
Which class has the least number of samples?
Which classes dominate the data in terms of the proportionate number of samples?

**Handling class imbalances**

Rectified class imbalances present in the training dataset with Augmentor library

**Model Building & training**

Created a CNN model, which can accurately detect 9 classes present in the dataset.
Defined appropriate optimiser and loss function for model training.
Trained the model for ~20 epochs.
Explained the findings after the model fit with evidence if the issues are resolved or not.

**Coding Guidelines**

Appropriate comments are written wherever applicable.
If new variables are created, the names are descriptive and unambiguous.
The code is written concisely wherever possible.
The GitHub repository link contains a python file, and a README.md file. README.md file should describe the project briefly.
Assumptions are made, they are stated clearly.
