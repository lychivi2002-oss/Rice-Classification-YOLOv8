# Rice-Classification-YOLOv8
Classifying 8 classes of Vietnamese rice (4 types: ST25, ST24, ST21, etc.) captured with both polarized and non-polarized imaging.
# Vietnamese Rice Classification using YOLOv8

This project utilizes the **YOLOv8** model (built on PyTorch) to detect and classify 8 distinct classes of Vietnamese rice.

## 🎯 Problem Statement

The goal is to build a computer vision model capable of distinguishing between 4 popular types of Vietnamese rice (ST25, ST24, ST21, etc.) from images.

## 🍚 Dataset

* **Data Source:** A custom-collected dataset.
* **Methodology:** The dataset includes 4 types of rice. Each type was captured using two different imaging methods:
    1.  Non-polarized imaging
    2.  Polarized imaging
* **Total Classes:** This results in a total of **8 distinct classes** for the model to learn (4 rice types x 2 imaging methods).

## 🛠 Methodology & Tech Stack

1.  **Annotation:** Labeled the dataset using bounding boxes to identify the rice kernels.
2.  **Model:** Utilized the **YOLOv8** model from the Ultralytics library.
3.  **Training:** Fine-tuned the model on the custom 8-class labeled dataset.
4.  **Core Technologies:**
    * Python
    * PyTorch
    * Ultralytics (YOLOv8)
    * Google Colab

## 📈 Results

The fine-tuned model achieved an excellent result on the test set:

* **Accuracy / mAP:** **99.1%**

*(You can also drag-and-drop your result image here to display it)*

## 🚀 View the Notebook

The entire process, including data handling, training, and evaluation, is documented in the Google Colab Notebook.

➡️ **Click here to see the full notebook: [YOLOv8_Seg.ipynb](https://github.com/lychivi2002-oss/Rice-Classification-YOLOv8/blob/main/YOLOv8_Seg.ipynb)**
