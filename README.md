# Melanoma Detection
> CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 The dataset provided is imbalanced, so we have balanced data using augmentor library from python.
- Conclusion 2 Model training accuracy and validation accuracy are good, thus model is not overfitting. But test results are not as expected.
- Conclusion 3 Increasing test dataset helps to make proper conclusion on why test accuracy is low.
- Conclusion 4 The classes 'melanoma', 'nevous' image samples are almost similar so these classes are overlapping each other when doing predictions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.11
- keras - version 2.x
- tensorflow - version 2.x.x

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by IIITB
- References if any Upgrad learning platform
- This project was based on [this tutorial](https://learn.upgrad.com/).


## Contact
Created by [@bhanu481] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->