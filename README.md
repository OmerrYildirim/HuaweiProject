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
<img width="916" height="374" alt="image" src="https://github.com/user-attachments/assets/6e6c1c5a-8c8a-42aa-b8db-573061e0609a" />
<img width="916" height="374" alt="image" src="https://github.com/user-attachments/assets/e6d69387-4ec3-4d1f-99a9-ca3ada92a95e" />
<img width="916" height="374" alt="image" src="https://github.com/user-attachments/assets/972d0fe1-d4cd-44e3-ad87-092d2e3456a8" />
<img width="916" height="374" alt="image" src="https://github.com/user-attachments/assets/1b60ddf9-9f74-41fb-997a-42240619a5fd" />
<img width="916" height="374" alt="image" src="https://github.com/user-attachments/assets/fd9f69e8-a33f-4825-a123-9735b25bdd21" />



## 📈 Evaluation

-   **FCN**: Simple architecture, fast, but lower accuracy compared to
    other models.\
-   **UNet**: Performed particularly well in medical imaging tasks.\
-   **PSPNet**: Achieved better segmentation results thanks to
    multi-scale feature extraction.\
-   **DeepLabv3**: Achieved the **highest performance** among the
    models.
