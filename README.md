# Deep Computer Vision: The Simpsons Character Classifier

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![Framework](https://img.shields.io/badge/Framework-Caer-orange.svg)](https://github.com/jason-dsouza/caer)

An end-to-end computer vision pipeline and custom Deep Learning classifier capable of identifying characters from *The Simpsons*. This project demonstrates production-grade image preprocessing, architectural design using convolutional layers, and multi-class target evaluation using standard Python scripts and Jupyter Notebooks.

---

## 🚀 Architectural Overview & Engineering Highlights

This repository showcases the practical integration of traditional computer vision workflows with modern deep learning paradigms:

* **Dynamic Data Pipeline:** Built custom image parsing workflows using `OpenCV` to handle variations in raw datasets, implementing standardized spatial scaling ($64 \times 64$ pixels) and channel normalization to optimize feature propagation.
* **Custom CNN Architecture:** Leveraged the `Caer` library to implement a highly performant, custom-layered Convolutional Neural Network (CNN) specifically tailored to combat data scarcity and class imbalances.
* **Efficient Memory Management:** Configured iterative generators to stream image matrices efficiently into memory, minimizing the CPU/GPU memory footprint during complex batch transformations.

---

## 🛠️ Tech Stack & Dependencies

* **Core Language:** Python 3.8+
* **Computer Vision Framework:** OpenCV (`opencv-python`)
* **Deep Learning Frameworks:** `caer`
* **Numerical & Data Frameworks:** NumPy, Matplotlib

---

## 📂 Project Repository Files

* `simpsons_classifier.ipynb`: Complete interactive walkthrough including data visualization, training logs, and evaluation plots.
* `simpsons_classifier.py`: Production-ready standalone script containing the pipeline execution.

---

## ⚙️ Getting Started & Replication

### 1. Environment Setup
Clone the repository and install the required dependencies:
```bash
cd simpsons-opencv-classifier
pip install -r requirements.txt
