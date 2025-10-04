# Contents
1. [Introduction](#introduction)
2. [Citation](#citation)
3. [License](#license)

# Introduction

On this web page, I provide the Python implementation of the data augmentation method proposed in my paper titled '[Data Augmentation Using a Convolutional Autoencoder for Age Estimation from Facial Images](https://doi.org/10.33851/JMIS.2025.12.3.95).' Accurate age estimation from facial images plays a pivotal role in various computer vision applications, such as biometric authentication, surveillance, and human-computer interaction. However, the inherent data imbalance across different age ranges—particularly the scarcity of samples in older age groups—poses a significant challenge for model training. In this paper, we propose a data augmentation strategy based on a convolutional autoencoder (CAE) to address this limitation. By generating synthetic facial images through convex interpolation in the latent space, the proposed method compensates for underrepresented age groups while preserving realistic facial features. To ensure age consistency in the augmented data, a convex combination of age labels is used in tandem with the latent representations. Extensive experiments are conducted on the FG-NET dataset using the leave-one-person-out (LOPO) cross-validation protocol. Evaluation results across six convolutional neural network (CNN) models demonstrate that our method consistently improves age estimation performance. Notably, MobileNetV2 with randomly initialized weights achieves a mean absolute error (MAE) of 2.77, outperforming existing state-of-the-art approaches on FG-NET.

# Citation

Please cite the following paper in your publications if they contribute to your research.

```
@article{kwon2025data,
  author={Kwon, Beom},
  journal={Journal of Multimedia Information System},
  title={Data Augmentation Using a Convolutional Autoencoder for Age Estimation from Facial Images},
  year={2025},
  volume={12},
  number={3},
  pages={95--110},
  doi={10.33851/JMIS.2025.12.3.953}
}
```
Paper link: [Data Augmentation Using a Convolutional Autoencoder for Age Estimation from Facial Images](https://doi.org/10.33851/JMIS.2025.12.3.95)

# License

Our codes are freely available for non-commercial use.
