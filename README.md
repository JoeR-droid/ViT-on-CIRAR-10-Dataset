# ViT-on-CIFAR-10-Dataset
In this project I built a Vision Transformer from scratch in PyTorch and trained it on CIFAR-10. Since CIFAR-10 images are only 32×32, I reduced the patch size from the standard 16×16 to 4×4 to generate enough tokens for the attention mechanism to be fully utilized. The model hit 80.99% test accuracy in eighteen minutes on dual T4 GPUs.
