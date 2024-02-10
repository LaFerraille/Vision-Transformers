# Vision Transformers (ViT) Exploration Repository

Welcome to the Vision Transformers (ViT) Exploration repository! This project is dedicated to understanding and implementing the Vision Transformer (ViT) architecture through comprehensive experiments and insightful demonstrations. Our focus spans from straightforward implementations on well-known datasets like MNIST and CIFAR to tackling the challenging scenario of ovarian-subtype classification.

## Introduction

The transformer architecture, initially revolutionizing Natural Language Processing (NLP) with its self-attention mechanism, has made its way into Computer Vision. The pivotal moment came with Dosovitskiy et al.'s presentation at ICLR 2021, introducing the Vision Transformer (ViT) for image recognition at scale, proposing a novel approach where "An Image is Worth 16x16 Words."

## Objectives

- **ViT Implementation**: From scratch implementation of the ViT architecture to train on MNIST and CIFAR10, benchmarking against the traditional ResNet model.
- **Attention Visualization**: Demonstrating the trained ViT's ability to focus on specific image parts through attention maps.
- **Ovarian Cancer Classification**: Employing a pretrained ViT model for the precise classification of ovarian cancer subtypes using histopathology images, showcasing the model's capability to process high-dimensional image data.

## Experiments

### MNIST/CIFAR Experiments

Our experiments replicate the original ViT idea, training from scratch and comparing its performance with a fine-tuned vanilla ResNet model. The attention maps generated provide a visual insight into the model's focus areas.

### Ovarian Cancer Subtype Classification

We applied a pretrained ViT model to classify ovarian cancer subtypes, leveraging its ability to understand global image context. The model, pretrained on the ImageNet dataset, was adapted to handle the high dimensionality of histopathology images, demonstrating its robustness in medical imaging applications.

## Getting Started

To begin exploring the Vision Transformer with our experiments:
1. **Clone this repository** to access all experimental notebooks and setup instructions.
2. **Follow the setup guides** within each experiment folder for detailed instructions on environment preparation and dataset handling.

