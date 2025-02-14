# Code Repository for "Dynamically Scaled Temperature in Self-Supervised Contrastive Learning"
## Accepted to IEEE Transactions on Artificial Intelligence

- *smallscale* directory contains the code to reproduce our results on CIFAR datasets
- *imagenet* directory contains code to reproduce our results on ImageNet100 and ImageNet1K datasets
- *SimCSE* directory contains the code from the original repository with the same name, modified to incorporate DySTreSS and MACL.

- SimCSE codes were run on NVIDIA A5500 GPU
- smallscale codes were run on NVIDIA 2080Ti
- experiments on ImageNet100 codes were run on NVIDIA P100 GPU
- experiments on ImageNet1K were run on NVIDIA A5000 GPU


```
S. Manna, S. Chattopadhyay, R. Dey, U. Pal and S. Bhattacharya,
"Dynamically Scaled Temperature in Self-Supervised Contrastive Learning"
in IEEE Transactions on Artificial Intelligence, vol. 1, no. 01, pp. 1-10,
Aug. 2025, doi: 10.1109/TAI.2024.3524979.

Abstract: In contemporary self-supervised contrastive algorithms like SimCLR,
MoCo, etc., the task of balancing attraction between two semantically similar
samples and repulsion between two samples of different classes is primarily
affected by the presence of hard negative samples. While the InfoNCE loss has
been shown to impose penalties based on hardness, the temperature hyper-parameter
is the key to regulating the penalties and the trade-off between uniformity and
tolerance. In this work, we focus our attention on improving the performance
of InfoNCE loss in self-supervised learning by proposing a novel cosine similarity
dependent temperature scaling function to effectively optimize the distribution of
the samples in the feature space. We also provide mathematical analyses to support
the construction of such a dynamically scaled temperature function. Experimental
evidence shows that the proposed framework outperforms the contrastive loss-based
SSL algorithms. Our code is available at https://www.github.com/sadimanna/DySTreSS.
URL: https://doi.ieeecomputersociety.org/10.1109/TAI.2024.3524979

```
