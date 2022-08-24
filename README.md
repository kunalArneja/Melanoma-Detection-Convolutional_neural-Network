# Project Name

Multiclass classification model using a custom convolutional neural network in TensorFlow.

## Problem Statement

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Model 1 - with dropout, no l2 regularisation, no batch normalisation
- Result - train accuracy ~, while validation accuracy was ~. So the model was overfitting.
- Model 2 - applied data augumentation strategy - with dropout, l2 regularisation, and batch normalisation
- Result - train accuracy ~, while validation accuracy was ~. So the model was overfitting less but the validation accuracy were still lower.
- Model 3 - applied augumentation strategy to reduce class imbalances
- Result - train accuracy ~, while validation accuracy was ~.

## Contact

Created by [@kunalArneja] - feel free to contact me!
