<div align="center">
  <img src="https://github.com/username/repo-name/blob/main/images/image1.png" width="400px" />
  <img src="https://github.com/username/repo-name/blob/main/images/image2.png" width="400px" />
</div>

<h2 align="center">Generative Adversarial Networks (GANs) for Synthetic Pneumonia-Positive X-ray Images</h2>

<p align="center">
  <a href="#about">About</a> •
  <a href="#configuration-details">Configuration Details</a> •
  <a href="#results">Results</a> •
  <a href="#future-work">Future Work</a>
</p>

---

## About

This notebook uses Generative Adversarial Networks (GANs) to generate synthetic pneumonia-positive X-ray images. The goal is to generate hyperrealistic images that can be used to augment the existing dataset for better model training. The current demo has yet to achieve this goal, but the plan is to explore the application of Generative Adversarial Networks (GANs) to generate new and accurate medical images in the future.

**The primary aim is to train the GAN to generate highly realistic synthetic X-ray images that closely resemble the real ones in the dataset. These synthetic images can then be utilized for future data augmentation.**

As of the current demonstration, the generated images might not yet reach clinically accurate levels. However, **a more complex architecture has the potential to generate highly realistic and accurate pneumonia-positive X-ray images.** The synthetic images produced can effectively augment existing datasets of pneumonia-positive X-rays, leading to improved accuracy and performance of pneumonia detection models

The main takeaway from this project is the potential of GANs in medical image generation for data augmentation, enabling the development of more effective diagnostic tools for pneumonia and other medical conditions.

## Configuration Details

* GPU Accelerator: T4 (2 units)
* Dataset: **[Chest X-ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)** 
* Dataset Size: 3875
* Output Image Size: 512x512
* Optimizer: Adam
* Learning Rate: 0.0002
* Loss Function: Binary Crossentropy
* Generator: 1 Dense, 6 Convolutional Transpose, 1 Convolutional
* Discriminator: 4 Convolutional, 4 MaxPooling, 1 Flatten, 2 Dense

---

## Results

<details>
<summary>Click here for results!</summary>
<br>

![image.png](attachment:59538bc3-73cd-4f39-93e1-f5d506f11cde.png)
![image.png](attachment:8931759e-6b2b-4cf4-808a-39c61aafeba2.png)

</details>

---

## Future Work

- Explore more complex architectures for GANs.
- Generate highly realistic and accurate pneumonia-positive X-ray images.
- Augment existing datasets of pneumonia-positive X-rays.
