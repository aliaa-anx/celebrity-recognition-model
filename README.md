# Celebrity Recognition Model

This repository houses a comparative study of various deep learning models applied to the task of celebrity recognition and face detection. The project is structured to clearly separate exploratory notebooks, training scripts, and finalized model assets.

---

##  Project Overview

The goal of this project is to implement and evaluate several popular Convolutional Neural Network (CNN) architectures, including **Inception V1**, **ResNet**, and **VGG-19**, **MobileNet** to determine the most effective model for accurately identifying and localizing celebrity faces in images.

### Key Features:

* **Structured Organization:** Clear separation of code by function (notebooks, scripts, models).
* **Model Comparison:** Implementation details and performance metrics for multiple CNN architectures.
* **Transfer Learning:** Use of pre-trained weights for feature extraction and fine-tuning.

---

##  Repository Structure

The project follows standard conventions to keep the different assets organized:

| Directory | Purpose | Contents |
| :--- | :--- | :--- |
| **`notebooks/`** | Contains all exploratory work, data cleaning, and model training notebooks. | `inception_v1.ipynb`, `vgg_19_model.ipynb`, etc. |

### Notebook Summary

| File | Model / Task | Description |
| :--- | :--- | :--- |
| `notebooks/inception_v1.ipynb` | **Inception V1** | Full training and evaluation workflow for the Inception V1 model. |
| `notebooks/vgg_19_model.ipynb` | **VGG-19** | Implementation and training details for the VGG-19 architecture. |
| `notebooks/resnet_detection.ipynb` | **ResNet** | Specific notebook focusing on object detection or localization using a ResNet backbone. |
| `notebooks/MobileNetV2.ipynb` | **MobileNetV2** | Specific notebook focusing on object detection or localization using a mobilenet backbone. |
| `notebooks/detection_exploration.ipynb` | **data processing** | Initial exploration, data loading, and augmentation and processing for detection tasks. |

---

##  Getting Started

### Prerequisites

To run the notebooks and scripts locally, you will need:

* Python 3.x
* TensorFlow / Keras
* Jupyter (to run the notebooks)


### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/alaa-anx/celebrity-recognition-model.git](https://github.com/aliaa-anx/celebrity-recognition-model.git)
    cd celebrity-recognition-model
    ```
2.  **Install dependencies:**
    ```bash
    pip install tensorflow keras numpy pandas jupyter matplotlib
    ```

---

##  How to Contribute


* **Branching:** All new features or fixes must be developed on a dedicated feature branch (e.g., `feature/new-model`).
* **Structure:** Place all new notebooks in `notebooks/` 
* **Documentation:** Update this `README.md` if you introduce major changes or new models.
