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
```pip install tensorflow numpy opencv-python
