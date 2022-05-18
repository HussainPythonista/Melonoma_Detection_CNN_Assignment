# Melonoma Detection 

## Problem statement: 
  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
  
There are 9 types of Skin cancer:
* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion

## Approach:
* Build our first model with basic parameters with out any tuning
* Checking underfit and overfitting
* Handled overfiting with class rebalance method

## Results:
* My final Model achieve the accuracy as 94% in train and 84% in validation

* And this result is far more better than previous accuracy 75% as train and 55% as val, because the train and val accuracy is very low and it is overfitting as well

* This shows that handling Data imbalance increased my model accuracy

* The final model accuracy between Val and Train is 10%,this is also indication of overfitting but this is not that much high as previous one.

* We can achieve better results and reduce overfit as well,but it need extra computationl power, so I leave as it is

It show the class rebalance increase my accuracy rat

## Technologies Used
* keras
* tensforflow
* PIL
* matplotlib
