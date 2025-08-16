# Semantic Segmentation Project

This project aims to explore deep learning-based image segmentation
methods. Different architectures were implemented to solve semantic
segmentation problems, and their results were compared.

## 📌 Models Used

The following deep learning-based segmentation architectures were
implemented in this project:

-   **FCN (Fully Convolutional Network)**
-   **UNet**
-   **PSPNet (Pyramid Scene Parsing Network)**
-   **DeepLabv3**

Each model was trained, validated, and tested, and their results were
recorded.

## ⚙️ Technologies

-   **Python 3.x**
-   **PyTorch** -- Model definition and training
-   **Torchvision** -- Pretrained models and data transformations
-   **Matplotlib & Seaborn** -- Visualization
-   **NumPy & Pandas** -- Data processing

## 📊 Training Process

-   The dataset was split into **80% training** and **20% validation**.\
-   DataLoader was used to efficiently feed the data to the models.\
-   **Early Stopping** was applied to avoid overfitting.\
-   At the end of training, metrics such as **Precision, Recall,
    F1-Score, Accuracy, and IoU** were calculated.

## 🖼️ Visualization of Results

The outputs of the models were visualized by showing the original
images, ground truth masks, and predicted masks side by side.

## 📈 Evaluation

-   **FCN**: Simple architecture, fast, but lower accuracy compared to
    other models.\
-   **UNet**: Performed particularly well in medical imaging tasks.\
-   **PSPNet**: Achieved better segmentation results thanks to
    multi-scale feature extraction.\
-   **DeepLabv3**: Achieved the **highest performance** among the
    models.
