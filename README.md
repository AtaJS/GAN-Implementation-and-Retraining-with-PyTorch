## GAN Implementation and Retraining with PyTorch

This project implements a Generative Adversarial Network (GAN) using PyTorch and demonstrates its training and evaluation process. The project includes building a DCGAN-inspired architecture, loading pre-trained weights, and retraining the model on a new dataset.

**Project Highlights:**

* **DCGAN Architecture**: Implementation of both Generator and Discriminator models based on the Deep Convolutional GAN (DCGAN) architecture principles.
* **Pre-trained Weights**: Loading and utilizing pre-trained weights for faster convergence and improved initial generation quality, originally trained on the CelebA dataset.
* **Transfer Learning**: Retraining the GAN on the AnimeFace dataset, demonstrating the adaptability of pre-trained GANs to new image domains through transfer learning.
* **PyTorch Workflow**: Full PyTorch implementation including model definition, dataset loading, training loops, loss functions, and optimizers for both Generator and Discriminator.
* **Visualization Tools**: Integrated visualizations of generated images and training losses to monitor GAN performance and training progress.

**Datasets:**

* **CelebA (Pre-training)**:  Used for obtaining pre-trained weights, this large-scale face attributes dataset facilitates initial model capabilities in generating realistic faces.
* **AnimeFace (Retraining)**: The target dataset for transfer learning, consisting of anime faces used to adapt the pre-trained GAN to a new style of image generation.

**Libraries Used:**

* Python
* NumPy
* Matplotlib
* Torch
* Torchvision
* IPython

**Author:** Ata Jodeiri Seyedian
**Emails:** ata.jodeiri@student.oulu.fi, sataseyedian@gmail.com
