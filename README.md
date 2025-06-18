<<<<<<< HEAD
=======
# Super Resolution Model
This project implements a CNN based image super-resolution model, designed to work with RGB images.

## 📐SRCNN Model Architecture
- Input: RGB low-resolution image  
- Layers:
  - Conv2D (64 filters, 3×3) + ReLU
  - Repeated Conv2D blocks with ReLU (configurable depth)
  - Final Conv2D (3 filters, 3×3)
  - Skip connection: input added back to output (residual learning)

## Dependencies
```bash
pip install tensorflow numpy opencv-python
```

## Reference
- **SRCNN** — Dong et al. (2014): [Paper](https://arxiv.org/abs/1501.00092)
>>>>>>> 637831838be52ee10b1949b2e9ba2c0d5b57256c
