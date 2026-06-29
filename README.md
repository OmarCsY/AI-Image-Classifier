# Image Classification (Dog Show) - AI Image Classifier

A Command Line Interface (CLI) application developed to classify images of dogs according to their breed using **Deep Learning**. This project was built as a key capstone project for the **Udacity Future AWS AI Scientist** program.

This project utilizes **Transfer Learning** by leveraging pre-trained CNN architectures (ResNet, AlexNet, and VGG) to analyze and classify input images. It successfully optimizes classification accuracy against runtime, demonstrating expertise in computational efficiency and model evaluation.

---

## 🚀 Key Features

* **Multi-Model Support:** Compare performance between different architectures (`ResNet`, `AlexNet`, `VGG`).
* **Command Line Arguments:** Flexible input handling for directory paths and model selection.
* **Performance Metrics:** Calculates and reports accuracy statistics (Dog vs. Not-Dog, Breed Accuracy).
* **Batch Processing:** Capable of processing batches of images efficiently using the provided shell and batch scripts.

---

## 🛠️ Tech Stack

* **Language:** Python 3
* **Libraries:** PyTorch, Torchvision, PIL (Pillow)
* **Concepts:** Convolutional Neural Networks (CNN), Transfer Learning, Data Augmentation

---

## 💻 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/OmarCsY/AI-Image-Classifier.git](https://github.com/OmarCsY/AI-Image-Classifier.git)
   cd AI-Image-Classifier

---

## 🏃‍♂️ Usage

To run the image classifier, use the following command in your terminal:

> *Note: You can change the `--arch` argument to `vgg` or `alexnet` to test different models.*

```bash
python check_images.py --dir pet_images/ --arch resnet --dogfile dognames.txt
```

To run batch processing for all models automatically, you can use the provided scripts:
```bash
sh run_models_batch.sh
```

---

## 🎓 Acknowledgements

This project was implemented as part of the **Udacity AI Programming with Python Nanodegree**.

* Starter code and dataset provided by **Udacity**.
* Core implementation, model logic, and result analysis developed by **Omar Al-Ali**.
