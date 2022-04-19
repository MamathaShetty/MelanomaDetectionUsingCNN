# Melanoma Detection Using CNN Classifier

## Problem statement

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Summary

1. The final model shows that model is not overfit. This is because, we were able to resolve the class rebalance issue by adding more samples of images using Augumentor.
2. The model is able to predict well by using multiple layers of Convolution 2D (Upto 256).
3. Further, the model is able to generalize well by using Batch Normalization in multiple layers.
4. In addition to the above, dropout (0.5) has been added to generalize the model.
5. The training accuracy has improved with a value of 0.8863 whereas validation accuracy is now 0.8374.
6. The training loss is reduced to 0.2916 and validation loss is reduced to 0.5235
7. The model can be further improved by adding more images.
