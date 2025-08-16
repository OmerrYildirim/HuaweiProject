🧠 Semantic Segmentation on LoveDA Dataset
📌 Project Overview

This project focuses on semantic segmentation using multiple deep learning models on the LoveDA dataset.
The aim is to assign each pixel of an aerial image to one of the land-cover categories, such as Building, Road, Water, Forest, Agriculture, Barren, Background.

We implemented and compared four state-of-the-art segmentation architectures and evaluated their performance both quantitatively and qualitatively.

🚀 Models Implemented

The following segmentation models were trained and compared:

UNet

FCN (ResNet50 backbone)

DeepLabv3 (ResNet50 backbone)

PSPNet (ResNet50 backbone)

⚙️ Methodology

Dataset:

LoveDA dataset with images and segmentation masks.

Images resized to 256x256.

Masks resized with nearest-neighbor interpolation to preserve class integrity.

Data split: 80% training, 20% validation.

Training Setup:

Framework: PyTorch

Loss Function: CrossEntropyLoss

Optimizer: Adam

Early stopping applied to avoid overfitting.

Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

IoU (Intersection over Union)

Visualization:

Side-by-side display of:

Original Image

Ground Truth Mask

Predicted Mask

Custom color palette and legend for class interpretation.

📊 Results
Model	Accuracy	F1 Score	Precision	Recall	IoU
UNet	0.8146	0.8123	0.8345	0.8092	0.6951
FCN-ResNet50	0.8948	0.9049	0.9046	0.9052	0.8292
DeepLabv3	0.8939	0.9020	0.8938	0.9113	0.8240
PSPNet	0.8214	0.8398	0.8410	0.8416	0.7302
