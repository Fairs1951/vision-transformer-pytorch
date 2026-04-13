# Vision Transformer (ViT) PyTorch

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch 2.0+](https://img.shields.io/badge/pytorch-2.0+-red.svg)](https://pytorch.org/)

A production-grade implementation of the Vision Transformer (ViT) architecture from scratch using PyTorch.

## Features
- Modular Patch Embedding
- Multi-Head Self-Attention (MHSA)
- Transformer Encoder Blocks
- Support for Pre-trained weights and custom datasets

## Installation
```bash
pip install -r requirements.txt
```

## Usage
```python
from vit import ViT
model = ViT(image_size=224, patch_size=16, num_classes=1000)
```