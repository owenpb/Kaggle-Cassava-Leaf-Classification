# [Kaggle-Cassava-Leaf-Classification](https://www.kaggle.com/c/cassava-leaf-disease-classification)

## Notebook: [kaggle_cassava_leaf_classification.ipynb](https://github.com/owenpb/Kaggle-Cassava-Leaf-Classification/blob/main/kaggle_cassava_leaf_classification.ipynb)

### Identifing the type of disease present on a Cassava Leaf image

In this competition, we explore a dataset consisting of 21,367 labeled photographs of Cassava leaves collected during a regular survey in Uganda. Images were crowdsourced from farmers and annotated by experts at the National Crops Resources Research Institute (NaCRRI) in collaboration with the AI lab at Makerere University, Kampala.

Our task is to classify each image into one of 5 categories: one indicating a healthy leaf, and the remaining four categories indicating different diseases. These are Cassava Bacteria Blight (CBB), Cassava Brown Streak Disease (CBSD), Cassava Green Mottle (CGM), and Cassava Mosaic Disease (CMD).

The notebook linked above contains:

1. Exploratory Data Analysis (EDA) of the Cassava leaf image dataset, and demonstration of image augmentation techniques using the Albumentations library.

2. Training and finetuning a ResNet-152 model from torchvision (PyTorch) with GPU P100 accelerator.

3. Ensembling out-of-fold (OOF) predictions with test time augmentations (TTA).

4. Preparing our final submission for this competition.

The notebook contains a link to open in Google Colab, where it can be run with GPU acceleration enabled. Alternatively, separate training and inference notebooks can be forked and run on Kaggle by following these links:

[Finetuned ResNet-152 Model: EDA and Training [1/2]](https://www.kaggle.com/code/owenpb/finetuned-resnet152-model-eda-and-training-1-2/edit/run/162794273)

[Finedtuned ResNet-152 Model: TTA and Inference [2/2]](https://www.kaggle.com/code/owenpb/finetuned-resnet152-model-tta-and-inference-2-2)

To download the full image dataset (6.19 GB), and for additional details and background information related to this dataset, see the Kaggle competition page at [kaggle.com/c/cassava-leaf-disease-classification](kaggle.com/c/cassava-leaf-disease-classification). 
