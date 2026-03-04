Agricultural crops image classification dataset is available at: https://www.kaggle.com/datasets/mdwaquarazam/agricultural-crops-image-classification/data
This dataset contains 30 different types of crop images in separate folders.

1. Exploratory Data Analysis (EDA)
2. Implementation of ****CNN**** with proper architecture (Fully Connected Layers, Convolution Layers, Pooling Layers etc.):
- GoogleNetv3 (also known as InceptionV3)

3. Implementation of various architectures with different ****activations functions**** (Sigmoid, ReLU, Leaky ReLU, ELU):
- Softmax
- ReLU

4. Initializing ****weights**** with different methods (Small random numbers, Xavier, Kaiming/MSRA):
- Xavier initialization (also known as Glorot Uniform): Acc.: 73.61%
- He normal: Acc.: 76.39%

5. Applying ****regularization methods**** (L1, L2, Dropout, Batch normalization):
- Dropout: preventing overfitting. Acc.: 73.61%
- Batch Normalization: normalizing input data. Acc.: 36.11%

6. ****Results****


| Model                   | Accuracy   |
| ------------------------------ | ---------- |
| CNN (Baseline)                 | 72.21%     |
| CNN + Softmax                  | 70.83%     |
| CNN + ReLU                     | 5.56%      |
| CNN + Dropout                  | 73.61%     |
| CNN + Batch Normalization      | 36.11%     |
| CNN + Xavier Initialization    | 73.61%     |
| CNN + He Normal Initialization | **76.39%** |





