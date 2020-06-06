# Semantically Aligned Bias Reducing Zero-Shot Learning
Implementation of **Alignment GAN using Spectral Normalization (AGSN)** for Generalized Inductive Zero-Shot Learning in PyTorch.

**AGSN** takes motivation from the models [SABR](https://arxiv.org/pdf/1904.07659.pdf) by *Paul et al.*, [Spectral Normalization](https://arxiv.org/pdf/1802.05957.pdf) by *Miyato et al.*, [CADA-VAE](https://arxiv.org/pdf/1812.01784.pdf) by *Schonfeld et al.*, [GDAN](https://arxiv.org/pdf/1811.04857.pdf) by *Huang et al.* and many others.

## Prerequisites
Compatible with Python 3.x, PyTorch 1.5.

## Training the model
1. Download datasets for zero shot learning from http://datasets.d2.mpi-inf.mpg.de/xian/xlsa17.zip.
2. Place the datasets in some folder and change the `data_root` string accordingly.
3. If the `pretrained` flag is set to *True*, then the trained models will be loaded from the path specified by `model_path`.

The default dataset used is **CUB**.

Here are all the [pretrained models](https://drive.google.com/drive/folders/1D-IvKQlr7EJmk8nK0FfuBsyYTwzguwon?usp=sharing).
