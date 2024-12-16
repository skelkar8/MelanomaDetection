# Project Name
> Melanoma Detection


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Melanoma Detection is a machine learning project aimed at building a CNN to accurately detect melanoma, a potentially deadly type of skin cancer. Melanoma accounts for 75% of skin cancer deaths, and early detection is critical to improving survival rates. This solution seeks to evaluate skin images and alert dermatologists to the presence of melanoma, thereby reducing the manual effort involved in diagnosis

## Background
- This project is part of a larger initiative to leverage machine learning for medical applications, specifically for oncological diseases. The ability to detect various skin conditions accurately can improve diagnostic workflows and patient outcomes.

## Dataset
- The dataset used for this project consists of 2,357 images of malignant and benign oncological diseases provided by the International Skin Imaging Collaboration (ISIC). The dataset is categorized into the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion
  - The data is balanced across categories, except for melanomas and moles, which have slightly more images.

## Model Summary
- The following is the summary of the final model used for training.
<img width="680" alt="Screenshot 2024-12-16 at 11 42 07 PM" src="https://github.com/user-attachments/assets/0a1b3e74-4809-4543-8b7d-b1a584e1c443" />


## Model Evaluation
- ![image](https://github.com/user-attachments/assets/9431aa9d-7eff-4917-a75b-39723dde9e79)


## Conclusions
- Dropouts and batch norm were instrumental in mitigating overfitting during the model training phase.
- Data augmentation techniques improved the model’s ability to generalize and perform well on unseen data.
- The custom CNN model achieved high accuracy in classifying melanoma among other skin conditions.


## Technologies Used
- tensorflow - version 2.16.2
- keras - version 3.7.0
- pandas - version 2.2.3

## Acknowledgements
- This project was done as part of IIIT Banglore's post graduate diploma in ML&AI. Credit goes to IIITB for the assignment and the provided data


## Contact
Created by [@skelkar8] - feel free to contact me!
