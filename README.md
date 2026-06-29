# AI Image Classifier - Dog Breed Identification

A Command Line Interface (CLI) application developed to classify images of dogs according to their breed using **Deep Learning**.

This project utilizes **Transfer Learning** by leveraging pre-trained CNN architectures (ResNet, AlexNet, and VGG) to analyze and classify input images. It demonstrates the power of using pre-trained neural networks for computer vision tasks with **PyTorch**.

## Key Features 🚀
* **Multi-Model Support:** Compare performance between different architectures:
    * ResNet
    * AlexNet
    * VGG
* **Command Line Arguments:** Flexible input handling for directory paths and model selection.
* **Performance Metrics:** Calculates and reports accuracy statistics (Dog vs. Not-Dog, Breed Accuracy).
* [cite_start]**Batch Processing:** Capable of processing batches of images efficiently using shell scripts[cite: 3].

## 🛠️ Tech Stack
* **Language:** Python 3
* [cite_start]**Libraries:** PyTorch[cite: 49], Torchvision, PIL (Pillow).
* **Concepts:** Convolutional Neural Networks (CNN), Transfer Learning, Data Augmentation.

## 🎓 Acknowledgements 
This project was implemented as part of the **Udacity AI Programming with Python Nanodegree**.
* [cite_start]Starter code and dataset provided by Udacity[cite: 46].
* Core implementation, model logic, and result analysis developed by **Omar Al-Ali**.

## Usage 💻

To run the image classifier, use the following command in your terminal:

```bash
python main.py --dir pet_images/ --arch resnet --dogfile dognames.txt
