# Lung Cancer Detection and Classification through CT Images
## Introduction
Lung cancer is one of the most prevalent types of cancer worldwide. Early detection of lung cancer can significantly improve patient survival rates. Computed tomography (CT) imaging is an effective diagnostic imaging method for detecting lung cancer. However, analyzing CT images can be challenging due to their complexity and variations.
Deep learning is a branch of artificial intelligence that can be utilized for medical image analysis. Convolutional neural networks (CNNs) have proven to be effective in classifying medical images.
This project proposes constructing a deep learning model to detect and classify lung cancer from CT images. The model will utilize CNNs to extract features from CT images and then apply machine learning algorithms to classify cancer cells.

## The research methodology includes
1. Collection and preprocessing of CT image datasets from lung cancer patients.
2. Apply CNN models to classify lung cancer cells from CT images. CNN models includes: Alexnet, DenseNet121, Lenet5, ResNet50, VGG16.
3. Applying machine learning algorithms to classify cancer cells.
4. Evaluating the model's effectiveness on real-world datasets.


## Dataset
### Begin: Describing early-stage cancer
|![begin1](/Data/begin/Bengin%20case%20(1).jpg)|![begin2](/Data/begin/Bengin%20case%20(2).jpg)|
|----------------------|----------------------|
### Malignants: Describing malignant cancer
|![Malignants1](/Data/malignants/Malignant%20case%20(1).jpg)|![beginMalignants2](/Data/malignants/Malignant%20case%20(10).jpg)|
|----------------------|----------------------|
### Normal: Describing the normal stage
|![begin1](/Data/normal/Normal%20case%20(1).jpg)|![begin1](/Data/normal/Normal%20case%20(10).jpg)|
|----------------------|----------------------|

## Result
The effectiveness of each model when classifying lung cancer:
| Model        | Accuracy  |Precision|Recall|F1-score|
|--------------|--------------|---------|-------|--------|
| DenseNet121  | 0.97         |0.97|0.94|0.95|
| Lenet5       | 0.97         |0.96|0.97|0.96|
| ResNet50     | 0.99         |0.99|0.99|0.99|
| VGG16        | 0.98         |0.98|0.94|0.96|


## Applications of the project include
* Supporting lung cancer diagnosis.
* Monitoring the cancer treatment process.
