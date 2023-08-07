<div align="center">
  <img src="https://github.com/himisir/medical-image-generation-with-gans-tensorflow/blob/main/src/img2.png" width="800px" />
</div>

<h1 align="center">Generative Adversarial Networks (GANs) for Synthetic Pneumonia-Positive X-ray Images</h1>

<p align="center">
  <a href="#about">About</a> •
  <a href="#configuration-details">Configuration Details</a> •
  <a href="#results">Results</a> •
  <a href="#future-work">Future Work</a> •
  <a href="#run-on-kaggle">Run on Kaggle</a>
</p>

---

## About

This notebook uses Generative Adversarial Networks (GANs) to generate synthetic pneumonia-positive X-ray images. The goal is to generate hyperrealistic images that can be used to augment the existing dataset for better model training. The current demo has yet to achieve this goal, but the plan is to explore the application of Generative Adversarial Networks (GANs) to generate new and accurate medical images in the future.

**The primary aim is to train the GAN to generate highly realistic synthetic X-ray images that closely resemble the real ones in the dataset. These synthetic images can then be utilized for future data augmentation.**

As of the current demonstration, the generated images might not yet reach clinically accurate levels. However, **a more complex architecture has the potential to generate highly realistic and accurate pneumonia-positive X-ray images.** The synthetic images produced can effectively augment existing datasets of pneumonia-positive X-rays, leading to improved accuracy and performance of pneumonia detection models.

---

## Configuration Details

* :rocket: GPU Accelerator: T4 (2 units)
* :file_folder: Dataset: **[Chest X-ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)** 
* :bar_chart: Dataset Size: 3875
* :frame_photo: Output Image Size: 512x512
* :gear: Optimizer: Adam
* :chart_with_upwards_trend: Learning Rate: 0.0002
* :fishing_pole_and_fish: Loss Function: Binary Crossentropy
* :artificial_satellite: Generator: 1 Dense, 6 Convolutional Transpose, 1 Convolutional
* :mag: Discriminator: 4 Convolutional, 4 MaxPooling, 1 Flatten, 2 Dense

---

## Run on Kaggle

To run this project on Kaggle, click the button below:

[![Open in Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/code/asif00/medical-image-generation-with-gans)

---

## Results

<details>
<summary>Click here for results!</summary>
<br>

<div align="center">
  <img src="https://github.com/himisir/medical-image-generation-with-gans-tensorflow/blob/main/src/img1.png" width="800px" />
</div>
<div align="center">
  <img src="https://github.com/himisir/medical-image-generation-with-gans-tensorflow/blob/main/src/img2.png" width="800px" />
</div>
</details>

---

## Future Work

- :building_construction: Explore more complex architectures for GANs.
- :microscope: Generate highly realistic and accurate pneumonia-positive X-ray images.
- :1234: Augment existing datasets of pneumonia-positive X-rays.

