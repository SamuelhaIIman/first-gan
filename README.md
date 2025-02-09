# first-gan (Generative Adversarial Network)

This project implements a simple Generative Adversarial Network (GAN) to generate handwritten digits similar to the MNIST dataset using PyTorch.

---

## Features

- Uses a Discriminator and a Generator network
- Trains on the MNIST dataset
- Logs training progress using TensorBoard
- Saves generated images for visualization

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/first-gan.git
cd first-gan
```
2. Install dependencies:
```bash
pip install torch torchvision matplotlib tensorboard
```

---

## Usage

Run the training script:
```bash
python first-gan.py
```

---

## Visualizing Results

After starting training, you can visualize progress:
```bash
tensorboard --logdir=runs/GAN_MNIST
```
Then, open the provided URL in a browser (e.g., http://localhost:6006/).

---

## Requirements

- Python 3.7+
- PyTorch
- Torchvision
- Matplotlib
- TensorBoard