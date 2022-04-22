# Melanoma Detection Assignment
> Multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [Problem Statement](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We tried different models with optimizers (sgd, adams, adagrad) and epochs (30,50,30) . By adding augmented images which inturn helped in handling class imbalance , we mitigated/addressed the problem of overfitting . 
- Out of all the models the performance was decent for the model with Adam's optimizer . 
- The model had a train accuracy of ~90% while the validation accuracy was about ~80% . 
- This model learns rapidly (increase in training and validation accuracy)for the first 20 epochs , but after this the learning becomes slow .

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensor Flow
- Keras
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@SanketRBhave] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->