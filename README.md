# Melanoma_Dissertation
Melanoma Skin Cancer Prediction using CNN-based architectures
A thesis submitted for the degree of Master of Data Science and its Applications.

In my project, I aimed to build CNN-based architecture models that can recognize melanoma skin cancer from a bunch of pictures. I got this huge dataset, about 25,331 pictures, from Kaggle. It's originally from ISIC (International Skin Imaging Collaboration), but I found it more convenient on Kaggle, so that's where I got it.

The dataset comes with two CSV files: ISIC_2019_Training_GroundTruth.csv and ISIC_2019_Training_Metadata.csv. The first CSV spills the beans on 10 skin diseases for each image, but I'm mainly interested in the "MEL" column. If it's a 1, it means melanoma; if it's a 0, it's something else.

The second CSV, the Metadata one, gives some extra details about the patients (whose skin images are used), like age, sex, where the skin issue is, and the patient's lesion ID.

My objective is to develop robust predictive models that can accurately identify melanoma skin cancer lesions, and after that comparing their results, which will help to observe the model which standout. By this we are contributing to early and effective detection for improved patient outcomes.
